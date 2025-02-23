<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of Marios Konstantinos Giannoulis, a developer passionate about C/C++ and problem-solving.">
    <meta name="keywords" content="Marios Konstantinos Giannoulis, C developer, portfolio, computer science, projects">
    <title>Marios Konstantinos Giannoulis - Portfolio</title>
    <link rel="icon" type="image/png" href="favicon.png">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #000;
            line-height: 1.6;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }
        a:hover {
            color: #0056b3;
        }

        header {
            background-color: #fff;
            color: #000;
            text-align: center;
            padding: 1.5rem 1rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        nav {
            margin-top: 1rem;
            display: flex;
            justify-content: center;
            gap: 1rem;
        }
        nav a {
            font-size: 1.2rem;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 4px;
        }
        nav a:hover, nav a.active {
            background-color: #f0f0f0;
        }

        main {
            margin: 2rem auto;
            max-width: 1000px;
            padding: 0 1rem;
        }

        section {
            margin-bottom: 2rem;
            padding: 2rem;
            background-color: #f7f7f7;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            opacity: 0;
            transform: translateY(20px);
            animation: fadeIn 0.8s ease-out forwards;
        }
        @keyframes fadeIn {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        section h2 {
            font-size: 2rem;
            border-bottom: 2px solid #000;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }

        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #fff;
            color: #000;
            margin-top: 2rem;
        }

        @media (prefers-color-scheme: dark) {
            body, header, footer {
                background-color: #121212;
                color: #fff;
            }
            a {
                color: #4A90E2;
            }
            a:hover {
                color: #82C0FF;
            }
            section {
                background-color: #1c1c1c;
            }
            section h2 {
                border-bottom: 2px solid #fff;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to my personal website!</h1>
        <nav>
            <a href="#about" class="active">About Me</a>
            <a href="#studies">My Studies</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hi! I'm <strong>Marios Konstantinos Giannoulis</strong>, a developer with expertise in C/C++. I love solving problems and building impactful projects.</p>
        </section>

        <section id="studies">
            <h2>My Studies</h2>
            <p>Currently studying at the <a href="https://www.di.uoa.gr/" target="_blank">Department of Informatics and Telecommunications</a>, National and Kapodistrian University of Athens.</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><strong>Factorization Algorithm</strong> - Breaking down two numbers into their prime factors. <a href="https://github.com/Mariosgian/Factor" target="_blank">View on GitHub</a></li>
                <li><strong>Traveling Salesman Problem Solver</strong> - Optimizing city visits based on distance. <a href="https://github.com/Mariosgian/TSP-Algorithm" target="_blank">View on GitHub</a></li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Feel free to reach out:</p>
            <ul>
                <li>Email: <a href="mailto:mariosgiannouliw@gmail.com">mariosgiannouliw@gmail.com</a></li>
                <li>GitHub: <a href="https://github.com/Mariosgian" target="_blank">github.com/Mariosgian</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/marios-konstantinos-giannoulis-129576289" target="_blank">linkedin.com/in/marios-konstantinos-giannoulis</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Marios Konstantinos Giannoulis. Built with ❤️ and hosted on <a href="https://pages.github.com/" target="_blank">GitHub Pages</a>.</p>
    </footer>
</body>
</html>
