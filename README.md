<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Armenian Speed Dating | Urartu Coffee</title>
    <style>
        /* General Styles */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #FDFD47; /* Bright Yellow from flyer */
            color: #D32F2F; /* Deep Red from flyer */
        }

        /* Navigation */
        nav {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 15px 0;
            position: sticky;
            top: 0;
            text-align: center;
            border-bottom: 2px solid #D32F2F;
            backdrop-filter: blur(5px);
        }

        nav a {
            text-decoration: none;
            color: #D32F2F;
            font-weight: bold;
            margin: 0 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 60px 20px;
            max-width: 800px;
            margin: 0 auto;
        }

        .welcome-text {
            font-size: 1.2rem;
            letter-spacing: 2px;
            margin-bottom: 10px;
        }

        h1 {
            font-size: 3.5rem;
            margin: 0;
            line-height: 1;
            text-transform: uppercase;
        }

        .sub-headline {
            font-size: 1.5rem;
            margin-top: 10px;
            font-style: italic;
        }

        /* Graphic Elements (Simplified CSS Crowns/Hearts) */
        .graphic-container {
            margin: 40px 0;
            font-size: 5rem;
        }

        /* Content Sections */
        section {
            padding: 60px 20px;
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }

        .cta-button {
            background-color: #D32F2F;
            color: #FDFD47;
            padding: 20px 40px;
            font-size: 1.5rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            font-weight: bold;
            transition: transform 0.2s;
        }

        .cta-button:hover {
            transform: scale(1.05);
        }

        .faq-item {
            text-align: left;
            margin-bottom: 30px;
            border-bottom: 1px dashed #D32F2F;
            padding-bottom: 10px;
        }

        footer {
            padding: 40px;
            text-align: center;
            font-size: 0.9rem;
        }

        /* Mobile Optimization */
        @media (max-width: 600px) {
            h1 { font-size: 2.5rem; }
            nav a { margin: 0 10px; font-size: 0.8rem; }
        }
    </style>
</head>
<body>

    <nav>
        <a href="#home">Home</a>
        <a href="#faq">FAQ</a>
        <a href="#signup">Sign Up</a>
    </nav>

    <div id="home" class="hero">
        <p class="welcome-text">WELCOME TO URARTU COFFEE'S</p>
        <h1>ARMENIAN<br>SPEED DATING</h1>
        <div class="graphic-container">
            👑 ❤️ 👑
        </div>
        <p class="sub-headline">Bringing together Armenians who are ready to find their person.</p>
        <p>WE HOPE YOU FIND YOUR MATCH</p>
    </div>

    <hr style="border: 0; border-top: 2px solid #D32F2F; max-width: 100px;">

    <section id="faq">
        <h2>Frequently Asked Questions</h2>
        
        <div class="faq-item">
            <h3>Who can join?</h3>
            <p
            
