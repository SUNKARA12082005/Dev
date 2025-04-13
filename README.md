<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AgriMarket Hub</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #2e7d32;
      padding: 20px;
      color: white;
      text-align: center;
    }
    nav {
      background: #388e3c;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1582515073490-39981397c445') center/cover;
      height: 250px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      text-shadow: 2px 2px 5px #000;
    }
    .section {
      padding: 30px;
    }
    .section h2 {
      color: #2e7d32;
      margin-bottom: 15px;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .product {
      background: white;
      border: 1px solid #ccc;
      border-radius: 10px;
      width: 200px;
      padding: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .product img {
      width: 100%;
      border-radius: 8px;
      height: 150px;
      object-fit: cover;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      margin-bottom: 15px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    footer {
      background: #1b5e20;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>AgriMarket Hub</h1>
    <p>Directly Connecting Farmers and Buyers</p>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    Farm Fresh. Fair Prices.
  </div>

  <section class="section" id="products">
    <h2>Available Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1603048297423-2b70f51ee6d3" alt="Tomatoes">
        <h3>Fresh Tomatoes</h3>
        <p>Rs. 40/kg</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1576402187878-974f70e7d09e" alt="Carrots">
        <h3>Carrots</h3>
        <p>Rs. 30/kg</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1615485737454-f8b41ed8c6ab" alt="Onions">
        <h3>Onions</h3>
        <p>Rs. 20/kg</p>
      </div>
    </div>
  </section>

  <section class="section" id="about">
    <h2>About Us</h2>
    <p>AgriMarket Hub is a digital platform created to help farmers sell their produce directly to consumers, bypassing middlemen and ensuring better profits and quality for all.</p>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Email Address" required>
      <textarea rows="5" placeholder="Your Message"></textarea>
      <input type="submit" value="Send Message">
    </form>
  </section>

  <footer>
    &copy; 2025 AgriMarket Hub. All rights reserved.
  </footer>

</body>
</html>
