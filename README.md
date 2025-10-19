# demo

<<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My T-Shirt Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    header {
      background: #222;
      color: #fff;
      padding: 15px;
      text-align: center;
    }
    .product-container {
      max-width: 800px;
      margin: 40px auto;
      background: white;
      padding: 20px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    .product-container img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }
    .product-title {
      font-size: 24px;
      margin: 15px 0;
    }
    .price {
      font-size: 20px;
      color: #28a745;
      margin-bottom: 20px;
    }
    .btn {
      background: #ff4d4d;
      color: white;
      border: none;
      padding: 12px 20px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 8px;
      transition: 0.3s;
    }
    .btn:hover {
      background: #e60000;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #222;
      color: white;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>My T-Shirt Store</h1>
  </header>

  <div class="product-container">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/89/T-Shirt_White.png" alt="T-Shirt">
    <h2 class="product-title">Classic White T-Shirt</h2>
    <p class="price">₹300</p>
    <button class="btn">Add to Cart 🛒</button>
  </div>

  <footer>
    © 2025 My T-Shirt Store | All Rights Reserved
  </footer>

</body>
</html>
