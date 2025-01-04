<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Personal website of Marios Konstantinos Giannoulis, a computer science student with expertise in C/C++.">
    <title>Personal Website</title>
    <style>
        :root {
            --primary-color: #007BFF;
            --primary-hover-color: #0056b3;
            --dark-primary-color: #4A90E2;
            --dark-hover-color: #82C0FF;
            --background-light: #fff;
            --background-dark: #121212;
            --section-light: #f7f7f7;
            --section-dark: #1c1c1c;
            --text-light: #000;
            --text-dark: #fff;
        }

        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--background-light);
            color: var(--text-light);
            line-height: 1.6;
            box-sizing: border-box;
        }

        a {
            color: var(--primary-color);
            text-decoration: none;
        }

        a:hover {
            color: var(--primary-hover-color);
        }

        header {
            background-color: var(--background-light);
            color: var(--text-light);
            text-align: center;
            padding: 3rem;
        }

        header h1 {
            margin: 0;
            font-size: 3rem;
            font-weight: bold;
            text-transform: uppercase;
        }

        nav {
            margin-top: 1rem;
        }

        nav a {
            margin: 0 1rem;
            font-size: 1.2rem;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 4px;
        }

        nav a:hover {
            background-color: #f0f0f0;
        }

        section {
            margin: 2rem auto;
            max-width: 1000px;
            padding: 3rem;
            background-color: var(--section-light);
            color: var(--text-light);
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            font-size: 2rem;
            color: var(--text-light);
            border-bottom: 2px solid var(--text-light);
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }

        section p, section ul {
            font-size: 1.1rem;
        }

        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: var(--background-light);
            color: var(--text-light);
            margin-top: 2rem;
        }

        footer a {
            font-weight: bold;
            color: var(--primary-color);
        }

        footer a:hover {
            color: var(--primary-hover-color);
        }

        @media (prefers-color-scheme: dark) {
            body {
                background-color: var(--background-dark);
                color: var(--text-dark);
            }

            header {
                background-color: var(--background-dark);
                color: var(--text-dark);
            }

            a {
                color: var(--dark-primary-color);
            }

            a:hover {
                color: var(--dark-hover-color);
            }

            section {
                background-color: var(--section-dark);
                color: var(--text-dark);
            }

            section h2 {
                color: var(--text-dark);
                border-bottom: 2px solid var(--text-dark);
            }

            footer {
                background-color: var(--background-dark);
                color: var(--text-dark);
            }
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5rem;
            }

            nav a {
                font-size: 1rem;
                padding: 0.5rem;
            }

            section {
                padding: 2rem;
            }

            section h2 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to my personal website!</h1>
        <nav>
            <a href="#about" aria-label="About Me">About Me</a>
            <a href="#studies" aria-label="About My Studies">About My Studies</a>
            <a href="#projects" aria-label="Projects">Projects</a>
            <a href="#contact" aria-label="Contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm <strong>Marios Konstantinos Giannoulis</strong>, a passionate developer with expertise in C/C++. I love solving complex problems and building impactful projects. Welcome to my personal space on the web!</p>
    </section>

    <section id="studies">
        <h2>About My Studies</h2>
        <p>I currently study at the <a href="https://www.di.uoa.gr/" target="_blank">Department of Informatics and Telecommunications</a>, in the National and Kapodistrian University of Athens.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>No projects yet, but stay tuned for future updates!</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me on:</p>
        <ul>
            <li>Email: <a href="mailto:mariosgiannouliw@gmail.com">mariosgiannouliw@gmail.com</a></li>
            <li>GitHub: <a href="https://github.com/Mariosgian" target="_blank">github.com/Mariosgian</a></li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/marios-konstantinos-giannoulis-129576289" target="_blank">linkedin.com/in/marios-konstantinos-giannoulis</a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Marios Konstantinos Giannoulis. Built with ❤️ and hosted on <a href="https://pages.github.com/" target="_blank">GitHub Pages</a>.</p>
    </footer>
</body>
</html>

