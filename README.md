
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Website</title>
    <style>
        /* Default (Light Mode) Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff; /* White background for light mode */
            color: #000; /* Black text */
            line-height: 1.6;
            box-sizing: border-box;
        }

        /* Global link styles: blue and no underline */
        a {
            color: #007BFF; /* Standard blue color for links */
            text-decoration: none; /* Removes underline */
        }

        /* Hover effect for links */
        a:hover {
            color: #0056b3; /* Darker blue for hover */
            text-decoration: none; /* Keeps underline removed */
        }

        /* Header Styles */
        header {
            background-color: #fff; /* White background for header */
            color: #000; /* Black text */
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
            background-color: #f0f0f0; /* Light gray background on hover */
        }

        /* Section Styles */
        section {
            margin: 2rem auto;
            max-width: 1000px;
            padding: 3rem;
            background-color: #f7f7f7; /* Light gray background for sections */
            color: #000; /* Black text */
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            font-size: 2rem;
            color: #000; /* Black section headings */
            border-bottom: 2px solid #000; /* Black border below heading */
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }

        section p, section ul {
            font-size: 1.1rem;
        }

        /* Footer Styles */
        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #fff; /* White background for footer */
            color: #000; /* Black text */
            margin-top: 2rem;
        }

        footer a {
            font-weight: bold; /* Footer links stand out */
        }

        /* Dark Mode Styles */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #121212; /* Dark background */
                color: #fff; /* White text */
            }

            header {
                background-color: #121212; /* Dark header background */
                color: #fff; /* White text */
            }

            /* Ensure links are blue and visible in dark mode */
            a {
                color: #4A90E2; /* Bright blue for better visibility in dark mode */
            }

            a:hover {
                color: #82C0FF; /* Lighter blue on hover in dark mode */
            }

            section {
                background-color: #1c1c1c; /* Dark gray background for sections */
                color: #fff; /* White text */
            }

            section h2 {
                color: #fff; /* White section headings */
                border-bottom: 2px solid #fff; /* White border below heading */
            }

            footer {
                background-color: #121212; /* Dark footer background */
                color: #fff; /* White text */
            }
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
            <li>LinkedIn: <a href="https://www.linkedin.com/in/marios-konstantinos-giannoulis-129576289" target="_blank">linkedin.com/in/marios-konstantinos-giannoulis</a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Marios Konstantinos Giannoulis. Built with ❤️ and hosted on <a href="https://pages.github.com/" target="_blank">GitHub Pages</a>.</p>
    </footer>
</body>
</html>
