<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rozhaniya P - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #a8e10c;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #d51f36;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .section {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #d51f36;
        }
        .resume-btn {
            display: block;
            width: 200px;
            text-align: center;
            margin: 20px auto;
            padding: 10px;
            background: black;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    Rozhaniya P <br>
    <small>Software Developer</small>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
</nav>

<div class="container">
    <div id="about" class="section">
        <h2>About Me</h2>
        <p>I am currently pursuing a BSc in Computer Science, with a passion for software development. I love learning new technologies and building applications that make a difference.</p>
    </div>

    <div id="education" class="section">
        <h2>Education</h2>
        <p><b>University:</b> Madras University</p>
        <p><b>Degree:</b> BSc Computer Science</p>
    </div>

    <div id="skills" class="section">
        <h2>Skills</h2>
        <ul>
            <li>Java</li>
            <li>Python</li>
            <li>HTML</li>
        </ul>
    </div>

    <div id="projects" class="section">
        <h2>Projects</h2>
        <ul>
            <li>Project 1 - <a href="#">Project Link</a></li>
            <li>Project 2 - <a href="#">Project Link</a></li>
        </ul>
    </div>

    <div id="resume" class="section">
        <h2>Resume</h2>
        <a href="#" class="resume-btn">Download CV</a>
    </div>
</div>

<footer style="text-align:center; padding:20px; background:black; color:white;">
    © 2024 Rozhaniya P
</footer>

</body>
</html>
