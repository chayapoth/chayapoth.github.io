
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chayapath</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: black;
            color: white;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #001f3f;
        }

        header img {
            width: 100px;
            height: auto;
            border-radius: 50%;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #0074D9;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #001f3f;
            border-radius: 5px;
        }

        #rotating-earth {
            width: 200px;
            height: 200px;
            background: url('earth_image_url') no-repeat center center/cover;
            border-radius: 50%;
            margin: 20px auto;
            animation: rotate 20s linear infinite;
        }

        @keyframes rotate {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }

        section {
            padding: 20px;
            text-align: center;
        }

        .board-members ul {
            list-style-type: none;
            padding: 0;
        }

        .board-members li {
            margin: 5px 0;
        }

        footer {
            background-color: #001f3f;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }

        .nebula-image {
            max-width: 90%;
            height: auto;
            margin: 20px auto;
            border: 2px solid white;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo_url" alt="Chayapath Logo">
        <h1>Chayapath</h1>
    </header>

    <nav>
        <a href="#introduction">Introduction</a>
        <a href="#board-members">Board Members</a>
        <a href="#nebula">Nebula 1</a>
        <a href="#newsletter">Newsletter</a>
        <a href="#contact">Contact</a>
    </nav>

    <div id="rotating-earth"></div>

    <section id="introduction">
        <h2>Introduction</h2>
        <p>Chayapath is a youth-based organization that aims to spread the mystery of space around Bangladesh. Our slogan is - "Let's get lost in the infinite silence of space!" We conduct our work keeping this slogan in mind. So why the delay? Join us today to get lost in the infinite silence of space!</p>
    </section>

    <section id="board-members" class="board-members">
        <h2>Board Members</h2>
        <ul>
            <li>Ahnad bin Hossain</li>
            <li>Yashfi Islam</li>
            <li>Muminul Haq Maruf</li>
            <li>Sanajidul Mohsinin Tamim</li>
            <li>Rafi Islam</li>
        </ul>
    </section>

    <section id="nebula">
        <h2>Nebula 1</h2>
        <img src="nebula_image_url" alt="Nebula 1" class="nebula-image">
    </section>

    <section id="newsletter">
        <h2>Newsletter</h2>
        <p>Subscribe to our newsletter "Darwin" to stay updated!</p>
        <form>
            <input type="email" placeholder="Enter your email" required>
            <button type="submit">Subscribe</button>
        </form>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:galaxy.artk@gmail.com" style="color: #0074D9;">galaxy.artk@gmail.com</a></p>
        <p>Facebook: <a href="https://www.facebook.com/profile.php?id=61557178986162&mibextid=ZbWKwL" target="_blank" style="color: #0074D9;">Visit our page</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Chayapath. All rights reserved.</p>
    </footer>
</body>
</html>
