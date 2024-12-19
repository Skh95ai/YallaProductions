<html lang="en">
<head>
    <!-- Start of headStart -->
    
    <!-- End of headStart -->
    <meta name="viewport" content="width=device-width">
    <meta name="generator" content="Framer 83b8097">
    <title>Looma - Free Photography Portfolio</title>
    <meta name="description" content="Looma is a free photography portfolio Framer website template designed for photographers, videographers, and photography agencies focused on fashion. Its sleek and minimal design makes it perfect for showcasing your creative work beautifully.">
    <meta name="framer-search-index" content="https://framerusercontent.com/sites/SnXe6T2fLRnSqF611zpzu/searchIndex-lDnqX_HYIyrX.json">
    <link href="https://framerusercontent.com/sites/icons/default-favicon-light.v1.png" rel="icon" media="(prefers-color-scheme: light)">
    <link href="https://framerusercontent.com/sites/icons/default-favicon-dark.v1.png" rel="icon" media="(prefers-color-scheme: dark)">
    <link rel="apple-touch-icon" href="https://framerusercontent.com/sites/icons/default-touch-icon.v3.png">
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:title" content="Looma - Free Photography Portfolio">
    <meta property="og:description" content="Looma is a free photography portfolio Framer website template designed for photographers, videographers, and photography agencies focused on fashion. Its sleek and minimal design makes it perfect for showcasing your creative work beautifully.">
    <meta property="og:image" content="https://framerusercontent.com/images/WEOHOO7whbacpAWKPgBFfn2wsw.jpg">
    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Looma - Free Photography Portfolio">
    <meta name="twitter:description" content="Looma is a free photography portfolio Framer website template designed for photographers, videographers, and photography agencies focused on fashion. Its sleek and minimal design makes it perfect for showcasing your creative work beautifully.">
    <meta name="twitter:image" content="https://framerusercontent.com/images/WEOHOO7whbacpAWKPgBFfn2wsw.jpg">

    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background-color: #008080; /* Teal background */
            color: #fff;
            padding: 20px;
            text-align: center;
            width: 100%;
            height: 15vh; /* Further reduces the vertical height */
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
        }

        header p {
            font-size: 1em;
            margin-top: 10px;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            flex: 1;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2 {
            margin-bottom: 10px;
        }

        .about-section, .services-section, .contact-section {
            text-align: center;
            margin: 40px 0;
            background: linear-gradient(135deg, #008080 0%, #ff00ff 100%); /* Mix of teal and magenta */
            color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .team {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .team-member {
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 300px;
            color: #333; /* Ensure text is visible */
        }

        .team-member img {
            width: 100%;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .service {
            background-color: #ffd700; /* Gold background for services */
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 300px;
            color: #333; /* Ensure text is visible */
        }

        .contact-form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            max-width: 500px;
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact-form button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background-color: #333;
            color: #fff;
            cursor: pointer;
            font-size: 16px;
        }

        .contact-form button:hover {
            background-color: #555;
        }

        footer {
            background-color: #008080; /* Teal background */
            color: #fff;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 40px; /* Increased gap for better separation */
            margin-top: 20px;
            border-top: 1px solid #555; /* Add a line to separate links */
            padding-top: 10px;
        }

        .social-links a {
            color: #fff;
            text-decoration: none;
            font-size: 24px;
        }

        .social-links a:hover {
            color: #ddd;
        }

        .work-section {
            text-align: center;
            margin: 40px 0;
        }

        .work-videos {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .work-video {
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 300px;
        }

        .work-video iframe {
            width: 100%;
            border-radius: 8px;
        }

        .video-background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <video autoplay muted loop class="video-background">
        <source src="your-video-url.mp4" type="video/mp4">
    </video>

    <header>
        <h1>Yalla Productions</h1>
        <p>Where Stories Come to Life</p>
        <nav>
            <a href="#about">About Us</a>
            <a href="#services">Services</a>
            <a href="#team">Team</a>
            <a href="#contact">Contact</a>
            <a href="#work">Work</a>
        </nav>
    </header>

    <div class="container">
        <section id="about" class="about-section">
            <h2>About Us</h2>
            <p>At Yalla Productions, we bring stories to life with creativity, passion, and professionalism. Whether you're a business or an individual, we focus on your success and craft unforgettable visuals that truly connect. We understand the challenges businesses face in reaching their full potential. We combine our passion for cinematography and filmmaking with creativity, professionalism, and a modern touch, helping your business thrive online to stand out. Our priority is making our clients and partners not just satisfied but truly proud of their growth and achievements. We’re here to help you break barriers, connect with new audiences, and build a legacy of success. Together, let’s transform your vision into reality and create something extraordinary.</p>
        </section>

        <section id="services" class="services-section">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service">
                    <h3>Corporate Videos</h3>
                    <p>Helping businesses tell their stories and grow their brands.</p>
                </div>
                <div class="service">
                    <h3>Live Events</h3>
                    <p>Capturing life's most meaningful moments.</p>
                </div>
                <div class="service">
                    <h3>Social Media Content</h3>
                    <p>Creating engaging content that resonates with your audience.</p>
                </div>
                <div class="service">
                    <h3>Documentaries</h3>
                    <p>Crafting powerful and captivating documentaries.</p>
                </div>
            </div>
        </section>

        <section id="team" class="team-section">
            <h2>Meet the Team</h2>
            <div class="team">
                <div class="team-member">
                    <img src="https://via.placeholder.com/150" alt="Sanad Khalaileh">
                    <h3>Sanad Khalaileh</h3>
                    <p>Owner and Director</p>
                </div>
                <div class="team-member">
                    <img src="https://via.placeholder.com/150" alt="Justin Vazquez">
                    <h3>Justin Vazquez</h3>
                    <p>Director of Photography</p>
                </div>
            </div>
        </section>

        <section id="work" class="work-section">
            <h2>Our Work</h2>
            <div class="work-videos">
                <div class="work-video">
                    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
                    <p>Example Video 1</p>
                </div>
                <div class="work-video">
                    <iframe src="https://www.youtube.com/embed/3JZ_D3ELwOQ" frameborder="0" allowfullscreen></iframe>
                    <p>Example Video 2</p>
                </div>
                <div class="work-video">
                    <iframe src="https://www.youtube.com/embed/tgbNymZ7vqY" frameborder="0" allowfullscreen></iframe>
                    <p>Example Video 3</p>
                </div>
                <div class="work-video">
                    <iframe src="https://www.youtube.com/embed/5qap5aO4i9A" frameborder="0" allowfullscreen></iframe>
                    <p>Example Video 4</p>
                </div>
            </div>
        </section>

        <section id="contact" class="contact-section">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Yalla Productions. All Rights Reserved.</p>
        <div class="social-links">
            <a href="https://youtube.com" target="_blank">YouTube</a>
            <a href="https://linkedin.com" target="_blank">LinkedIn</a>
            <a href="https://instagram.com" target="_blank">Instagram</a>
        </div>
    </footer>
</body>
</html>
