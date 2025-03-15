<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Garun Saini - Hindu Devotion Store</title>
    <style>
        body { 
            font-family: 'Arial', sans-serif; 
            margin: 0; 
            padding: 0; 
            background: linear-gradient(to right, #ffecd2, #fcb69f);
            text-align: center;
        }
        /* Navigation Bar */
        .navbar {
            background: linear-gradient(to right, #ff6a00, #ee0979);
            padding: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 18px;
            font-weight: bold;
            transition: all 0.3s;
        }
        .navbar a:hover {
            background-color: rgba(255, 255, 255, 0.2);
            border-radius: 5px;
        }
        /* Logo */
        .logo {
            width: 180px;
            margin: 20px auto;
            display: block;
        }
        /* Hero Banner */
        .hero {
            background: url('https://source.unsplash.com/1600x600/?hindu,temple') no-repeat center;
            background-size: cover;
            color: white;
            padding: 80px 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        .hero h1 {
            font-size: 45px;
            margin: 0;
            font-weight: bold;
        }
        .hero p {
            font-size: 22px;
            font-weight: bold;
        }
        /* Product Section */
        .container {
            width: 90%;
            margin: auto;
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .product {
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            width: 280px;
            text-align: center;
            transition: transform 0.3s ease-in-out;
        }
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
        .product h3 {
            margin: 10px 0;
            color: #ff6a00;
            font-size: 20px;
            font-weight: bold;
        }
        .product p {
            color: #555;
            font-size: 16px;
        }
        .buy-btn {
            display: inline-block;
            margin-top: 10px;
            padding: 12px 18px;
            background: linear-gradient(to right, #ff6a00, #ee0979);
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .buy-btn:hover {
            background: linear-gradient(to right, #ee0979, #ff6a00);
        }
        /* Spiritual Guide Section */
        .spiritual-guide {
            margin: 40px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
            width: 80%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        .spiritual-guide h2 {
            color: #ff6a00;
            font-size: 24px;
            margin-bottom: 10px;
        }
        .spiritual-guide p {
            font-size: 18px;
            color: #333;
        }
        /* Footer */
        .footer {
            background: #222;
            color: white;
            padding: 15px;
            margin-top: 20px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Logo -->
    <img src="https://i.imgur.com/your-logo-url.png" alt="Garun Saini Logo" class="logo">

    <!-- Navigation Bar -->
    <div class="navbar">
        <a href="#">Home</a>
        <a href="#">Categories</a>
        <a href="#">Spiritual Guide</a>
        <a href="#">Contact</a>
    </div>

    <!-- Hero Banner -->
    <div class="hero">
        <h1>Welcome to Garun Saini's Devotion Store</h1>
        <p>Your one-stop shop for Hindu spiritual products</p>
    </div>

    <!-- Product Container -->
    <div class="container">
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/71pS-wnl+XL.jpg" alt="Bhagavad Gita">
            <h3>Bhagavad Gita</h3>
            <p>Spiritual wisdom from Lord Krishna.</p>
            <a href="https://www.amazon.in/dp/B08K4Z79RZ" class="buy-btn" target="_blank">Buy Now</a>
        </div>

        <div class="product">
            <img src="https://m.media-amazon.com/images/I/51RrIr2nUsL._SL1024_.jpg" alt="Upanishads">
            <h3>The Upanishads</h3>
            <p>Ancient Hindu philosophy on the soul and universe.</p>
            <a href="https://www.amazon.in/dp/0140441638" class="buy-btn" target="_blank">Buy Now</a>
        </div>

        <div class="product">
            <img src="https://m.media-amazon.com/images/I/61ESg7qGq8L.jpg" alt="Yoga Vasistha">
            <h3>Yoga Vasistha</h3>
            <p>A deep dive into reality and consciousness.</p>
            <a href="https://www.amazon.in/dp/B08XLPB1ZT" class="buy-btn" target="_blank">Buy Now</a>
        </div>
    </div>

    <!-- Spiritual Guide Section -->
    <div class="spiritual-guide">
        <h2>Guide to Hindu Darshans</h2>
        <p>To open your mind to the universe and God, start with: </p>
        <ul>
            <li>📖 Read **Bhagavad Gita** for understanding Dharma and Karma.</li>
            <li>🧘‍♂️ Study **Yoga Vasistha** for deep metaphysical insights.</li>
            <li>🌌 Explore the **Upanishads** for the secrets of Brahman.</li>
            <li>🔥 Understand **Vedanta** to realize the illusion of the world (Maya).</li>
        </ul>
        <p>Follow this path, and you will **unlock the knowledge of the multiverse.**</p>
    </div>

    <!-- Footer -->
    <div class="footer">
        <p>Follow me on Instagram: <a href="https://instagram.com/dwaj_1" target="_blank" style="color: #ff6a00;">@dwaj_1</a></p>
        <p>&copy; 2025 Garun Saini. All rights reserved.</p>
    </div>

</body>
</html>
