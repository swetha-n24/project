<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Swetha | Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="sam.css">
</head>
<body>

<nav>
    <h2 class="logo">Swetha</h2>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<header class="hero">
    <div class="hero-text">
        <h1>Hello, I'm <span>Swetha</span></h1>
        <p>Computer Science Engineering Student</p>
        <a href="#contact" class="btn">Hire Me</a>
    </div>
</header>

<section id="about" class="section">
    <h2>About Me</h2>
    <p>I am a passionate CSE student skilled in Python, HTML, CSS and Data Structures. 
       I enjoy building responsive and user-friendly web applications.</p>
</section>

<section id="skills" class="section">
    <h2>Skills</h2>
    <div class="skill-grid">
        <div class="card">Python</div>
        <div class="card">HTML</div>
        <div class="card">CSS</div>
        <div class="card">DSA</div>
        <div class="card">SQL</div>
        <div class="card">Git & GitHub</div>
    </div>
</section>

<section id="projects" class="section">
    <h2>Projects</h2>
    <div class="project-grid">
        <div class="project-card">
            <h3>Student Management System</h3>
            <p>Python-based CRUD application using file handling.</p>
        </div>
        <div class="project-card">
            <h3>Password Strength Checker</h3>
            <p>Regex-based password validation tool.</p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: nswetha570@email.com</p>
</section>

<footer>
    <p>© 2026 Swetha | All Rights Reserved</p>
</footer>

</body>
</html>



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* Navigation */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 10%;
    background: #111;
    color: white;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #00adb5;
}

/* Hero Section */
.hero {
    height: 90vh;
    background: linear-gradient(to right, #00adb5, #393e46);
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.hero span {
    color: yellow;
}

.btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background: #111;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background: white;
    color: #111;
}

/* Sections */
.section {
    padding: 60px 10%;
    text-align: center;
}

.skill-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.card {
    background: #00adb5;
    padding: 20px;
    color: white;
    border-radius: 8px;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.project-card {
    background: #f4f4f4;
    padding: 20px;
    border-radius: 8px;
    transition: 0.3s;
}

.project-card:hover {
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

/* Footer */
footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 15px;
}

/* Responsive */
@media(max-width: 768px) {
    nav {
        flex-direction: column;
    }

    nav ul {
        margin-top: 10px;
    }
}
