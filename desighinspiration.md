I like the style of : "Clean Tech"
Color Scheme: Professional Navy Blue with Minecraft Green accents.

Layout: Organized Grid System with balanced spacing (multiples of 8px).

Visuals: White Cards with soft shadows to make projects pop.

Interactivity: Hover effects that make cards "lift" when you touch them.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Merjen's Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <nav>
            <div class="logo">Merjen<span>.Dev</span></div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about" class="hero">
        <h1>Future Software Engineer</h1>
        <p>Hi, I'm Merjen. I love <strong>Minecraft</strong> and building logical systems. Now, I'm learning to turn that logic into code!</p>
    </section>

    <section id="projects">
        <h2 class="section-title">My Projects</h2>
        <div class="project-grid">
            
            <div class="project-card">
                <div class="icon">⏱️</div>
                <h3>Quiz Game</h3>
                <p>An interactive quiz where I added a <strong>timer</strong> for each question.</p>
            </div>

            <div class="project-card">
                <div class="icon">🔢</div>
                <h3>Calculator</h3>
                <p>A functional math tool to practice JavaScript variables and inputs.</p>
            </div>

            <div class="project-card">
                <div class="icon">⛏️</div>
                <h3>Minecraft Logic</h3>
                <p>Engineering automated systems using Redstone circuits.</p>
            </div>

        </div>
    </section>

    <footer id="contact">
        <p>Contact: amanmyradovamerjen350@gmail.com</p>
    </footer>

</body>
</html>