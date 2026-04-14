# Hi there, I'm Piyush Kumar! 👋





<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Piyush Kumar | Ultra Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:'Poppins',sans-serif;background:#020617;color:#fff}
header{height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;background:linear-gradient(135deg,#020617,#0f172a)}
h1{font-size:48px}
p{color:#94a3b8;margin:10px 0}
.btn{padding:10px 20px;background:#38bdf8;color:#000;border:none;border-radius:6px;cursor:pointer}
section{padding:60px 20px;max-width:1100px;margin:auto}
.card{background:#0f172a;padding:20px;border-radius:12px;margin:15px 0;box-shadow:0 0 20px rgba(0,0,0,0.3)}
.skills-bar{margin:10px 0}
.bar{height:8px;background:#1e293b;border-radius:5px;overflow:hidden}
.progress{height:100%;background:#38bdf8}
.projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:15px}
.project{padding:15px;background:#020617;border-radius:10px}
footer{text-align:center;padding:20px;color:#94a3b8}
</style>
</head>
<body><header>
<h1>👋 Hi, I'm Piyush Kumar</h1>
<p>🚀 Web Developer | AI Enthusiast</p>
<button class="btn" onclick="scrollToSection('projects')">View Projects</button>
</header><section>
<h2>👨‍💻 About Me</h2>
<div class="card">
<p>I am a passionate developer building real-world web apps and exploring AI technologies.</p>
</div>
</section><section>
<h2>🚀 Skills</h2>
<div class="card">
<div class="skills-bar">HTML<div class="bar"><div class="progress" style="width:90%"></div></div></div>
<div class="skills-bar">CSS<div class="bar"><div class="progress" style="width:85%"></div></div></div>
<div class="skills-bar">JavaScript<div class="bar"><div class="progress" style="width:80%"></div></div></div>
<div class="skills-bar">Python<div class="bar"><div class="progress" style="width:75%"></div></div></div>
</div>
</section><section id="projects">
<h2>📌 Projects</h2>
<div class="projects">
<div class="project">
<h3>🔥 Image Gallery App</h3>
<p>Advanced image upload, search & like system.</p>
</div>
<div class="project">
<h3>🤖 AI Image Generator</h3>
<p>Create AI images using prompts.</p>
</div>
<div class="project">
<h3>🌐 Portfolio Website</h3>
<p>Personal portfolio with animations.</p>
</div>
</div>
</section><section>
<h2>📬 Contact Me</h2>
<div class="card">
<input type="text" placeholder="Your Name" style="width:100%;padding:10px;margin:5px 0;border-radius:5px;border:none">
<input type="email" placeholder="Your Email" style="width:100%;padding:10px;margin:5px 0;border-radius:5px;border:none">
<textarea placeholder="Message" style="width:100%;padding:10px;margin:5px 0;border-radius:5px;border:none"></textarea>
<button class="btn">Send</button>
</div>
</section><footer>
© 2026 Piyush Kumar | Ultra Portfolio 🚀
</footer><script>
function scrollToSection(id){
  document.getElementById(id).scrollIntoView({behavior:'smooth'});
}
</script></body>
</html>
