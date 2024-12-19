<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #95DBE5; /* Tanager Turquoise */
            color: #078282; /* Teal Blue */
        }
        header {
            background-color: #339E66; /* Kelly Green */
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #078282; /* Teal Blue */
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #339E66; /* Kelly Green */
        }
        section {
            padding: 20px;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .project-card {
            background-color: white;
            border: 1px solid #078282; /* Teal Blue */
            border-radius: 8px;
            padding: 15px;
            text-align: center;
        }
        .project-card img {
            max-width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #078282; /* Teal Blue */
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>Hi, I’m [Your Name], a passionate [Your Profession].</p>
    </header>
    
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.</p>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project-card">
                <img src="project1.jpg" alt="Project 1">
                <h3>Project One</h3>
                <p>Brief description of Project One.</p>
            </div>
            <div class="project-card">
                <img src="project2.jpg" alt="Project 2">
                <h3>Project Two</h3>
                <p>Brief description of Project Two.</p>
            </div>
            <div class="project-card">
                <img src="project3.jpg" alt="Project 3">
                <h3>Project Three</h3>
                <p>Brief description of Project Three.</p>
            </div>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4"></textarea><br><br>

            <button type="submit" style="background-color: #339E66; color: white; border: none; padding: 10px 20px; border-radius: 4px;">Submit</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>
