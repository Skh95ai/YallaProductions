# YallaProductions" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Skh95ai/YallaProductions.git
git push -u origin main
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yalla Productions</title>
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
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
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
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 300px;
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
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Yalla Productions</h1>
        <p>Where Stories Come to Life</p>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#team">Team</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="about" class="about-section">
            <h2>About Us</h2>
            <p>At Yalla Productions, we bring stories to life with creativity, passion, and professionalism. Whether you're a business or an individual, we focus on your success and craft unforgettable visuals that truly connect.</p>
        </section>

        <section id="services" class="services-section">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service">
                    <h3>Corporate Videos</h3>
                    <p>Helping businesses tell their stories and grow their brands.</p>
                </div>
                <div class="service">
                    <h3>Event Coverage</h3>
                    <p>Capturing life's most meaningful moments.</p>
                </div>
                <div class="service">
                    <h3>Social Media Content</h3>
                    <p>Creating engaging content that resonates with your audience.</p>
                </div>
            </div>
        </section>

        <section id="team" class="team-section">
            <h2>Meet the Team</h2>
            <div class="team">
                <div class="team-member">
                    <img src="https://via.placeholder.com/150" alt="Team Member">
                    <h3>John Doe</h3>
                    <p>Creative Director</p>
                </div>
                <div class="team-member">
                    <img src="https://via.placeholder.com/150" alt="Team Member">
                    <h3>Jane Smith</h3>
                    <p>Lead Videographer</p>
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
    </footer>
</body>
</html>
