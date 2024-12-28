
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chayapath</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: white;
            background-color: black;
            overflow-x: hidden;
        }
        header {
            text-align: center;
            padding: 20px;
        }
        header img {
            width: 150px;
            height: auto;
        }
        .earth {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) rotate(0deg);
            width: 300px;
            height: 300px;
            border-radius: 50%;
            background: url('earth_image_url') no-repeat center center/cover;
            animation: rotateEarth 20s linear infinite;
        }
        @keyframes rotateEarth {
            from {
                transform: translate(-50%, -50%) rotate(0deg);
            }
            to {
                transform: translate(-50%, -50%) rotate(360deg);
            }
        }
        nav {
            background-color: blue;
            padding: 10px 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
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
        .section {
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            text-align: center;
        }
        .board-members ul {
            list-style-type: none;
            padding: 0;
        }
        .board-members ul li {
            margin: 10px 0;
        }
        .nebula {
            margin: 20px auto;
            max-width: 90%;
        }
        .nebula img {
            width: 100%;
            height: auto;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: blue;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://drive.google.com/uc?export=view&id=1KdLRXp6efbQxAmUZh7PmWKDWN1cm7AHn" alt="Chayapath Logo">
    </header>

    <div class="earth"></div>

    <nav>
        <ul>
            <li><a href="#introduction">Introduction</a></li>
            <li><a href="#board">Board Members</a></li>
            <li><a href="#nebula">Niharika 1</a></li>
            <li><a href="#newsletter">Newsletter</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div id="introduction" class="section">
        <h1>Welcome to Chayapath</h1>
        <p>Chayapath is a youth-based organization that aims to spread the mystery of space around Bangladesh. Our slogan is - "Let's get lost in the infinite silence of space!" We conduct our work keeping this slogan in mind. So why the delay? Join us today to get lost in the infinite silence of space!</p>
    </div>

    <div id="board" class="section board-members">
        <h2>Board Members</h2>
        <ul>
            <li>Ahnad bin Hossain</li>
            <li>Yashfi Islam</li>
            <li>Muminul Haq Maruf</li>
            <li>Sanajidul Mohsinin Tamim</li>
            <li>Rafi Islam</li>
        </ul>
    </div>

    <div id="nebula" class="section nebula">
        <h2>Niharika 1</h2>
        <img src="https://drive.google.com/uc?export=view&id=1lrR3Ksxor_5Fmvgw1FLMpS3OsBiJJc72" alt="Niharika 1 Image">
        <img src="https://drive.google.com/uc?export=view&id=15Db-7JtL3LNiDfUd-JAEAtqEWpPFzbrO" alt="Second Niharika Image">
    </div>

    <div id="newsletter" class="section">
        <h2>Subscribe to our Newsletter</h2>
        <p>Join "Darwin" for the latest updates and insights!</p>
        <form>
            <input type="email" placeholder="Enter your email" required>
            <button type="submit">Subscribe</button>
        </form>
    </div>

    <div id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:galaxy.artk@gmail.com">galaxy.artk@gmail.com</a></p>
        <p>Facebook: <a href="https://www.facebook.com/profile.php?id=61557178986162&mibextid=ZbWKwL" target="_blank">Visit our Facebook Page</a></p>
    </div>

    <footer>
        <p>&copy; 2024 Chayapath. All rights reserved.</p>
    </footer>
</body>
</html>
