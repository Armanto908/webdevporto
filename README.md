#webdevporto
├── index.html
├── styles.css
└── script.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Programming Journey</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Programming Journey</h1>
        <p>Sharing my passion and knowledge in the world of coding</p>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hi, I'm [Your Name], a passionate web developer with a deep understanding and love for programming. Here I share my journey, projects, and what drives me in the world of code.</p>
        </section>
        <section id="interests">
            <h2>My Interests</h2>
            <ul>
                <li>Front-End Development with HTML, CSS, and JavaScript</li>
                <li>Back-End Development with Node.js and Express</li>
                <li>Exploring New Technologies like React and Vue.js</li>
                <li>Contributing to Open Source Projects</li>
                <li>Building Full-Stack Web Applications</li>
            </ul>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <p>Check out my <a href="https://github.com/[YourGitHubUsername]" target="_blank">GitHub</a> for more projects.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

h2 {
    color: #4CAF50;
}

ul {
    list-style-type: square;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
    position: fixed;
    width: 100%;
    bottom: 0;
}
document.addEventListener("DOMContentLoaded", () => {
    console.log("Welcome to my programming journey!");
});
