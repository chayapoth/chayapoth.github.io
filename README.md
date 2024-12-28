
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chayapoth</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #282c34;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #333;
            color: #fff;
            overflow: hidden;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            padding: 0.75rem 1.5rem;
            display: block;
        }
        nav ul li a:hover {
            background: #575757;
        }
        section {
            padding: 1.5rem;
            max-width: 800px;
            margin: auto;
        }
        .members {
            list-style: none;
            padding: 0;
        }
        .members li {
            margin: 0.5rem 0;
        }
        .contact a {
            color: #007BFF;
            text-decoration: none;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            background: #282c34;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Chayapoth</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#introduction">Introduction</a></li>
            <li><a href="#members">Board Members</a></li>
            <li><a href="#project">Project: Niharika</a></li>
            <li><a href="#subscription">Subscribe</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <section id="introduction">
        <h2>Introduction</h2>
        <p>Chayapoth is a youth-based organization whose mission is to spread the mystery of space around Bangladesh. Our slogan is - "Let's get lost in the infinite silence of space!" We conduct our work keeping this slogan in mind. So why the delay? Join us today to get lost in the infinite silence of space!</p>
    </section>

    <section id="members">
        <h2>Board Members</h2>
        <ul class="members">
            <li>Ahanad Bin Hossain</li>
            <li>Yeshfi Islam</li>
            <li>Mominul Haque Maruf</li>
            <li>Sanajidul Muhsinin Tamim</li>
            <li>Rafi Islam</li>
        </ul>
    </section>

    <section id="project">
        <h2>Project: Niharika</h2>
        <p>Add an image of Niharika project here:</p>
        <img src="path-to-your-image.jpg" alt="Niharika Project" style="width:100%; max-width:800px;">
    </section>

    <section id="subscription">
        <h2>Subscribe to Durbeen</h2>
        <form>
            <label for="email">Enter your email:</label>
            <input type="email" id="email" name="email" required>
            <button type="submit">Subscribe</button>
        </form>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:galaxy.artk@gmail.com">galaxy.artk@gmail.com</a></p>
        <p>Facebook: <a href="https://www.facebook.com/profile.php?id=61557178986162&mibextid=ZbWKwL" target="_blank">Visit our Facebook page</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Chayapoth. All rights reserved.</p>
    </footer>
</body>
</html>
