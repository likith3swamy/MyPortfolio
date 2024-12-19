<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio website of Swamy R, showcasing skills in programming, frontend, and backend technologies.">
    <meta name="author" content="Swamy R">
    <meta name="keywords" content="Swamy R, Portfolio, Computer Science, JSSATEB, Programming, Frontend, Backend, Projects">
    <title>Home - Portfolio</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
        }

        /* Header */
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 1rem 0 0;
            display: flex;
            justify-content: center;
            gap: 1.5rem;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ff9800;
        }

        /* Main Section */
        main {
            padding: 2rem;
            max-width: 900px;
            margin: auto;
        }

        section {
            margin-bottom: 2rem;
        }

        h2 {
            border-bottom: 2px solid #ff9800;
            display: inline-block;
            margin-bottom: 1rem;
            color: #444;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            margin-bottom: 0.5rem;
        }

        /* Links */
        a {
            color: #007BFF;
            text-decoration: none;
            transition: color 0.3s;
        }

        a:hover {
            color: #0056b3;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 0.5rem;
            }

            nav ul li {
                text-align: center;
            }

            header h1 {
                font-size: 2rem;
            }

            main {
                padding: 1rem;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="resume.html">Resume</a></li>
                <li><a href="biodata.html">Bio-data</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>
                Hello! I am Swamy R, a Computer Science Engineering student at JSS Academy of Technical Education, Bangalore.
            </p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li><strong>Programming Languages:</strong> C, Java, Python</li>
                <li><strong>Frontend Technologies:</strong> HTML, CSS, JavaScript, React</li>
                <li><strong>Backend Technologies:</strong> Node.js, Express</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <ul>
                <li>Phone: +91 6363246462</li>
                <li>Email: <a href="mailto:likithswamy3@gmail.com">likithswamy3@gmail.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/Swamy-R" target="_blank">LinkedIn Profile</a></li>
                <li>GitHub: <a href="https://github.com/Swamy_R" target="_blank">GitHub Profile</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; <script>document.write(new Date().getFullYear());</script> Swamy R</p>
    </footer>
</body>

</html>
