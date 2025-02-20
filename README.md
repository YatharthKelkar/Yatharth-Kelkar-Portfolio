<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yatharth Kelkar - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
            color: white;
            text-align: center;
            overflow-x: hidden;
        }
        header {
            background: linear-gradient(90deg, #ff6f61, #ff4757, #ff9a00);
            padding: 50px 20px;
            font-size: 2em;
            font-weight: bold;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }
        nav {
            display: flex;
            justify-content: center;
            background: #1a1a1a;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-size: 1.2em;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffd700;
        }
        section {
            padding: 100px 20px;
            transition: all 0.5s;
        }
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: url('https://source.unsplash.com/1600x900/?technology,futuristic') center/cover;
            color: white;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.7);
        }
        .hero h1 {
            font-size: 3em;
            animation: fadeIn 2s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .section:nth-child(odd) {
            background: rgba(34, 49, 63, 0.8);
        }
        .section:nth-child(even) {
            background: rgba(44, 62, 80, 0.8);
        }
        .btn {
            background: #ff4757;
            color: white;
            padding: 15px 25px;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
            transition: transform 0.3s, background 0.3s;
        }
        .btn:hover {
            transform: scale(1.1);
            background: #ff9a00;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            padding: 20px;
        }
        .skill {
            background: linear-gradient(45deg, #ff6b81, #ff4757, #ff9a00);
            color: white;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 3px 6px rgba(0,0,0,0.3);
        }
        footer {
            background: #1a1a1a;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        Yatharth Kelkar - Tech Enthusiast
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#tech-analysis">Tech Analysis</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Innovative Web Developer | Python Expert | Linux Power User | Tech Trend Analyst</p>
        <a href="https://www.youtube.com/@YatharthKelkar" target="_blank" class="btn">Visit My YouTube</a>
    </section>
    <section id="about" class="section">
        <h2>About Me</h2>
        <p>Hi, I'm Yatharth Kelkar, a tech enthusiast with a deep passion for coding and open-source technologies. I specialize in web development, Python scripting, and Linux systems. Always eager to explore new trends in technology, I strive to innovate and create impactful digital experiences.</p>
    </section>
    <section id="skills" class="section">
        <h2>My Skills</h2>
        <div class="skills-grid">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">Python</div>
            <div class="skill">JavaScript (Learning)</div>
            <div class="skill">Linux (Ubuntu, Arch, Mint, Fedora)</div>
        </div>
    </section>
    <section id="tech-analysis" class="section">
        <h2>Tech Analysis</h2>
        <p>Keeping up with cutting-edge innovations in the tech world, from software updates to emerging trends in AI, web development, and open-source ecosystems.</p>
    </section>
    <section id="contact" class="section">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:kelkaryatharth@gmail.com">kelkaryatharth@gmail.com</a></p>
        <p>Email: <a href="mailto:kelkaryatharth1@gmail.com">kelkaryatharth1@gmail.com</a></p>
    </section>
    <footer>
        <p>&copy; 2025 Yatharth Kelkar. All Rights Reserved.</p>
    </footer>
</body>
</html>
