&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;
&lt;head&gt;
&lt;meta charset=&quot;UTF-8&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, iniƟal-scale=1&quot;&gt;
&lt;Ɵtle&gt;TaskFlow – ProducƟvity App&lt;/Ɵtle&gt;

&lt;meta name=&quot;descripƟon&quot; content=&quot;TaskFlow helps you manage tasks, track Ɵme,
and boost producƟvity.&quot;&gt;
&lt;link
href=&quot;hƩps://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css&quot;
rel=&quot;stylesheet&quot;&gt;

&lt;link href=&quot;hƩps://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css&quot;
rel=&quot;stylesheet&quot;&gt; &lt;style&gt;
body {
font-family: &quot;Segoe UI&quot;, sans-serif;
padding-top: 70px;
background-color: #f1f5f9;
}
.navbar {
background-color: #ffffff !important;
box-shadow: 0 2px 10px rgba(0,0,0,0.05);
}

.navbar-brand {
color: #1e293b !important;
font-weight: 700;
}

.nav-link {
color: #475569 !important;
font-weight: 500;
}

.nav-link:hover {
color: #38bdf8 !important;
}

.hero {
min-height: 85vh;
display: flex;
align-items: center;
jusƟfy-content: center;
background: linear-gradient(135deg, #1e293b, #0f172a);
color: #ffffff;
text-align: center;
}

.hero h1 {
font-size: 3.2rem;
font-weight: 700;
}

.hero .btn {
background-color: #38bdf8;
border: none;
color: #0f172a;
font-weight: 600;
padding: 12px 40px;
}

/* SecƟons */
secƟon {
padding: 80px 0;
}

h2 {
font-weight: 700;
color: #1e293b;
}
/* Features */
.feature-icon {
font-size: 42px;
color: #38bdf8;
margin-boƩom: 15px;
}

#features .col-md-4 {
display: flex;
flex-direcƟon: column;
align-items: center;
}

/* Pricing */
#pricing {
background-color: #e2e8f0;

}

.pricing-card {
height: 100%;
border: none;
border-radius: 14px;
transiƟon: transform 0.3s ease, box-shadow 0.3s
ease; }
.pricing-card:hover {
transform: translateY(-8px);
box-shadow: 0 20px 40px
rgba(0,0,0,0.1); }

.card-price {
color: #38bdf8;
font-weight: 700;
}

/* Contact */
#contact .form-control {
border-radius: 10px;
}

/* Footer */
footer {
background-color: #0f172a;
color: #cbd5f5;
padding: 20px 0;
text-align: center;
}

&lt;/style&gt;
&lt;/head&gt;

&lt;body&gt;
&lt;!-- Navbar --&gt;
&lt;nav class=&quot;navbar navbar-expand-lg fixed-top&quot;&gt;
&lt;div class=&quot;container&quot;&gt;
&lt;a class=&quot;navbar-brand&quot; href=&quot;#&quot;&gt;TaskFlow&lt;/a&gt;
&lt;buƩon class=&quot;navbar-toggler&quot; type=&quot;buƩon&quot; data-bs-toggle=&quot;collapse&quot;
data-bs target=&quot;#navbarNav&quot;&gt;
&lt;span class=&quot;navbar-toggler-icon&quot;&gt;&lt;/span&gt;
&lt;/buƩon&gt;
&lt;div class=&quot;collapse navbar-collapse&quot; id=&quot;navbarNav&quot;&gt;
&lt;ul class=&quot;navbar-nav ms-auto&quot;&gt;
&lt;li class=&quot;nav-item&quot;&gt;&lt;a class=&quot;nav-link&quot;
href=&quot;#features&quot;&gt;Features&lt;/a&gt;&lt;/li&gt; &lt;li class=&quot;nav-item&quot;&gt;&lt;a class=&quot;nav-
link&quot; href=&quot;#pricing&quot;&gt;Pricing&lt;/a&gt;&lt;/li&gt; &lt;li class=&quot;nav-item&quot;&gt;&lt;a
class=&quot;nav-link&quot; href=&quot;#contact&quot;&gt;Contact&lt;/a&gt;&lt;/li&gt; &lt;/ul&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/nav&gt;

&lt;!-- Hero --&gt;
&lt;secƟon class=&quot;hero&quot;&gt;
&lt;div class=&quot;container&quot;&gt;
&lt;h1&gt;Manage Your Tasks Smarter&lt;/h1&gt;
&lt;p class=&quot;lead mt-3&quot;&gt;Organize work, boost producƟvity, and save Ɵme with
TaskFlow.&lt;/p&gt; &lt;a href=&quot;#pricing&quot; class=&quot;btn btn-lg mt-4&quot;&gt;Get Started&lt;/a&gt;
&lt;/div&gt;
&lt;/secƟon&gt;
&lt;!-- Features --&gt;
&lt;secƟon id=&quot;features&quot;&gt;

&lt;div class=&quot;container&quot;&gt;
&lt;h2 class=&quot;text-center mb-5&quot;&gt;Why Choose
TaskFlow?&lt;/h2&gt; &lt;div class=&quot;row text-center&quot;&gt;
&lt;div class=&quot;col-md-4 mb-4&quot;&gt;
&lt;div class=&quot;feature-icon&quot;&gt;&lt;i class=&quot;bi bi-list-
task&quot;&gt;&lt;/i&gt;&lt;/div&gt; &lt;h5&gt;Task Management&lt;/h5&gt;
&lt;p&gt;Easily create, update, and track tasks in one
place.&lt;/p&gt; &lt;/div&gt;
&lt;div class=&quot;col-md-4 mb-4&quot;&gt;
&lt;div class=&quot;feature-icon&quot;&gt;&lt;i class=&quot;bi bi-clock-
history&quot;&gt;&lt;/i&gt;&lt;/div&gt; &lt;h5&gt;Time Tracking&lt;/h5&gt;
&lt;p&gt;Monitor Ɵme spent on tasks to improve
efficiency.&lt;/p&gt; &lt;/div&gt;
&lt;div class=&quot;col-md-4 mb-4&quot;&gt;
&lt;div class=&quot;feature-icon&quot;&gt;&lt;i class=&quot;bi bi-bar-chart-
line&quot;&gt;&lt;/i&gt;&lt;/div&gt; &lt;h5&gt;AnalyƟcs&lt;/h5&gt;
&lt;p&gt;Get insights with performance and producƟvity
reports.&lt;/p&gt; &lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/secƟon&gt;

&lt;!-- Pricing --&gt;
&lt;secƟon id=&quot;pricing&quot;&gt;
&lt;div class=&quot;container&quot;&gt;
&lt;h2 class=&quot;text-center mb-5&quot;&gt;Pricing Plans&lt;/h2&gt;
&lt;div class=&quot;row jusƟfy-content-center align-items-
stretch&quot;&gt; &lt;div class=&quot;col-md-4 mb-4&quot;&gt;
&lt;div class=&quot;card pricing-card text-center&quot;&gt;
&lt;div class=&quot;card-body&quot;&gt;
&lt;h5&gt;Basic&lt;/h5&gt;

&lt;h3 class=&quot;card-price&quot;&gt;₹0&lt;/h3&gt;
&lt;p&gt;For personal use&lt;/p&gt;
&lt;ul class=&quot;list-unstyled&quot;&gt;
&lt;li&gt;✔ Task Management&lt;/li&gt;
&lt;li&gt;✔ Basic Reports&lt;/li&gt;
&lt;/ul&gt;
&lt;a href=&quot;#&quot; class=&quot;btn btn-outline-primary&quot;&gt;Choose Plan&lt;/a&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;

&lt;div class=&quot;col-md-4 mb-4&quot;&gt;
&lt;div class=&quot;card pricing-card text-center border border-
primary&quot;&gt; &lt;div class=&quot;card-body&quot;&gt;
&lt;span class=&quot;badge bg-primary mb-2&quot;&gt;Most Popular&lt;/span&gt;
&lt;h5&gt;Pro&lt;/h5&gt;
&lt;h3 class=&quot;card-price&quot;&gt;₹499 / month&lt;/h3&gt;
&lt;p&gt;For professionals&lt;/p&gt;
&lt;ul class=&quot;list-unstyled&quot;&gt;
&lt;li&gt;✔ All Basic Features&lt;/li&gt;
&lt;li&gt;✔ Time Tracking&lt;/li&gt;
&lt;li&gt;✔ Advanced Reports&lt;/li&gt;
&lt;/ul&gt;
&lt;a href=&quot;#&quot; class=&quot;btn btn-primary&quot;&gt;Choose Plan&lt;/a&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/secƟon&gt;

&lt;!-- Contact --&gt;
&lt;secƟon id=&quot;contact&quot;&gt;
&lt;div class=&quot;container&quot;&gt;
&lt;h2 class=&quot;text-center mb-5&quot;&gt;Contact Us&lt;/h2&gt;
&lt;div class=&quot;row jusƟfy-content-center&quot;&gt;
&lt;div class=&quot;col-md-6&quot;&gt;
&lt;form onsubmit=&quot;event.preventDefault(); alert(&#39;Message
sent!&#39;);&quot;&gt; &lt;div class=&quot;mb-3&quot;&gt;
&lt;label for=&quot;name&quot; class=&quot;form-label&quot;&gt;Name&lt;/label&gt;
&lt;input id=&quot;name&quot; type=&quot;text&quot; class=&quot;form-control&quot; placeholder=&quot;Enter your name&quot;&gt;
&lt;/div&gt;
&lt;div class=&quot;mb-3&quot;&gt;
&lt;label for=&quot;email&quot; class=&quot;form-label&quot;&gt;Email&lt;/label&gt;
&lt;input id=&quot;email&quot; type=&quot;email&quot; class=&quot;form-control&quot; placeholder=&quot;Enter your email&quot;&gt;
&lt;/div&gt;
&lt;div class=&quot;mb-3&quot;&gt;
&lt;label for=&quot;message&quot; class=&quot;form-label&quot;&gt;Message&lt;/label&gt;
&lt;textarea id=&quot;message&quot; class=&quot;form-control&quot; rows=&quot;4&quot; placeholder=&quot;Your
message&quot;&gt;&lt;/textarea&gt; &lt;/div&gt;
&lt;buƩon type=&quot;submit&quot; class=&quot;btn btn-primary w-100&quot;&gt;Send
Message&lt;/buƩon&gt; &lt;/form&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/secƟon&gt;

&lt;!-- Footer --&gt;
&lt;footer&gt;
&lt;p class=&quot;mb-0&quot;&gt;© 2026 TaskFlow. All rights reserved.&lt;/p&gt;
&lt;/footer&gt;

&lt;!-- Bootstrap JS --&gt;
&lt;script src=&quot;hƩps://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js&quot;&gt;&lt;/script&gt;

&lt;/body&gt;
&lt;/html&gt;
