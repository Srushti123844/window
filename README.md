<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Bites - Food Delivery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #ff6f00;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }
        .item {
            background-color: white;
            margin: 15px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            width: 250px;
            text-align: center;
            overflow: hidden;
        }
        .item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .item h3 {
            margin: 10px 0;
        }
        .item p {
            color: #555;
            padding: 0 10px 10px;
        }
        .order-btn {
            background-color: #ff6f00;
            color: white;
            padding: 10px;
            text-decoration: none;
            display: inline-block;
            margin-bottom: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>Delicious Bites</h1>
    <p>Fast, Fresh & Delivered to Your Doorstep</p>
</header>

<section class="menu">
    <div class="item">
        <img src="https://source.unsplash.com/250x180/?pizza" alt="Pizza">
        <h3>Cheesy Pizza</h3>
        <p>Loaded with mozzarella and toppings of your choice.</p>
        <a href="#" class="order-btn">Order Now</a>
    </div>

    <div class="item">
        <img src="https://source.unsplash.com/250x180/?burger" alt="Burger">
        <h3>Classic Burger</h3>
        <p>Juicy grilled beef patty with fresh lettuce and tomato.</p>
        <a href="#" class="order-btn">Order Now</a>
    </div>

    <div class="item">
        <img src="https://source.unsplash.com/250x180/?sushi" alt="Sushi">
        <h3>Fresh Sushi</h3>
        <p>Assorted sushi rolls made fresh to order.</p>
        <a href="#" class="order-btn">Order Now</a>
    </div>

    <div class="item">
        <img src="https://source.unsplash.com/250x180/?pasta" alt="Pasta">
        <h3>Italian Pasta</h3>
        <p>Classic Alfredo pasta with creamy white sauce.</p>
        <a href="#" class="order-btn">Order Now</a>
    </div>
</section>

</body>
</html>
