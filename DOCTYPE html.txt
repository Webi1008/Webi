<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Webi | Compare & Choose Smart</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Poppins:wght@600&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background-color: #f4f6f8;
      color: #1a1a1a;
    }
    header {
      background-color: #004aad;
      color: white;
      padding: 60px 20px 80px;
      text-align: center;
      position: relative;
    }
    header::before {
      content: '';
      position: absolute;
      top: -80px;
      left: -100px;
      width: 300px;
      height: 300px;
      background: #0056d2;
      border-radius: 60% 40% 70% 30% / 30% 60% 40% 70%;
      opacity: 0.4;
      filter: blur(70px);
      z-index: 0;
    }
    header h1 {
      font-family: 'Poppins', sans-serif;
      font-size: 2.8em;
      margin: 0;
      z-index: 1;
      position: relative;
    }
    header p {
      font-size: 1.2em;
      margin: 10px 0 20px;
      z-index: 1;
      position: relative;
    }
    nav {
      background: #ffffff;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      color: #004aad;
      text-decoration: none;
      margin: 0 10px;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav a:hover {
      text-decoration: underline;
      color: #002d70;
    }
    .btn {
      background-color: #004aad;
      color: white;
      padding: 10px 20px;
      border: none;
      font-weight: bold;
      cursor: pointer;
      border-radius: 4px;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    #services::before {
      content: '';
      position: absolute;
      top: -60px;
      right: -120px;
      width: 350px;
      height: 350px;
      background: #c2dbff;
      border-radius: 60% 40% 70% 30% / 30% 60% 40% 70%;
      filter: blur(70px);
      z-index: -1;
    }
    h2 {
      color: #004aad;
      font-family: 'Poppins', sans-serif;
      margin-bottom: 20px;
    }
    ul {
      padding-left: 20px;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .features div {
      background: #ffffff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
      text-align: center;
      position: relative;
    }
    .features div img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 6px;
      margin-bottom: 15px;
      transition: transform 0.3s ease;
      cursor: pointer;
    }
    .features div:hover img {
      transform: scale(1.05);
    }
    #benefits ul {
      list-style: none;
      padding-left: 0;
    }
    #benefits ul li {
      padding-left: 30px;
      margin-bottom: 15px;
      position: relative;
      font-weight: 600;
      color: #004aad;
    }
    #benefits ul li::before {
      content: '✔️';
      position: absolute;
      left: 0;
      top: 0;
      font-size: 1.2em;
    }
    footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .modal {
      display: none;
      position: fixed;
      z-index: 999;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0,0,0,0.5);
    }
    .modal-content {
      background: white;
      margin: 10% auto;
      padding: 20px;
      width: 90%;
      max-width: 400px;
      border-radius: 10px;
      text-align: center;
    }
    .modal-content a {
      display: block;
      margin: 10px 0;
      color: #004aad;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <nav>
    <div><strong>Webi</strong></div>
    <div>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#benefits">Why Us</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <header>
    <h1>Compare & Choose Smart</h1>
    <p>Your one-stop platform to research and compare everything</p>
  </header>

  <section id="about">
    <h2>About Webi</h2>
    <p><strong>Webi</strong> is an online comparison and research platform for:</p>
    <ul>
      <li>Physical Goods: Clothing, electronics, books, etc.</li>
      <li>Digital Products: E-books, software, courses, etc.</li>
      <li>Services: Consulting, writing, marketing</li>
      <li>Handmade Items: Jewelry, crafts, art</li>
    </ul>
    <p>Compare prices, features, and deals across online retailers.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="features">
      <div>
        <a href="https://www.google.com/search?q=product+comparison" target="_blank">
          <img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=400&q=80" alt="Product Comparison" />
        </a>
        <h3>🔍 Product Comparison</h3>
        <p>Compare products instantly via Google Search.</p>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=400&q=80" alt="Price Tracking" onclick="document.getElementById('priceModal').style.display='block'" />
        <h3>📈 Price Tracking</h3>
        <p>Track deals across Amazon, Flipkart, and more.</p>
      </div>
      <div>
        <a href="https://webi1008.github.io/Webi/" target="_blank">
          <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=400&q=80" alt="Buying Guides" />
        </a>
        <h3>🧠 Buying Guides</h3>
        <p>Expert advice for smart shopping decisions.</p>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1551836022-d5d88e9218df?auto=format&fit=crop&w=400&q=80" alt="User Reviews" />
        <h3>🗣️ User Reviews</h3>
        <p>
          “I had a fantastic experience working with Webi! Their team was incredibly responsive and knowledgeable. I especially appreciated their transparency and efficiency. Highly recommended!” — Jon Bein
        </p>
      </div>
    </div>
  </section>

  <div id="priceModal" class="modal" onclick="this.style.display='none'">
    <div class="modal-content" onclick="event.stopPropagation()">
      <h3>Choose a Site</h3>
      <a href="https://www.amazon.in/" target="_blank">Amazon</a>
      <a href="https://www.flipkart.com/" target="_blank">Flipkart</a>
      <a href="https://www.91mobiles.com/" target="_blank">99Mobiles</a>
      <a href="https://www.bestreviewsonline.in/new-deals" target="_blank">BestReviewsOnline Deals</a>
    </div>
  </div>

  <section id="benefits">
    <h2>Why Choose Webi?</h2>
    <ul>
      <li>Fast & easy product search</li>
      <li>Real-time price and deal updates</li>
      <li>Expert-reviewed comparisons</li>
      <li>Trusted by thousands of smart shoppers</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:email@123.com">email@123.com</a></p>
  </section>

  <footer>
    &copy; 2025 Webi. All rights reserved.
  </footer>
</body>
</html>
