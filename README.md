<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h1>About Me</h1>
        <p>Brief introduction about yourself.</p>
    </section>
    <section id="projects">
        <h1>Projects</h1>
        <div class="project">
            <h2>Project 1</h2>
            <p>Description of project 1.</p>
            <a href="https://live-demo.com" target="_blank">Live Demo</a>
            <a href="https://github.com/your-username/project1" target="_blank">Source Code</a>
        </div>
        <div class="project">
            <h2>Project 2</h2>
            <p>Description of project 2.</p>
            <a href="https://live-demo.com" target="_blank">Live Demo</a>
            <a href="https://github.com/your-username/project2" target="_blank">Source Code</a>
        </div>
    </section>
    <section id="skills">
        <h1>Skills</h1>
        <p>List of your skills.</p>
    </section>
    <section id="resume">
        <h1>Resume</h1>
        <a href="resume.pdf" download>Download Resume</a>
    </section>
    <section id="contact">
        <h1>Contact</h1>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
