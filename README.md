# portfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            background: #648596;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
        }
        section {
            background: #fff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color:#648596;
        }
        .content img {
            max-width: 100%;
            border-radius: 8px;
        }
        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .skill {
            background: #648596;
            color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            flex: 1 1 calc(33.333% - 20px);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .project-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .project {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            flex: 1 1 calc(50% - 20px);
        }
        .project img {
            max-width: 100%;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #648596;
            color: #ffffff;
        }
        a {
            color: #648596;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <p><h1>Portfolio</h1></p>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#resume">Resume</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            
        </div>
    </header>

    <section id="about">
        <div class="container">
            <center><h1>About Me</h1></center>
            <p></p>
            <div class="content">
                <center><img src="C:\Users\Administrator\Desktop\download.jpeg" alt="Name"></center>
                <center><h3>Hi, I'm Ritika Gathibandhe</h3></center>
                <center><p>I'm a final year student pursuing my degree in B.Tech in Electronics Engineering.</p></center>
                <center><p>I have skills related to my field and also software.</p></center>
            </div>
        </div>
    </section>

    <section id="skills">
        <div class="container">
            <center><h1>Skills</h1></center>
            <p></p>
            <div class="skills-grid">
                <div class="skill">C</div>
                <div class="skill">C++</div>
                <div class="skill">Python</div>
                <div class="skill">HTML & CSS</div>
                <div class="skill">MATLAB</div>
                <div class="skill">GUI</div>
                <div class="skill">SQL</div>
                <div class="skill">Django</div>
            </div>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <center><h1>Projects</h1></center>
            <p></p>
            <div class="project-grid">
                <div class="project">
                    <center><img src="C:\Users\Administrator\Desktop\clap switrch.jpeg" alt="Project 2"></center>
                    <center><h3>Clap Switch</h3></center>
                    <center><p>A circuit which detects the characteristic sound pattern of a clap, and activates or deactivates the connected devices. Provides a hand free convenient way to operate appliances.</p></center>
                </div>
            </div>
        </div>
    </section>

    <section id="resume">
        <div class="container">
            <Center><h1>Resume</h1></Center>
            <center><a href="Ritika.V.Gathibandhe.docx" download>Download Resume</a></center>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <center><h1>Contact</h1></center>
            <center><p>Email: <a href="mailto:ritikagathibandhe@gmail.com">ritikagathibandhe@gmail.com</a></p></center>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Ritika Gathibandhe. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
