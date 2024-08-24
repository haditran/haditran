<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haditran | Professional Translation Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1><a href="index.html">Haditran</a></h1>
            <nav>
                <ul>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#blog">Blog</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h2>Breaking Language Barriers with Precision</h2>
            <p>Professional Translation Services for Every Need</p>
            <a href="#contact" class="cta-button">Get a Free Quote</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <h2>Our Translation Services</h2>
            <div class="service">
                <h3>Document Translation</h3>
                <p>High-quality document translation services for all types of documents.</p>
            </div>
            <div class="service">
                <h3>Website Localization</h3>
                <p>Ensure your website reaches a global audience with our localization services.</p>
            </div>
            <!-- Add more services as needed -->
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Haditran</h2>
            <p>Learn more about our mission, team, and approach to translation services.</p>
            <!-- Add more details as needed -->
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="blog">
        <div class="container">
            <h2>Translation Insights and News</h2>
            <!-- Add blog posts or articles here -->
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Get in Touch</h2>
            <form action="submit_form.php" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Haditran. All rights reserved.</p>
            <ul>
                <li><a href="#">Privacy Policy</a></li>
                <li><a href="#">Terms of Service</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

.container {
    width: 80%;
    margin: 0 auto;
    overflow: hidden;
}

/* Header */
header {
    background: #333;
    color: #fff;
    padding: 10px 0;
}

header h1 {
    float: left;
}

header h1 a {
    color: #fff;
    text-decoration: none;
}

nav ul {
    float: right;
    list-style: none;
}

nav ul li {
    display: inline;
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Hero Section */
.hero {
    background: #333;
    color: #fff;
    padding: 50px 0;
    text-align: center;
}

.hero .cta-button {
    display: inline-block;
    background: #e8491d;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

/* Services Section */
.services {
    padding: 20px 0;
    text-align: center;
}

.service {
    margin: 20px 0;
}

/* About Us Section */
.about {
    padding: 20px 0;
    text-align: center;
}

/* Blog Section */
.blog {
    padding: 20px 0;
    text-align: center;
}

/* Contact Section */
.contact {
    padding: 20px 0;
}

.contact form {
    max-width: 600px;
    margin: 0 auto;
}

.contact form label {
    display: block;
    margin: 10px 0 5px;
}

.contact form input,
.contact form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
}

.contact form button {
    background: #e8491d;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

footer ul {
    list-style: none;
}

footer ul li {
    display: inline;
    margin: 0 10px;
}

footer ul li a {
    color: #fff;
    text-decoration: none;
}


