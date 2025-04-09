<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Batron - Authentic Electronics from China</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

<!-- Header -->
<header>
    <div class="logo">
        <h1>Batron</h1>
    </div>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="cart">
        <button id="cart-button">Cart (0)</button>
    </div>
</header>

<!-- Hero Section -->
<section class="hero">
    <div class="hero-content">
        <h2>Your Source for Authentic Electronics from China</h2>
        <p>Shop the latest gadgets and tech, imported directly from trusted manufacturers.</p>
        <a href="#products" class="cta-btn">Shop Now</a>
    </div>
</section>

<!-- Featured Products -->
<section id="products" class="featured-products">
    <h3>Featured Products</h3>
    <div class="product-list">
        <!-- Example product -->
        <div class="product-card">
            <img src="smartphone.jpg" alt="Smartphone">
            <h4>Smartphone X</h4>
            <p>$299.99</p>
            <a href="#" class="btn" onclick="addToCart('Smartphone X', 299.99)">Add to Cart</a>
            <a href="#" class="btn buy-now" onclick="buyNow('Smartphone X', 299.99)">Buy Now</a>
        </div>
        <!-- Add more products similarly -->
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="contact-section">
    <h3>Contact Us</h3>
    <form id="contact-form">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Your Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>
        
        <button type="submit">Send Message</button>
    </form>
</section>

<!-- Footer -->
<footer>
    <p>&copy; 2025 Batron Electronics | All rights reserved.</p>
</footer>

<script src="scripts.js"></script>
</body>
</html>
