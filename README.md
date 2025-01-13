<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Koushik's Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .typewriter {
            display: inline-block;
            border-right: 2px solid black;
            white-space: nowrap;
            overflow: hidden;
            animation: blink 0.7s step-end infinite alternate;
        }
        @keyframes blink {
            50% {
                border-color: transparent;
            }
        }
    </style>
</head>
<body>
    <h1>
        <span class="typewriter" id="dynamic-text">Hi 👋, I'm Koushik</span>
    </h1>
    <p>A passionate frontend developer from </p>
    <h2>🚀 Languages and Tools I Use</h2>
    <p>
        <a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" style="display: inline-block;">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="42" height="42" />
        </a>
        <a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" style="display: inline-block;">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="42" height="42" />
        </a>
        <a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" style="display: inline-block;">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="42" height="42" />
        </a>
        <!-- Add the rest of your icons here -->
    </p>
    <h2>⚡️ Where to find me</h2>
    <p>
        <a target="_blank" href="https://www.linkedin.com/in/KoushikAlapati" style="display: inline-block;">
            <img src="https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
        </a>
    </p>
    <p>
        <img align="center" src="https://github-readme-stats.vercel.app/api?username=akoushik2k&show_icons=true&locale=en" alt="akoushik2k" />
    </p>

    <script>
        const textElement = document.getElementById('dynamic-text');
        const textArray = ["Hi 👋, I'm Koushik", "Welcome to my profile"];
        let index = 0;

        setInterval(() => {
            index = (index + 1) % textArray.length; // Toggle between 0 and 1
            textElement.textContent = textArray[index];
        }, 3000); // Change text every 3 seconds
    </script>
</body>
</html>
