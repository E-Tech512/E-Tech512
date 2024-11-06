<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gozu - Full Stack Developer</title>
    <style>
        /* General body styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #0E1218, #131923, #151D29, #171F2B, #192331, #5B73A2);
            color: #fff;
            text-align: center;
        }
        
        /* Header Section */
        header {
            padding: 50px;
            background-color: #32A8BB;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            font-size: 3.5em;
            margin: 0;
            animation: fadeIn 2s ease-in-out;
        }
        header p {
            font-size: 1.4em;
            margin-top: 10px;
            animation: fadeIn 2s ease-in-out 1s;
        }

        /* About Me Section */
        .about {
            padding: 40px 20px;
            background-color: rgba(0, 0, 0, 0.6);
            margin-top: 30px;
            border-radius: 10px;
        }
        .about h2 {
            font-size: 2.5em;
            color: #32A8BB;
        }
        .about p {
            font-size: 1.2em;
            max-width: 700px;
            margin: 20px auto;
        }

        /* Skills Section */
        .skills {
            background-color: #171F2B;
            padding: 40px 20px;
            border-radius: 10px;
            margin-top: 50px;
        }
        .skills h3 {
            font-size: 2.5em;
            color: #32A8BB;
        }
        .skills ul {
            list-style-type: none;
            padding: 0;
        }
        .skills li {
            font-size: 1.3em;
            margin: 10px 0;
            color: #fff;
        }

        /* Social Media Buttons */
        .social-links {
            margin-top: 40px;
        }
        .social-links a {
            text-decoration: none;
            color: #fff;
            background-color: #5B73A2;
            padding: 15px 30px;
            margin: 10px;
            border-radius: 5px;
            font-size: 1.2em;
            transition: 0.3s;
        }
        .social-links a:hover {
            background-color: #4a61a1;
        }

        /* Animations */
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Hi, I'm Gozu</h1>
    <p>I'm a Computer Engineering student specializing in Full Stack Software Development</p>
</header>

<div class="about">
    <h2>About Me</h2>   
    <p>I’m passionate about coding and creating interactive and dynamic web applications. I’m constantly learning new technologies and frameworks to improve my skills and create better software solutions.</p>
</div>

<div class="skills">
    <h3>My Skills</h3>
    <ul>
        <li>HTML, CSS, JavaScript (ES6+)</li>
        <li>React, Angular, Vue.js</li>
        <li>Node.js, Express</li>
        <li>Python, Django, Flask</li>
        <li>Java, Spring Boot</li>
        <li>SQL, MongoDB, PostgreSQL</li>
        <li>Version Control: Git, GitHub</li>
    </ul>
</div>

<div class="social-links">
    <a href="https://github.com/gozu" target="_blank">Visit My GitHub</a>
    <a href="https://www.linkedin.com/in/gozu" target="_blank">Connect on LinkedIn</a>
    <a href="mailto:gozu@example.com" target="_blank">Email Me</a>
</div>

</body>
</html>
