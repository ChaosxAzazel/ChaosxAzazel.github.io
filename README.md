<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Flashy Website</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #121212;
            color: #fff;
            overflow-x: hidden;
        }
        header {
            background: linear-gradient(90deg, #ff0055, #ff5500);
            padding: 20px;
            text-align: center;
            font-size: 2rem;
            font-weight: bold;
            animation: glow 1.5s ease-in-out infinite alternate;
        }
        @keyframes glow {
            from {
                text-shadow: 0 0 10px #ff0055, 0 0 20px #ff5500, 0 0 30px #ff5500;
            }
            to {
                text-shadow: 0 0 20px #ff0055, 0 0 30px #ff5500, 0 0 40px #ff5500;
            }
        }
        .container {
            padding: 50px;
            text-align: center;
        }
        .product-card {
            background: #1f1f1f;
            border-radius: 10px;
            padding: 20px;
            margin: 20px;
            display: inline-block;
            width: 300px;
            transition: transform 0.3s ease;
        }
        .product-card:hover {
            transform: scale(1.1);
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
        }
        .product-card h3 {
            margin: 20px 0;
        }
        .product-card p {
            font-size: 1.1rem;
            color: #bbb;
        }
        .buy-button {
            background: #ff5500;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        .buy-button:hover {
            background: #ff0055;
        }
    </style>
</head>
<body>

<header>
    Welcome to Your Flashy Website
</header>

<div class="container">
    <div class="product-card">
        <img src="your-product-image.jpg" alt="Product Image">
        <h3>Product Name</h3>
        <p>Product description goes here. Highlight features and benefits.</p>
        <button class="buy-button">Buy Now</button>
    </div>
    <div class="product-card">
        <img src="your-product-image2.jpg" alt="Product Image">
        <h3>Another Product</h3>
        <p>Another product description with key points and details.</p>
        <button class="buy-button">Buy Now</button>
    </div>
</div>

</body>
</html>
