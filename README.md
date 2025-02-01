# the-invert-company
/* Reset some default browser styles */
body, h1, h2, h3, p, ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

/* General styles */
body {
    font-family: Arial, sans-serif;
    color: #333;
    background-color: #fff;
    line-height: 1.6;
}

/* Header styles */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #000;
    color: #fff;
}

header .logo h1 {
    font-size: 24px;
}

header nav ul {
    display: flex;
    gap: 15px;
}

header nav a {
    color: #fff;
    text-decoration: none;
    font-size: 16px;
}

/* Hero section styles */
.hero {
    position: relative;
    text-align: center;
    color: #fff;
}

.hero img {
    width: 100%;
    height: auto;
    opacity: 0.8;
}

.hero-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.hero-text h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #000;
    color: #fff;
    text-decoration: none;
    font-size: 16px;
    border-radius: 5px;
}

.btn:hover {
    background-color: #333;
}

/* Products section styles */
.products {
    padding: 40px 20px;
    text-align: center;
}

.products h2 {
    font-size: 28px;
    margin-bottom: 20px;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.product {
    border: 1px solid #ddd;
    padding: 20px;
    width: 200px;
}

.product img {
    width: 100%;
    height: auto;
    margin-bottom: 10px;
}

.product h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

.product p {
    font-size: 16px;
    margin-bottom: 10px;
}

/* Footer styles */
footer {
    background-color: #f8f8f8;
    padding: 20px;
    text-align: center;
}

footer .newsletter {
    margin-bottom: 20px;
}

footer input[type="email"] {
    padding:32
