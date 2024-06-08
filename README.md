<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>King Dynasty - DJ & Entrepreneur</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #ffffff;
        }
        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #ff4081;
        }
        header h1 {
            font-size: 2.5em;
            margin: 0;
            color: #ff4081;
        }
        header p {
            font-size: 1.2em;
            margin: 5px 0 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #282828;
            border-bottom: 2px solid #ff4081;
        }
        nav a {
            color: #ffffff;
            padding: 15px 20px;
            text-decoration: none;
            text-align: center;
            transition: background-color 0.3s, color 0.3s;
        }
        nav a:hover {
            background-color: #ff4081;
            color: #121212;
        }
        .container {
            padding: 20px;
        }
        .section {
            padding: 20px;
            margin: 20px 0;
            background-color: #1f1f1f;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255, 64, 129, 0.5);
        }
        .section h2 {
            color: #ff4081;
        }
        .services ul {
            list-style-type: none;
            padding: 0;
        }
        .services li {
            background-color: #282828;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(255, 64, 129, 0.5);
        }
        .portfolio img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 10px;
        }
        footer {
            background-color: #1f1f1f;
            color: #ff4081;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            border-top: 2px solid #ff4081;
        }
    </style>
</head>
<body>

    <header>
        <h1>King Dynasty</h1>
        <p>DJ, Audio Engineer, and Entrepreneur</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="about" class="section about">
            <h2>About Me</h2>
            <p>My name is King Dynasty. I am a full-time DJ specializing in karaoke and club events. I have a passion for DJing karaoke gigs the most, but I also create websites, logos, party/event flyers, and music artist album covers. Additionally, I work as an audio engineer at two recording studios, recording hip-hop and R&B artists for $60 an hour and mastering songs for $100. I am also an entrepreneur, offering business consulting services.</p>
        </section>

        <section id="services" class="section services">
            <h2>Services</h2>
            <ul>
                <li>DJing for Karaoke and Club Events</li>
                <li>Website Development</li>
                <li>Logo Design</li>
                <li>Party and Event Flyers</li>
                <li>Music Artist Album Covers</li>
                <li>Audio Engineering (Recording: $60/hr, Mastering: $100)</li>
                <li>Business Consulting</li>
            </ul>
        </section>

        <section id="portfolio" class="section portfolio">
            <h2>Portfolio</h2>
            <p>Check out some of my work:</p>
            <img src="https://via.placeholder.com/800x400?text=DJing+Event" alt="DJing Event">
            <img src="https://via.placeholder.com/800x400?text=Website+Development" alt="Website Development">
            <img src="https://via.placeholder.com/800x400?text=Logo+Design" alt="Logo Design">
            <img src="https://via.placeholder.com/800x400?text=Party+Flyer" alt="Party Flyer">
            <img src="https://via.placeholder.com/800x400?text=Album+Cover" alt="Album Cover">
            <img src="https://via.placeholder.com/800x400?text=Recording+Studio" alt="Recording Studio">
        </section>

        <section id="contact" class="section contact">
            <h2>Contact</h2>
            <p>If you'd like to get in touch, please reach out to me at:</p>
            <p>Email: <a href="mailto:kingdynasty@example.com" style="color: #ff4081;">kingdynasty@example.com</a></p>
            <p>Phone: <a href="tel:1234567890" style="color: #ff4081;">(123) 456-7890</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 King Dynasty. All rights reserved.</p>
    </footer>

</body>
</html>
