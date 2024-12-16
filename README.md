<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Organic Store</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f9f9f9;
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            text-align: center;
        }
        header {
            background: #68b684;
            padding: 20px;
            border-radius: 20px;
        }
        header h1 {
            color: white;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .product {
            background: white;
            padding: 15px;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 20px;
        }
        .product h2 {
            margin: 10px 0;
            color: #333;
        }
        .product p {
            color: #555;
        }
        .btn {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #68b684;
            color: white;
            text-decoration: none;
            border-radius: 20px;
            transition: background 0.3s;
        }
        .btn:hover {
            background: #4f9265;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Welcome to Organic Store</h1>
        </header>

        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Organic Vegetables">
                <h2>Fresh Organic Vegetables</h2>
                <p>Handpicked farm-fresh veggies for your health.</p>
                <a href="#" class="btn">Shop Now</a>
            </div>

            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Natural Ghee">
                <h2>Natural Ghee</h2>
                <p>Pure and healthy ghee for a balanced diet.</p>
                <a href="#" class="btn">Shop Now</a>
            </div>

            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Cold Pressed Oils">
                <h2>Cold Pressed Oils</h2>
                <p>Healthy oils for a flavorful experience.</p>
                <a href="#" class="btn">Shop Now</a>
            </div>
        </div>
    </div>
</body>
</html>
