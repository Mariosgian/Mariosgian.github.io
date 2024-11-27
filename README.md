<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Website</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #2c3e50; /* Same color as the header */
            color: white; /* Text color to ensure visibility on dark background */
            line-height: 1.6;
            box-sizing: border-box;
        }

        /* Header Styles */
        header {
            background-color: #2c3e50; /* Dark background for header */
            color: white;
            text-align: center;
            padding: 2rem;
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
            color: #ecf0f1; /* Light text color */
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.1rem;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 4px;
        }

        nav a:hover {
            background-color: #3498db; /* Add hover background */
            color: white;
        }

        /* Section Styles */
        section {
            margin: 2rem auto;
            max-width: 1000px;
            padding: 2rem;
            background-color: #ecf0f1; /* Light gray background for sections */
            color: #34495e; /* Darker text color for readability */
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            font-size: 2rem;
            color: #34495e; /* Dark text color for headings */
            border-bottom: 2px solid #e67e22; /* Warm orange border */
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }

        section p, section ul {
            font-size: 1.1rem;
            color: #555;
        }

        section a {
            color: #e67e22; /* Orange links to match border */
            text-decoration: none;
        }

        section a:hover {
            text-decoration: underline;
        }

        /* Projects Section */
        #projects ul {
            list-style-type: none;
            padding-left: 0;
        }

        #projects li {
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
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
            padding: 1.5rem;
            background-color: #2c3e50;
            color: white;
            margin-top: 2rem;
        }

        footer a {
            color: #3498db;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5rem;
            }

            nav a {
                font-size: 1rem;
                padding: 0.5rem;
            }

            section {
                padding: 1.5rem;
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
            <a href="#about">About Me</a>
            <a href="#studies">About My Studies</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
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
            <li>I currently have no projects.</li>
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
