<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Preetha Ravikumar | Robotics Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#0f172a;
    color:white;
    line-height:1.6;
}

nav{
    position:fixed;
    width:100%;
    top:0;
    background:rgba(15,23,42,0.95);
    backdrop-filter:blur(10px);
    z-index:1000;
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
    padding:20px;
    gap:30px;
}

nav a{
    text-decoration:none;
    color:white;
    transition:0.3s;
}

nav a:hover{
    color:#38bdf8;
}

section{
    padding:100px 10%;
}

.hero{
    height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero h1{
    font-size:4rem;
}

.hero h2{
    color:#38bdf8;
    margin-top:10px;
    font-weight:400;
}

.hero p{
    max-width:800px;
    margin-top:20px;
    color:#cbd5e1;
}

.btns{
    margin-top:30px;
}

.btn{
    display:inline-block;
    margin:10px;
    padding:12px 24px;
    border-radius:8px;
    text-decoration:none;
    color:white;
    border:1px solid #38bdf8;
    transition:0.3s;
}

.btn:hover{
    background:#38bdf8;
    color:#0f172a;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
    color:#38bdf8;
    font-size:2rem;
}

.card-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.card h3{
    color:#38bdf8;
    margin-bottom:15px;
}

.skills{
    display:flex;
    flex-wrap:wrap;
    gap:15px;
    justify-content:center;
}

.skill{
    background:#1e293b;
    padding:10px 20px;
    border-radius:25px;
}

footer{
    text-align:center;
    padding:40px;
    color:#94a3b8;
}

.about{
    max-width:900px;
    margin:auto;
    text-align:center;
    color:#cbd5e1;
}

@media(max-width:768px){

.hero h1{
    font-size:2.5rem;
}

.hero h2{
    font-size:1.2rem;
}

nav ul{
    gap:15px;
    flex-wrap:wrap;
}
}
</style>
</head>

<body>

<nav>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#experience">Experience</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero">

<h1>Preetha Ravikumar</h1>

<h2>MSc Robotics & Autonomous Systems | University of Bath</h2>

<p>
Robotics engineer with experience in robotic arm development, automation systems,
sensor integration, computer vision, control systems and mechanical design.
Passionate about building intelligent robotic solutions that combine software,
electronics and mechanical engineering.
</p>

<div class="btns">
<a href="#" class="btn">Download CV</a>
<a href="#" class="btn">LinkedIn</a>
<a href="#" class="btn">GitHub</a>
</div>

</section>

<section id="about">

<h2 class="section-title">About Me</h2>

<div class="about">
<p>
I am currently pursuing an MSc in Robotics and Autonomous Systems at the University of Bath.
My background in Mechanical Engineering and practical experience in robotics, automation,
control systems and product development have enabled me to work on projects ranging from
industrial robotic arms to healthcare technologies. I enjoy solving engineering challenges
through multidisciplinary collaboration and hands-on implementation.
</p>
</div>

</section>

<section id="experience">

<h2 class="section-title">Experience</h2>

<div class="card-grid">

<div class="card">
<h3>TRUMPF India Pvt. Ltd.</h3>
<p>
Robotics Engineering Intern involved in robotic arm development,
sensor integration, vision-based systems, control implementation
and system optimisation.
</p>
</div>

<div class="card">
<h3>IIITDM Research Internship</h3>
<p>
Worked on Hypothermic Machine Perfusion systems,
developing sensor-based monitoring solutions,
temperature control optimisation and experimental testing.
</p>
</div>

</div>

</section>

<section id="projects">

<h2 class="section-title">Featured Projects</h2>

<div class="card-grid">

<div class="card">
<h3>Industrial Robot Arm Development</h3>
<p>
Designed and developed a 6-DOF robotic arm with stepper motors,
servo control and Arduino-based architecture.
Implemented robotic kinematics and motion control.
</p>
</div>

<div class="card">
<h3>Assistive Music Therapy Gloves</h3>
<p>
Developed sensor-based wearable gloves that convert hand movements
into piano sounds for pediatric cerebral palsy therapy.
</p>
</div>

<div class="card">
<h3>Adaptive Page Turner</h3>
<p>
Voice-controlled page-turning system designed for physically
challenged users. Selected among the Top 40 teams at ENTHIRATHON 2024.
</p>
</div>

<div class="card">
<h3>MediaPipe Robot Control</h3>
<p>
Implemented real-time robotic arm control using computer vision
and hand tracking with movement smoothing techniques.
</p>
</div>

</div>

</section>

<section id="skills">

<h2 class="section-title">Technical Skills</h2>

<div class="skills">

<div class="skill">Python</div>
<div class="skill">MATLAB</div>
<div class="skill">Arduino</div>
<div class="skill">RoboDK</div>
<div class="skill">Robot Kinematics</div>
<div class="skill">Automation</div>
<div class="skill">Computer Vision</div>
<div class="skill">Sensors</div>
<div class="skill">Actuators</div>
<div class="skill">AutoCAD</div>
<div class="skill">Creo</div>
<div class="skill">Mechanical Design</div>

</div>

</section>

<section id="contact">

<h2 class="section-title">Contact</h2>

<div class="about">
<p>Email: your.email@example.com</p>
<p>LinkedIn: linkedin.com/in/yourprofile</p>
<p>GitHub: github.com/PreethaRavikumar</p>
</div>

</section>

<footer>
© 2026 Preetha Ravikumar | Robotics Portfolio
</footer>

</body>
</html>
