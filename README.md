<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Website</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0; /* Change this color */
            color: #333;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Header Styles */
        header {
            background: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2rem;
        }

        nav {
            margin: 1rem 0;
        }

        nav a {
            color: #FFD700;
            margin: 0 1rem;
            font-weight: bold;
        }

        nav a:hover {
            color: white;
        }

        /* Section Styles */
        section {
            margin: 2rem auto;
            max-width: 800px;
            padding: 1.5rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            border-bottom: 2px solid #007BFF;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }

        /* Projects Section */
        #projects ul {
            list-style-type: square;
            padding-left: 1.5rem;
        }

        /* Contact Section */
        #contact ul {
            list-style: none;
            padding: 0;
        }

        #contact li {
            margin-bottom: 0.5rem;
        }

        /* Footer Styles */
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #333;
            color: white;
            margin-top: 2rem;
        }

        footer a {
            color: #FFD700;
        }

        footer a:hover {
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to my personal website!</h1>
        <nav>
            <a href="#about">About Me</a>
            <a href="#studies">About My Studies</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Marios Konstantinos Giannoulis, a passionate developer with expertise in C/C++. I love solving complex problems and building impactful projects. Welcome to my personal space on the web!</p>
    </section>
    <section id="studies">
        <h2>About My Studies</h2>
        <p>I currently study at the <a href="https://www.di.uoa.gr/" target="_blank">Department of Informatics and Telecommunications</a>, in the National and Kapodistrian University of Athens.</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <ul>
           I currently have no projects.
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me on:</p>
        <ul>
            <li>Email: <a href="mailto:mariosgiannouliw@gmail.com">mariosgiannouliw@gmail.com</a></li>
            <li>GitHub: <a href="https://github.com/Mariosgian" target="_blank">github.com/Mariosgian</a></li>
        </ul>
    </section>
    <footer>
        <p>&copy; 2024 Marios Konstantinos Giannoulis. Built with ❤️ and hosted on <a href="https://pages.github.com/" target="_blank">GitHub Pages</a>.</p>
    </footer>
</body>
</html>
