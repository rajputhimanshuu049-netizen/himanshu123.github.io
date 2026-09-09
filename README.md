<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Himanshu | Tech</title>

<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
font-family:Arial,sans-serif;
background:#070914;
color:white;
}
nav{
position:fixed;
top:0;
width:100%;
padding:18px 7%;
display:flex;
justify-content:space-between;
background:#070914ee;
border-bottom:1px solid #22263d;
z-index:10;
}
.logo{font-size:22px;font-weight:bold}
.logo span,h1 span,h2 span{color:#6c63ff}
nav a{color:#aaa;text-decoration:none;margin-left:20px}
.hero{
min-height:100vh;
display:flex;
align-items:center;
padding:100px 7%;
}
.hero div{max-width:750px}
.badge{
display:inline-block;
padding:8px 15px;
border:1px solid #444;
border-radius:30px;
margin-bottom:25px;
color:#bbb;
}
h1{
font-size:clamp(50px,10vw,90px);
line-height:1;
margin-bottom:25px;
}
p{
font-size:18px;
color:#aaa;
line-height:1.7;
}
.btn{
display:inline-block;
margin-top:25px;
padding:14px 22px;
background:#6c63ff;
color:white;
border-radius:10px;
text-decoration:none;
font-weight:bold;
}
section{
padding:90px 7%;
border-top:1px solid #171b2d;
}
h2{font-size:38px;margin-bottom:25px}
.card{
background:#0d1020;
border:1px solid #292d45;
border-radius:18px;
padding:25px;
margin-bottom:20px;
}
.grid{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:20px;
}
@media(max-width:700px){
nav a{display:none}
.grid{grid-template-columns:1fr}
}
</style>
</head>

<body>

<nav>
<div class="logo">HIMANSHU<span>.</span></div>
<div>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</div>
</nav>

<section class="hero" id="home">
<div>
<div class="badge">⚡ CSEIML • AI & Tech</div>

<h1>Build.<br>Learn.<br><span>Level Up.</span></h1>

<p>
Welcome to my personal tech space.
I am learning Computer Science, AI and Machine Learning
and building my skills one project at a time.
</p>

<a class="btn" href="#projects">View Projects →</a>
</div>
</section>

<section id="about">
<h2>About <span>Me</span></h2>

<div class="card">
<h3>Computer Science + AI/ML</h3>
<p>
I'm learning programming from the basics and working
towards becoming a strong developer.
</p>
</div>
</section>

<section id="projects">
<h2>My <span>Projects</span></h2>

<div class="grid">

<div class="card">
<h3>🚀 Project One</h3>
<p>My first project will appear here.</p>
</div>

<div class="card">
<h3>🤖 AI Project</h3>
<p>AI and Machine Learning projects.</p>
</div>

<div class="card">
<h3>🌐 Web Project</h3>
<p>Websites and applications I build.</p>
</div>

</div>
</section>

<section id="contact">
<h2>Let's <span>Connect</span></h2>

<div class="card">
<p>
Thanks for visiting my website!
</p>

<a class="btn" href="mailto:your@email.com">
Email Me
</a>
</div>
</section>

</body>
</html>
