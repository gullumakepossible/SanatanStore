<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Garun Saini's Devotion Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
 <!-- Logo -->
    <header>
        <img src="https://raw.githubusercontent.com/your-username/repository/main/images/logo.png" 
             alt="Garun Saini Logo" class="logo">
        <h1>Welcome to Garun Saini's Devotion Store</h1>
        <p>Your one-stop shop for Hindu spiritual products</p>
    </header>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <a href="#">Home</a>
        <a href="#">Categories</a>
        <a href="#">Spiritual Guide</a>
        <a href="#">Contact</a>
        <a href="https://www.instagram.com/dwaj_1" target="_blank">Instagram</a>
    </nav>
   <!-- Hero Banner -->
    <section class="hero">
        <h2>Discover the Best Hindu Spiritual Books & Items</h2>
        <p>Explore the wisdom of the Vedas, Upanishads, and Bhagavad Gita.</p>
    </section>
    <!-- Product Section -->
    <section class="products">
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/71s3HcOBgHL.jpg" alt="Bhagavad Gita">
            <h3>Bhagavad Gita</h3>
            <p>The most profound Hindu scripture explaining Dharma & Karma.</p>
            <a href="https://www.amazon.in/dp/B08Z3TT3M3" target="_blank" class="buy-btn">Buy on Amazon</a>
        </div>
      <div class="product">
            <img src="https://m.media-amazon.com/images/I/91PYuAfUbHL.jpg" alt="Vedas Book Set">
            <h3>Vedas (Complete Set)</h3>
            <p>Unlock the cosmic knowledge of Rigveda, Yajurveda, Samaveda & Atharvaveda.</p>
            <a href="https://www.amazon.in/dp/B09V7L2V8B" target="_blank" class="buy-btn">Buy on Amazon</a>
        </div>
       <div class="product">
            <img src="https://m.media-amazon.com/images/I/71qX13EIbdL.jpg" alt="Rudraksha Mala">
            <h3>Rudraksha Mala</h3>
            <p>Powerful spiritual beads for meditation and divine energy.</p>
            <a href="https://www.amazon.in/dp/B07GDBRDKK" target="_blank" class="buy-btn">Buy on Amazon</a>
        </div>
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/71Tt7EakixL.jpg" alt="Saffron Kurta">
            <h3>Saffron Kurta</h3>
            <p>Traditional saffron clothing worn by Hindu saints and devotees.</p>
            <a href="https://www.amazon.in/dp/B09LHZ5PZ5" target="_blank" class="buy-btn">Buy on Amazon</a>
        </div>
    </section>
    <!-- Footer -->
    <footer class="footer">
        <p>© 2025 Garun Saini. All Rights Reserved. | Follow me on <a href="https://www.instagram.com/dwaj_1" target="_blank">Instagram</a></p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    text-align: center;
    margin: 0;
    padding: 0;
}
header {
    background-color: #ff6600;
    color: white;
    padding: 20px;
}
.logo {
    width: 120px;
    display: block;
    margin: 0 auto 10px;
}
.navbar {
    background-color: #222;
    padding: 10px;
}
.navbar a {
    color: white;
    text-decoration: none;
    margin: 15px;
    font-weight: bold;
}
.hero {
    background-color: #ffcc00;
    padding: 20px;
}

.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px;
}

.product {
    background: white;
    margin: 15px;
    padding: 15px;
    width: 250px;
    border-radius: 10px;
    box-shadow: 2px 2px 10px gray;
}

.product img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}
.buy-btn {
    display: inline-block;
    background-color: #ff6600;
    color: white;
    padding: 10px;
    text-decoration: none;
    margin-top: 10px;
    border-radius: 5px;
}
.footer {
    background: #222;
    color: white;
    padding: 15px;
    font-size: 14px;
}
