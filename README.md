<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        .header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 2px solid #2c3e50;
        }
        .header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 10px;
        }
        .section p {
            line-height: 1.6;
        }
        .contact-info {
            list-style: none;
            padding: 0;
        }
        .contact-info li {
            margin-bottom: 10px;
        }
        .contact-info a {
            color: #2980b9;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        .skills ul, .experience ul {
            list-style: none;
            padding: 0;
        }
        .skills li, .experience li {
            background: #ecf0f1;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://via.placeholder.com/150" alt="Profile Picture">
            <h1>John Doe</h1>
            <p>Senior Software Engineer</p>
        </div>

        <div class="section">
            <h2>About Me</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque vitae urna at justo fermentum tristique. Duis nec tincidunt libero, non tempus ligula.</p>
        </div>

        <div class="section skills">
            <h2>Skills</h2>
            <ul>
                <li>JavaScript</li>
                <li>Python</li>
                <li>React</li>
                <li>Node.js</li>
                <li>SQL & NoSQL Databases</li>
            </ul>
        </div>

        <div class="section experience">
            <h2>Experience</h2>
            <ul>
                <li><strong>Senior Software Engineer</strong> at Tech Company (2020 - Present)
                    <p>Lead development on key projects, mentor junior developers, and collaborate with cross-functional teams to deliver high-quality software.</p>
                </li>
                <li><strong>Software Engineer</strong> at Another Company (2015 - 2020)
                    <p>Worked on various software development projects, improved system performance, and contributed to codebase management.</p>
                </li>
            </ul>
        </div>

        <div class="section">
            <h2>Contact</h2>
            <ul class="contact-info">
                <li>Email: <a href="mailto:john.doe@example.com">john.doe@example.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/johndoe" target="_blank">linkedin.com/in/johndoe</a></li>
                <li>GitHub: <a href="https://github.com/johndoe" target="_blank">github.com/johndoe</a></li>
            </ul>
        </div>
    </div>
</body>
</html>
