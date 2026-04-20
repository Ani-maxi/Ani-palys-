<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ani Palys Bakery</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff8f5;
    }

    header {
      background-color: #f7c6c7;
      padding: 20px;
      text-align: center;
      color: #5a2a27;
    }

    nav {
      background-color: #5a2a27;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1549931319-a545dcf3bc73') no-repeat center;
      background-size: cover;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 50px;
    }

    .section {
      padding: 40px 20px;
      text-align: center;
    }

    .menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .item {
      background: white;
      margin: 15px;
      padding: 15px;
      border-radius: 10px;
      width: 200px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .item img {
      width: 100%;
      border-radius: 10px;
    }

    footer {
      background-color: #5a2a27;
      color: white;
      text-align: center;
      padding: 15px;
    }

    button {
      background-color: #f7c6c7;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #f3a6a8;
    }
  </style>
</head>
<body>

<header>
  <h1>Ani Palys</h1>
  <p>Freshly Baked Happiness Every Day</p>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#menu">Menu</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero">
  <h1>Welcome to Ani Palys</h1>
  <p>Delicious Cakes, Pastries & More</p>
  <button>Order Now</button>
</div>

<div id="about" class="section">
  <h2>About Us</h2>
  <p>At Ani Palys, we bake with love using the finest ingredients. Our recipes are homemade and crafted to bring joy in every bite.</p>
</div>

<div id="menu" class="section">
  <h2>Our Menu</h2>
  <div class="menu">
    
    <div class="item">
      <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587">
      <h3>Chocolate Cake</h3>
      <p>₹500</p>
    </div>

    <div class="item">
      <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b">
      <h3>Cupcakes</h3>
      <p>₹200</p>
    </div>

    <div class="item">
      <img src="https://images.unsplash.com/photo-1509440159596-0249088772ff">
      <h3>Bread</h3>
      <p>₹150</p>
    </div>

    <div class="item">
      <img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e">
      <h3>Cookies</h3>
      <p>₹120</p>
    </div>

  </div>
</div>

<div id="contact" class="section">
  <h2>Contact Us</h2>
  <p>Email: anipalys@email.com</p>
  <p>Phone: +91 98765 43210</p>
  <p>Location: Your City</p>
</div>

<footer>
  <p>© 2026 Ani Palys Bakery | Made with ❤️</p>
</footer>

</body>
</html>
