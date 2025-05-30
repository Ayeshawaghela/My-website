<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prisha Ladies Tailor</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Roboto&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #fffafc;
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #f6d1f5, #f0a1d2);
            color: white;
            text-align: center;
            padding: 40px 20px;
        }
        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3em;
            margin: 0;
        }
        header p {
            font-size: 1.2em;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            background-color: #f8e4f4;
            padding: 10px;
        }
        nav a {
            text-decoration: none;
            color: #555;
            font-weight: bold;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        .services, .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }
        .service-item, .gallery-item {
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            padding: 20px;
            text-align: center;
        }
        .service-item h3 {
            margin-top: 10px;
        }
        .gallery-item img {
            width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #f0a1d2;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .contact-info {
            margin: 20px 0;
        }
        .cta {
            text-align: center;
            margin: 40px 0;
        }
        .cta button {
            background-color: #f0a1d2;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 24px;
            font-size: 1em;
            cursor: pointer;
        }
        .cta button:hover {
            background-color: #e088bb;
        }
    </style>
</head>
<body>
    <header>
        <h1>Prisha Ladies Tailor</h1>
        <p>Where Tradition Meets Modern Elegance ✨</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>At <strong>Prisha Ladies Tailor</strong>, we specialize in crafting stunning traditional and western women’s wear. From perfectly fitted blouses, graceful suit salwars, and dreamy lehengas to elegant bridal wear, we bring your style vision to life. Our passion for detail and love for design ensures every stitch reflects beauty and sophistication. Whether you want timeless classics or trendy fusion looks, we are your go-to designer tailor!</p>
    </section>
    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-item">
                <h3>Custom Blouses</h3>
                <p>Designer blouses tailored to fit you perfectly, from simple to intricate embroidery.</p>
            </div>
            <div class="service-item">
                <h3>Suit Salwars &# My-website
