<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Personal website of Your Name.">
    <meta name="author" content="Your Name">
    <meta name="keywords" content="personal website, Your Name, portfolio, contact, GitHub">
    <meta name="robots" content="index, follow">
    <title>Your Name - Personal Website</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <style>
        /* Reset some default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body Styling */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Header Styling */
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        header p {
            font-size: 18px;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* Section Styling */
        section {
            padding: 40px 20px;
            text-align: center;
        }

        section h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .project {
            margin-bottom: 20px;
        }

        .project h3 {
            font-size: 22px;
            margin-bottom: 10px;
        }

        .project a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }

        .project a:hover {
            text-decoration: underline;
        }

        /* Footer Styling */
        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        footer p {
            font-size: 14px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 24px;
            }

            nav ul {
                display: flex;
                flex-direction: column;
                align-items: center;
            }

            nav ul li {
                margin: 10px 0;
            }
        }
    </style>
</head>

<body>
    <header>
        <div class="container">
            <h1>Hi, I'm Your Name!</h1>
            <p>Welcome to my personal website</p>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="https://github.com/yourgithubusername" target="_blank">GitHub</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>I'm a passionate web developer who loves building responsive and user-friendly websites. I have experience with HTML, CSS, JavaScript, and frameworks like React and Node.js.</p>
            <p>In my free time, I enjoy contributing to open-source projects and learning new technologies.</p>
        </section>

        <section id="portfolio">
            <h2>My Portfolio</h2>
            <div class="project">
                <h3>Project 1: Personal Blog</h3>
                <p>This is a personal blog where I write about web development and tech-related topics. Built using HTML, CSS, and JavaScript.</p>
                <a href="https://github.com/yourgithubusername/personal-blog" target="_blank">View on GitHub</a>
            </div>
            <div class="project">
                <h3>Project 2: E-Commerce Website</h3>
                <p>A fully functional e-commerce website with user authentication, cart functionality, and a responsive design. Built using React and Firebase.</p>
                <a href="https://github.com/yourgithubusername/e-commerce" target="_blank">View on GitHub</a>
            </div>
            <div class="project">
                <h3>Project 3: Portfolio Website</h3>
                <p>This is my personal portfolio website, built using HTML, CSS, and JavaScript.</p>
                <a href="https://github.com/yourgithubusername/portfolio" target="_blank">View on GitHub</a>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>If you'd like to get in touch with me, feel free to reach out through any of the platforms below:</p>
            <ul>
                <li>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></li>
                <li>LinkedIn: <a href="https://linkedin.com/in/yourlinkedinprofile" target="_blank">LinkedIn Profile</a></li>
                <li>GitHub: <a href="https://github.com/yourgithubusername" target="_blank">GitHub Profile</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Your Name. All rights reserved.</p>
        </div>
    </footer>

</body>

</html>
