<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>My Full HTML Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f4f4f9;
            color: #333;
        }
        header, footer {
            background-color: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #007acc;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #007acc;
        }
        section {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My GitHub Hosted Website</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I am Crisen, and this is my first website hosted on GitHub Pages. I enjoy coding, creating websites, and exploring new technologies.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><strong>Project A:</strong> A simple to-do list app.</li>
                <li><strong>Project B:</strong> Portfolio website.</li>
                <li><strong>Project C:</strong> Blog platform.</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>You can reach me via email at <a href="mailto:crisen@example.com">crisen@example.com</a>.</p>
        </section>
    </main>
    <footer>
        <p>© 2024 Crisen. All rights reserved.</p>
    </footer>
</body>
</html>

