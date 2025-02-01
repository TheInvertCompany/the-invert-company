# the-invert-company
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Invert Company</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>The Invert Company</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <img src="images/hero-image.jpg" alt="Hero Image">
            <div class="hero-text">
                <h2>Art Through Apparel</h2>
                <a href="#" class="btn">Shop Now</a>
            </div>
        </section>
        <section class="products">
            <h2>Featured Products</h2>
            <div class="product-grid">
                <!-- Repeat this block for each product -->
                <div class="product">
                    <img src="images/product1.jpg" alt="Product 1">
                    <h3>Product Name</h3>
                    <p>$Price</p>
                    <a href="#" class="btn">Add to Cart</a>
                </div>
                <!-- End of product block -->
            </div>
        </section>
    </main>
    <footer>
        <div class="newsletter">
            <h2>Subscribe to our Newsletter</h2>
            <form action="#" method="post">
                <input type="email" name="email" placeholder="Enter your email" required>
                <button type="submit" class="btn">Subscribe</button>
            </form>
        </div>
        <div class="social-media">
            <a href="https://www.facebook.com/theinvertcompany" target="_blank">Facebook</a>
            <a href="https://www.instagram.com/theinvertcompany__" target="_blank">Instagram</a>
        </div>
        <p>&copy; 2025 The Invert Company. All rights reserved.</p>
    </footer>
</body>
</html>
