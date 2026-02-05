<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic To-Do List</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!--
    NAME - CHANDAN TIWARI
    BRANCH - CSE(DS)
    ROLL NO - 56
    
    -->
    <div class="container">
        <h1>To-Do List</h1>
        <div class="input-container">
            <input type="text" id="task-input" placeholder="Enter a new task">
            <button id="add-task-btn">Add Task</button>
        </div>
        <ul id="task-list"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>

 body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 400px;
}

h1 {
    text-align: center;
    color: #333;
}

.input-container {
    display: flex;
    margin-bottom: 20px;
}

#task-input {
    flex: 1;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 4px 0 0 4px;
}

#add-task-btn {
    padding: 10px 15px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 0 4px 4px 0;
    cursor: pointer;
}

#add-task-btn:hover {
    background-color: #45a049;
}

#task-list {
    list-style-type: none;
    padding: 0;
}

.task-item {
    display: flex;
    align-items: center;
    padding: 10px;
    border-bottom: 1px solid #eee;
}

.task-item.completed .task-text {
    text-decoration: line-through;
    color: #888;
}

.task-text {
    flex: 1;
    cursor: pointer;
}

.delete-btn {
    background-color: #f44336;
    color: white;
    border: none;
    padding: 5px 10px;
    border-radius: 4px;
    cursor: pointer;
}

.delete-btn:hover {
    background-color: #da190b;
}

document.addEventListener('DOMContentLoaded', function() {
    const taskInput = document.getElementById('task-input');
    const addTaskBtn = document.getElementById('add-task-btn');
    const taskList = document.getElementById('task-list');

   
    function addTask() {
        const taskText = taskInput.value.trim();
        if (taskText === '') return;

        const taskItem = document.createElement('li');
        taskItem.className = 'task-item';

        const taskTextElement = document.createElement('span');
        taskTextElement.className = 'task-text';
        taskTextElement.textContent = taskText;
        taskTextElement.addEventListener('click', toggleTask);

        const deleteBtn = document.createElement('button');
        deleteBtn.className = 'delete-btn';
        deleteBtn.textContent = 'Delete';
        deleteBtn.addEventListener('click', deleteTask);

        taskItem.appendChild(taskTextElement);
        taskItem.appendChild(deleteBtn);
        taskList.appendChild(taskItem);

        taskInput.value = '';
    }


    function toggleTask() {
        this.parentElement.classList.toggle('completed');
    }

   
    function deleteTask() {
        this.parentElement.remove();
    }

    
    addTaskBtn.addEventListener('click', addTask);
    taskInput.addEventListener('keypress', function(e) {
        if (e.key === 'Enter') {
            addTask();
        }
    });
});
