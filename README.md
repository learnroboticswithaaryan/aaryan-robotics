<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Learn Robotics with Aaryan</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{background:#0a0a0a;color:white}

/* NAVBAR */
nav{
 display:flex;justify-content:space-between;align-items:center;
 padding:20px 8%;position:fixed;width:100%;
 background:rgba(0,0,0,0.6);backdrop-filter:blur(10px);
}
nav h2{color:#00f7ff}
nav a{color:white;margin-left:20px;text-decoration:none}

/* HERO */
.hero{
 height:100vh;display:flex;align-items:center;justify-content:center;
 text-align:center;background:radial-gradient(circle,#001f3f,#000);
}
.hero h1{font-size:55px}
.hero span{color:#00f7ff}
.hero p{margin:20px 0;color:#aaa}
.btn{
 padding:12px 25px;border:none;background:#00f7ff;
 color:black;border-radius:30px;cursor:pointer
}

/* SECTION */
section{padding:90px 10%;text-align:center}

/* CARDS */
.cards{display:flex;justify-content:center;flex-wrap:wrap}
.card{
 background:#111;margin:15px;padding:25px;width:260px;
 border-radius:15px;transition:.3s
}
.card:hover{
 transform:translateY(-10px);
 box-shadow:0 0 20px #00f7ff;
}

/* FOOTER */
footer{text-align:center;padding:20px;background:#000;color:#777}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
  <h2>Aaryan</h2>
  <div>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#learn">Learn</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- HERO -->
<div class="hero" id="home">
  <div>
    <h1>Hi, I'm <span>Aaryan</span></h1>
    <p>Grade 10 student | Robotics Enthusiast | Future Innovator 🚀</p>
    <button class="btn" onclick="scrollToSection()">Start Learning</button>
  </div>
</div>

<!-- ABOUT -->
<section id="about">
  <h2>About Me</h2>
  <p>
    I am a 16-year-old Grade 10 student who is deeply interested in robotics, electronics, and technology. 
    I started exploring robotics at a young age and have built several beginner-friendly projects like 
    robot cars, rain detectors, and sensor-based systems.
  </p>
  <br>
  <p>
    My goal is to make robotics easy for students by explaining concepts in a simple and practical way. 
    Through this platform, I want to help beginners start their journey in robotics without confusion.
  </p>
</section>

<!-- LEARN -->
<section id="learn">
  <h2>What You Will Learn</h2>
  <div class="cards">
    <div class="card">Arduino Basics</div>
    <div class="card">Sensors & Components</div>
    <div class="card">Building Simple Robots</div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <h2>My Projects</h2>
  <div class="cards">
    <div class="card">Line Follower Robot</div>
    <div class="card">Rain Detector System</div>
    <div class="card">Arduino Robot Car</div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>Contact Me</h2>
  <p>Email: learnroboticswithaaryan@gmail.com</p>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 Learn Robotics with Aaryan</p>
</footer>

<script>
function scrollToSection(){
  document.getElementById("learn").scrollIntoView({behavior:"smooth"});
}
</script>

</body>
</html>
