<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Editkaro.in</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        section {
            padding: 50px;
            text-align: center;
        }
        #home {
            background: #ff4d4d;
            color: white;
        }
        #portfolio {
            background: #f2f2f2;
        }
        .portfolio-items {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .category {
            background: #333;
            color: white;
            margin: 10px;
            padding: 15px;
            border-radius: 5px;
            font-size: 18px;
        }
        #about {
            background: #ffcc00;
        }
        #contact {
            background: #4CAF50;
            color: white;
        }
        form input, form textarea, form button {
            display: block;
            width: 80%;
            margin: 10px auto;
            padding: 10px;
            border: none;
            border-radius: 5px;
        }
        form button {
            background: #333;
            color: white;
            cursor: pointer;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Editkaro.in</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>About Editkaro.in</h2>
        <p>Your go-to agency for social media marketing and video editing.</p>
        <form>
            <label for="email">Subscribe to our newsletter:</label>
            <input type="email" id="email" required>
            <button type="submit">Subscribe</button>
        </form>
    </section>
    
    <section id="portfolio">
        <h2>Our Work</h2>
        <p>Showcasing our best video editing projects.</p>
        <div class="portfolio-items">
            <div class="category">Short Form</div>
            <div class="category">Long Form</div>
            <div class="category">Gaming Videos</div>
            <div class="category">Football Edits</div>
            <div class="category">eCommerce Ads</div>
            <div class="category">Documentary Style</div>
            <div class="category">Color Grading</div>
            <div class="category">Anime Videos</div>
            <div class="category">Ads</div>
        </div>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Our mission and vision to deliver high-quality video content.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="tel" placeholder="Your Phone" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 Editkaro.in. All rights reserved.</p>
    </footer>
</body>
</html>
