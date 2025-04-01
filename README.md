# ABROAD-ACTIVISM
ABROAD ACTIVISM is a dynamic  website that combines the thrill of international travel with the impact of social activism. Our platform provides users with opportunities to explore working holidays, volunteer programs, and cultural exchanges across various destinations while participating in meaningful activism .



< html>
<head>
    
<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ABROAD ACTIVISM</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
   
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            color: #fff;
            overflow-x: hidden;
            background: #f8f8f8;
        }
        .top-bar {
            background: #5a6e3a;
            color: white;
            text-align: center;
            padding: 10px 0;
            font-size: 14px;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 5%;
            background: #5a6e3a;
            position: absolute;
            width: 100%;
            top: 0;
            z-index: 10;
        }
        .logo {
            font-size: 40px;
            font-weight: bold;
            color: #fff;
            font-family: 'Playfair Display', serif;
            letter-spacing: 3px;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            padding: 0;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            transition: 0.3s;
        }
        nav ul li a:hover {
            color: #d4af37;
        }
        .hero {
            position: relative;
            height: 100vh;
            width: 100vw;
            background: url('https://fortunetours.in/wp-content/uploads/2023/11/Andaman.jpg') no-repeat center center;
            background-size: cover;
            display: flex;
            align-items: center;
            justify-content: flex-start;
            padding-left: 10%;
        }
        h1 {
            font-size: 65px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 3px;
            line-height: 1.2;
            font-family: 'Playfair Display', serif;
            color: #fff;
        }
        h1 span {
            font-family: 'Dancing Script', cursive;
            font-size: 75px;
            color: #d4af37;
        }
        p {
            font-size: 22px;
            margin-top: 10px;
            max-width: 500px;
            line-height: 1.5;
            color: #fff;
        }
        .cta-button {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            background: #d4af37;
            color: white;
            font-size: 20px;
            font-weight: bold;
            border-radius: 8px;
            text-decoration: none;
            transition: 0.3s;
        }
        .cta-button:hover {
            background: #b7950b;
        }
        .program-section {
            background: #fff;
            padding: 60px 10%;
        }
        .program-section h2 {
            color: #5a6e3a;
            font-size: 40px;
            font-family: 'Playfair Display', serif;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        .program-section h2 span {
            font-family: 'Dancing Script', cursive;
            font-size: 50px;
            color: #d4af37;
        }
        .program-section p {
            color: #333;
            font-size: 18px;
            max-width: 600px;
        }
        .program-container {
            display: flex;
            gap: 20px;
            overflow-x: auto;
            padding-top: 20px;
        }
        .destination-card {
            border-radius: 12px;
            width: 250px;
            height: 300px;
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: flex-end;
            padding: 20px;
            color: white;
            font-size: 22px;
            font-weight: bold;
            text-shadow: 3px 3px 5px rgba(0,0,0,0.6);
            font-family: 'Playfair Display', serif;
            transition: transform 0.3s ease;
        }
        .destination-card:hover {
            transform: scale(1.05);
        }
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            color: #fff;
            background: #2c2c2c;
        }
        .activism-section {
            padding: 50px 10%;
            background: url('https://cdn.pixabay.com/photo/2017/08/30/06/42/texture-2691062_1280.png') no-repeat center/cover;
            position: relative;
        }
        .activism-section h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 80px;
            color:#d4af37 ;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
            margin: 0;
        }
        .activism-container {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }
        .activism-card {
            background: #fff;
            color: #333;
            width: 450px;
            height: 450px;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            background-size: cover;
            background-position: center;
            position: relative;
            transition: transform 0.3s;
        }
        .activism-card:hover {
            transform: scale(1.05);
        }
        .activism-card::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4);
        }
        .activism-card-content {
            position: relative;
            z-index: 2;
            padding: 30px;
            color: #fff;
        }
        .activism-card h2 {
            font-size: 24px;
            background: #5a6e3a;
            display: inline-block;
            padding: 5px 10px;
            color: #fff;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .activism-card p {
            font-size: 16px;
        }
        .btn {
            display: inline-block;
            background: #5a6e3a;
            color: white;
            text-decoration: none;
            padding: 10px 25px;
            border-radius: 50%;
            transition: background 0.3s;
        }
        .btn:hover {
            background: #445527;
        }
        .card-animal {
            background-image: url('https://images.unsplash.com/photo-1555685812-4b943f1cb0eb');
        }
        .card-anti-racism {
            background-image: url('https://t4.ftcdn.net/jpg/07/05/13/55/360_F_705135521_wb5HD7PtxZ7l64r3uS7ky9pS00Z8c7jr.jpg');
        }
        * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        background: #f4f4f4;
        color: #333;
    }
    .footer {
        background: #1e1e1e;
        color: #ddd;
        padding: 40px 0;
    }
    .footer-container {
        display: flex;
        justify-content: space-between;
        max-width: 1100px;
        margin: 0 auto;
        flex-wrap: wrap;
    }
    .footer-column {
        flex: 1;
        min-width: 200px;
        margin: 20px;
    }
    .footer-column h3 {
        color: #8cc63f;
        font-size: 18px;
        margin-bottom: 15px;
    }
    .footer-column p {
    font-size: 16px; /* Change this value to adjust the text size */
}

    .footer-column ul {
        list-style: none;
    }
    .footer-column ul li {
        margin-bottom: 10px;
    }
    .footer-column ul li a {
        color: #ddd;
        text-decoration: none;
        transition: color 0.3s;
    }
    .footer-column ul li a:hover {
        color: #8cc63f;
    }
    .footer-social {
        display: flex;
        gap: 15px;
        margin-top: 20px;
    }
    .footer-social a {
        color: #ddd;
        font-size: 18px;
        transition: color 0.3s;
    }
    .footer-social a:hover {
        color: #8cc63f;
    }
    
    </style>

</head>
<body>
    
    <header>
        <div class="top-bar">
            WhatsApp: +51 34 4567 4677 | 1 800 345 3457 | hello@flutedu.com
        </div>
        <nav>
            <div class="logo">ABROAD <span style="color:#d4af37; font-family: 'Dancing Script', cursive;">ACTIVISM</span></div>
            <ul>
                <li><a href="#">All Programs</a></li>
                <li><a href="#">Destinations</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <div>
            <h1>PROVIDING <span>Inspiration</span> ABROAD</h1>
            <p>Giving you the opportunity to give back, learn, and grow as you experience some of the most amazing places on earth.</p>
            <a href="#" class="cta-button">Explore Now</a>
        </div>
    </section>
    <section class="program-section">
        <h2>Working Holiday <span>Programs</span></h2>
        
        
  <p> Working Holidays around the World! In Japan, China, Germany. Try something different! </p>
 
        <div class="program-container">

                   <div class="destination-card" style="background-image: url('https://static.independent.co.uk/2023/12/06/14/iStock-646880230.jpg');">Australia</div>
            <div class="destination-card" style="background-image: url('https://media.istockphoto.com/id/899508826/photo/the-great-wall-of-china.jpg?s=612x612&w=0&k=20&c=RzyuDykCPnftDjyUiVkyia3c6jDRXzU2UrcTSnAJo48=');">Japan</div>
            <div class="destination-card" style="background-image: url('https://assets.tripsmiths.com/images/listing/527440-shutterstock-1513825088.jpg');">China</div>
            <div class="destination-card" style="background-image: url('https://images.pexels.com/photos/1119972/pexels-photo-1119972.jpeg');">Germany</div>
        </div>
    </section>
    <section class="activism-section">
        <h1>Activism</h1>
        <div class="activism-container">
            <div class="activism-card card-animal">
                <div class="activism-card-content">
                    <h2>ANIMAL RESCUE</h2>
                    <p>Pain itself is very important, it is followed by a great deal of care, but in such a way that labor and pain are avoided.</p>
                    <a href="#" class="btn">→</a>
                </div>
            </div>
            <div class="activism-card card-anti-racism">
                <div class="activism-card-content">
                    <h2>ANTI-RACISM</h2>
                    <p>Pain itself is important, it is followed by great effort, but in such a way that work and hardship are reduced.</p>
                    <a href="#" class="btn">→</a>
                </div>
            </div>
        </div>
    </section>
    <footer class="footer">
    <div class="footer-container">
        <div class="footer-column">
            <h3>MyWebsite</h3>
            <p>Providing inspiration and opportunities worldwide. Join us to explore new horizons.</p>
            <p>📞 <a href="tel:+123456789">9468444611</a></p>
        </div>
        <div class="footer-column">
            <h3>Programs</h3>
            <ul>
                <li><a href="#">Working Holiday</a></li>
                <li><a href="#">Volunteer Abroad</a></li>
                <li><a href="#">Internship Programs</a></li>
                <li><a href="#">Courses & Study Abroad</a></li>
            </ul>
        </div>
        <div class="footer-column">
            <h3>Destinations</h3>
            <ul>
                <li><a href="#">Australia</a></li>
                <li><a href="#">Japan</a></li>
                <li><a href="#">China</a></li>
                <li><a href="#">Germany</a></li>
            </ul>
        </div>
        <div class="footer-column">
            <h3>Connect</h3>
            <div class="footer-social">
                <a href="#"> Facebook</a>
                <a href="#"> Instagram</a>
                <a href="#">LinkdIn</a>
               
            </div>
        </div>
    </div>
    
</footer>

</body>

</html>

