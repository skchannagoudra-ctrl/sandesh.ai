# sandesh.ai
sandesh.ai
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sandesh | AI Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
<script src="https://unpkg.com/scrollreveal"></script>
<script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}
body{background:#0f172a;color:white;scroll-behavior:smooth;overflow-x:hidden;}
#particles-js{position:fixed;width:100%;height:100%;z-index:-1;}

nav{
position:fixed;width:100%;padding:15px 60px;
background:rgba(0,0,0,0.6);
backdrop-filter:blur(10px);
display:flex;justify-content:space-between;
z-index:1000;
}
nav h2{color:#38bdf8;}
nav a{color:white;text-decoration:none;margin-left:25px;transition:0.3s;}
nav a:hover{color:#38bdf8;}

header{
height:100vh;
display:flex;flex-direction:column;
justify-content:center;align-items:center;
text-align:center;padding:20px;
}
header h1{
font-size:50px;
background:linear-gradient(90deg,#38bdf8,#818cf8);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}
header span{color:#38bdf8;}
.btn{
margin-top:25px;padding:12px 25px;
background:#38bdf8;color:#0f172a;
border:none;border-radius:30px;
cursor:pointer;font-weight:bold;
transition:0.3s;
}
.btn:hover{background:white;}

section{padding:80px 10%;}
section h2{text-align:center;margin-bottom:40px;font-size:35px;color:#38bdf8;}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}
.card{
background:#1e293b;
padding:25px;border-radius:15px;
transition:0.4s;
}
.card:hover{
transform:translateY(-10px);
box-shadow:0 0 20px #38bdf8;
background:#334155;
}

.social{
text-align:center;margin-top:20px;
}
.social a{
color:white;margin:0 15px;
font-size:20px;text-decoration:none;
transition:0.3s;
}
.social a:hover{color:#38bdf8;}

footer{
text-align:center;padding:20px;
border-top:1px solid #334155;
color:#94a3b8;
}
</style>
</head>

<body>

<div id="particles-js"></div>

<nav>
<h2>Sandesh</h2>
<div>
<a href="#about">About</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</div>
</nav>

<header>
<h1>Hello, I'm Sandesh</h1>
<h3>I am <span id="typing"></span></h3>
<a href="resume.pdf" download>
<button class="btn">Download Resume</button>
</a>
</header>

<section id="about">
<h2>About Me</h2>
<p style="text-align:center;max-width:700px;margin:auto;color:#cbd5e1;">
B.Tech AI Engineering student passionate about Machine Learning,
Deep Learning and building intelligent systems.
Currently mastering Python and real-world AI projects.
</p>
</section>

<section id="projects">
<h2>Projects</h2>
<div class="projects">
<div class="card">
<h3>AI Chatbot</h3>
<p>Built conversational AI using NLP techniques.</p>
</div>

<div class="card">
<h3>Face Detection</h3>
<p>Real-time face detection using OpenCV.</p>
</div>

<div class="card">
<h3>ML Prediction Model</h3>
<p>Developed ML model with Scikit-learn.</p>
</div>
</div>
</section>

<section id="contact">
<h2>Contact</h2>
<p style="text-align:center;">Email: yourmail@gmail.com</p>

<div class="social">
<a href="#">LinkedIn</a>
<a href="#">GitHub</a>
<a href="#">Instagram</a>
</div>
</section>

<footer>
© 2026 Sandesh Channagoudra | AI Engineer
</footer>

<script>
var typed = new Typed("#typing", {
strings: ["AI Developer", "Machine Learning Enthusiast", "Python Programmer"],
typeSpeed: 60,
backSpeed: 40,
loop: true
});

ScrollReveal().reveal('.card', { delay: 200, distance: '50px', origin: 'bottom' });

particlesJS("particles-js", {
particles: {
number: { value: 80 },
size: { value: 3 },
color: { value: "#38bdf8" },
line_linked: { enable: true, color: "#38bdf8" }
}
});
</script>

</body>
</html>
