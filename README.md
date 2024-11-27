
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
            color: #000; /* Black links */
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.2rem;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 4px;
        }

        nav a:hover {
            background-color: #000; /* Black background on hover */
            color: #fff; /* White text on hover */
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

        section a {
            color: #000; /* Black links in sections */
            text-decoration: none;
        }

        section a:hover {
            text-decoration: underline;
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
            color: #000; /* Black links in footer */
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Dark Mode Styles */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #121212; /* Dark background */
                color: #fff; /* White text */
            }

            header {
                background-color: #121212; /* Dark background for header */
                color: #fff; /* White text */
            }

            nav a {
                color: #fff; /* White links */
            }

            nav a:hover {
                background-color: #fff; /* White background on hover */
                color: #121212; /* Dark text on hover */
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

            footer a {
                color: #fff; /* White links in footer */
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
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Marios Konstantinos Giannoulis. Built with ❤️ and hosted on <a href="https://pages.github.com/" target="_blank">GitHub Pages</a>.</p>
    </footer>
</body>
</html>
![image](https://github.com/user-attachments/assets/dd7dadcd-d2e5-42e6-9b31-ddb3d1125245)
