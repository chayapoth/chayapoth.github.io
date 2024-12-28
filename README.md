<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Chayapath</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <img src="https://drive.google.com/uc?id=1KdLRXp6efbQxAmUZh7PmWKDWN1cm7AHn" alt="Chayapath Logo" class="logo">
    </header>

    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#introduction">Introduction</a></li>
            <li><a href="#board-members">Board Members</a></li>
            <li><a href="#nebula-image">Nebula 1</a></li>
            <li><a href="#newsletter">Newsletter</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Introduction Section -->
    <section id="introduction">
        <h2>Introduction</h2>
        <p>Chayapath is a youth-based organization that aims to spread the mystery of space around Bangladesh. Our slogan is - "Let's get lost in the infinite silence of space!". We conduct our work keeping this slogan in mind. So why the delay? Join us today to get lost in the infinite silence of space!</p>
    </section>

    <!-- Board Members Section -->
    <section id="board-members">
        <h2>Board Members</h2>
        <ul>
            <li>Ahnad bin Hossain</li>
            <li>Yashfi Islam</li>
            <li>Muminul Haq Maruf</li>
            <li>Sanajidul Mohsinin Tamim</li>
            <li>Rafi Islam</li>
        </ul>
    </section>

    <!-- Nebula 1 Image Section -->
    <section id="nebula-image">
        <h2>Nebula 1</h2>
        <img src="https://drive.google.com/uc?id=1lrR3Ksxor_5Fmvgw1FLMpS3OsBiJJc72" alt="Nebula 1 Image">
    </section>

    <!-- Newsletter Subscription Section -->
    <section id="newsletter">
        <h2>Newsletter Subscription</h2>
        <form action="#" method="post">
            <label for="email">Enter your email for our newsletter:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <button type="submit">Subscribe</button>
        </form>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:galaxy.artk@gmail.com">galaxy.artk@gmail.com</a></p>
        <p>Follow us on Facebook: <a href="https://www.facebook.com/profile.php?id=61557178986162&mibextid=ZbWKwL" target="_blank">Facebook Page</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Chayapath. All Rights Reserved.</p>
    </footer>
</body>
</html>
/* General styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: white;
    color: #333;
}

/* Header and logo */
header {
    text-align: center;
    margin: 20px 0;
}

.logo {
    width: 200px;
    height: auto;
}

/* Navigation Bar */
nav {
    background-color: #0056b3;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Sections */
section {
    padding: 20px;
    margin: 20px;
}

h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

ul {
    list-style-type: none;
}

ul li {
    font-size: 18px;
    margin-bottom: 5px;
}

#nebula-image img {
    width: 100%;
    max-width: 600px;
    height: auto;
    display: block;
    margin: 20px auto;
}

#newsletter form {
    text-align: center;
}

#newsletter input {
    padding: 10px;
    margin-right: 10px;
    font-size: 16px;
}

#newsletter button {
    padding: 10px 20px;
    font-size: 16px;
    background-color: #0056b3;
    color: white;
    border: none;
}

#newsletter button:hover {
    background-color: #004080;
}

/* Contact */
#contact a {
    color: #0056b3;
    text-decoration: none;
}

#contact a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background-color: #f1f1f1;
    margin-top: 40px;
}
