# viki-s-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Victoria Okula</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F5F5DC;
            color: #333;
        }
        header {
            background-color: #FFF;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        section {
            padding: 20px;
        }
        .portfolio img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
        }
        .social-media a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #FFF;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #CCC;
            border-radius: 4px;
        }
        .contact-form button {
            padding: 10px 20px;
            background-color: #333;
            color: #FFF;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        footer {
            background-color: #FFF;
            padding: 10px;
            text-align: center;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Victoria Okula</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
        <a href="#social-media">Social Media</a>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Victoria Okula. I'm passionate about photography and coffee. My ultimate goal is to be able to make a living with either of my passions. Welcome to my personal webpage where you can learn more about me and my work.</p>
    </section>
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <!-- Example images, replace with your own -->
            <img src="https://via.placeholder.com/300" alt="Sample Photo 1">
            <img src="https://via.placeholder.com/300" alt="Sample Photo 2">
            <img src="https://via.placeholder.com/300" alt="Sample Photo 3">
        </div>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <section id="social-media">
        <h2>Social Media</h2>
        <div class="social-media">
            <a href="https://instagram.com/yourprofile" target="_blank">Instagram</a>
            <a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
            <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Victoria Okula. All rights reserved.</p>
    </footer>
</body>
</html>
