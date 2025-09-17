# YOURWEBSOFFICIAL
A Website For Websites
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YOURWEBSOFFICIAL - Affordable Websites Since 2007</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f8f8f8ff;
      color: #333333de;
    }
    header {
      background-color: #fff;
      border-bottom: 2px solid #ddd;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
    }
    header h1 {
      color: #444;
      margin: 0;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #444;
      font-weight: bold;
    }
    nav a:hover {
      color: #000;
    }
    section {
      padding: 60px 40px;
      max-width: 1100px;
      margin: auto;
    }
    .about {
      background: #fff;
      border-radius: 8px;
      padding: 30px;
      text-align: center;
    }
    .about h2 { margin-bottom: 20px; }
    .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .portfolio-item {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      border: 1px solid #ddd;
    }
    .portfolio-item img {
      max-width: 100%;
      border-radius: 5px;
    }
    .prices {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .price-box {
      background: #fff;
      padding: 30px;
      border-radius: 8px;
      width: 300px;
      text-align: center;
      border: 1px solid #ddd;
    }
    .price-box h3 { margin: 0 0 15px; }
    .price {
      font-size: 24px;
      margin: 15px 0;
      color: #222;
    }
    footer {
      background: #f0f0f0;
      padding: 20px;
      text-align: center;
      font-size: 14px;
      color: #555;
      border-top: 2px solid #ddd;
    }
  </style>
</head>
<body>
  <header>
    <h1>YOURWEBS</h1>
    <nav>
      <a href="#about">About us</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#prices">Prices</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>
      At <strong>YOURWEBS</strong>, we’ve been crafting affordable, reliable, and modern websites since 2007.  
      What started as a small passion project has grown into a trusted name for businesses and individuals  
      looking to build their online presence without breaking the bank.  
      Our mission is simple: <em>professional websites that anyone can afford.</em>
    </p>
  </section>

  <section id="portfolio">
    <h2 style="text-align:center;">Portfolio</h2>
    <div class="portfolio">
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/300x200" alt="Basic Website Example">
        <p>Basic Package Example</p>
      </div>
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/300x200" alt="Standard Website Example">
        <p>Standard Package Example</p>
      </div>
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/300x200" alt="Premium Website Example">
        <p>Premium Package Example</p>
      </div>
    </div>
  </section>

  <section id="prices">
    <h2 style="text-align:center;">Our Prices</h2>
    <div class="prices">
      <div class="price-box">
        <h3>Basic</h3>
        <p class="price">$199.99</p>
        <p>Perfect for small personal sites or startups.</p>
      </div>
      <div class="price-box">
        <h3>Standard</h3>
        <p class="price">$299.99</p>
        <p>Ideal for small businesses needing a strong online presence.</p>
      </div>
      <div class="price-box">
        <h3>Premium</h3>
        <p class="price">$399.99</p>
        <p>Best for growing businesses looking for advanced features and design.</p>
      </div>
    </div>
  </section>

  <footer id="contact">
    <p>📞 343-549-8885 | ✉️ yourwebs2007@gmail.com</p>
    <p>© 2025 YOURWEBS. All rights reserved.</p>
  </footer>
</body>
</html>
