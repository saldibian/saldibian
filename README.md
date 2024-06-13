<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Drop Stitch Hot Tubs</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="logo">
                <img src="logo.png" alt="Drop Stitch Hot Tubs">
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Main Banner -->
    <section id="home" class="main-banner">
        <div class="container">
            <h1>Experience Year-Round Relaxation</h1>
            <p>Heats up to 40°C, Fits 4-6 People, Soothing Air Jet System</p>
            <a href="#products" class="btn">Explore Our Hot Tubs</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section">
        <div class="container">
            <h2>About Drop Stitch Hot Tubs</h2>
            <p>Brief introduction to the company and its mission.</p>
        </div>
    </section>

    <!-- Featured Product Section -->
    <section id="products" class="featured-product">
        <div class="container">
            <h2>Featured Product</h2>
            <div class="product-details">
                <img src="wave-california-hot-tub.jpg" alt="Wave California Drop Stitch Hot Tub">
                <div class="details">
                    <h3>Wave California Drop Stitch Hot Tub</h3>
                    <p>Durable, easy setup, fits up to 4-6 people. Perfect for year-round use.</p>
                    <p><strong>$700 ALL IN for White Drop Stitch Tub</strong></p>
                    <a href="#purchase" class="btn">Buy Now</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <div class="container">
            <h2>Contact Us</h2>
            <div class="contact-form">
                <form action="submit_form.php" method="post">
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <input type="tel" name="phone" placeholder="Your Phone Number" required>
                    <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-info">
                <p>Accepted Payment Methods: Cash, Visa/Mastercard/American Express, Etransfer</p>
                <p>Email: <a href="mailto:lay-z-spa@mail.com">lay-z-spa@mail.com</a></p>
                <p>Call: <a href="tel:+18558566863">1-855-856-6863</a> / Text: <a href="sms:+12269984300">226-998-4300</a></p>
            </div>
        </div>
    </footer>

</body>
</html>
/* Reset and Basic Styles */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f0f0f0;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

/* Header Styles */
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

header .logo {
    float: left;
}

header nav {
    float: right;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline;
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Main Banner Styles */
.main-banner {
    background-image: url('banner-image.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.main-banner h1 {
    font-size: 3em;
    margin-bottom: 20px;
}

.main-banner p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

.main-banner .btn {
    display: inline-block;
    background-color: #ff9900;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.main-banner .btn:hover {
    background-color: #e68a00;
}

/* About Section Styles */
.about-section {
    padding: 80px 0;
    background-color: #fff;
}

.about-section h2 {
    font-size: 2.5em;
    margin-bottom: 30px;
}

.about-section p {
    font-size: 1.1em;
    line-height: 1.8;
}

/* Featured Product Section Styles */
.featured-product {
    padding: 100px 0;
    background-color: #f0f0f0;
}

.featured-product .product-details {
    display: flex;
    align-items: center;
}

.featured-product img {
    max-width: 50%;
    margin-right: 50px;
}

.featured-product .details {
    flex: 1;
}

.featured-product h3 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.featured-product p {
    font-size: 1.1em;
    margin-bottom: 20px;
}

.featured-product .btn {
    background-color: #ff9900;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.featured-product .btn:hover {
    background-color: #e68a00;
}

/* Contact Section Styles */
.contact-section {
    padding: 80px 0;
    background-color: #fff;
}

.contact-section h2 {
    font-size: 2.5em;
    margin-bottom: 30px;
}

.contact-form {
    max-width: 600px;
    margin: 0 auto;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact-form .btn {
    background-color: #ff9900;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.contact-form .btn:hover {
    background-color: #e68a00;
}

/* Footer Styles */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

footer p {
    margin-bottom: 10px;
}

footer a {
    color: #fff;
    text-decoration: none;
}
