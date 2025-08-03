<html lang="en">
    <head>
    <meta charset="UTF-8">
    <title>Shop Smart-Online Store</title>
    <style>
       body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #4a5e34;
            padding: 20px;
            text-align: center;
        }
        nav a {
            color: rgb(32, 4, 48);
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .banner {
            background-color: #1d97b6;
            text-align: center;
            padding: 20px 20px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .product {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            margin: 15px;
            padding: 15px;
            width: 200px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .footer {
            background-color: #2c3e50;
            color: white;
            text-align: left;
            padding: 1rem;
			position:relative;
			bottom:0;
			width:100%;
            margin-top: 40px;
        }
        
    </style>
    </head>
    <body>
    <header>
        <h1>Shop Smart</h1>
        <p>Online shopping destination</p>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">About us</a>
        <a href="#">Contack us</a>
        <a href="#">Shop</a>
    </nav>
    <div class="banner">
        <h2>Welcome to shop smart</h2>
        <p>Discover the best product</p>
    </div>
    <section class="products">
        <div class="product">
            <img src="D:\Roshani\wat.jpg",alt="product1">
            <h3>Smart watch</h3>
            <p>Rs 999</p>
            <button>Add to cart</button>
        </div>
        <div class="product">
            <img src="D:\Roshani\watch1.jpg",alt="product2">
            <h3>Smart watch</h3>
            <p>Rs 999</p>
            <button>Add to cart</button>
        </div>
        <div class="product">
            <img src="D:\Roshani\watch.jpg",alt="product3">
            <h3>Smart watch</h3>
            <p>Rs 999</p>
            <button>Add to cart</button>
        </div>
    </section>
    <footer class="footer">
        <p>&copy;2025 ShopSmart.All rights reserved</p>
    </footer>
</body>
</html>
