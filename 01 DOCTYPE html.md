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
      position: relative;
      overflow-x: hidden;
    }
    header {
      background-color: #004aad;
      color: white;
      padding: 60px 20px 80px;
      text-align: center;
      position: relative;
      overflow: visible;
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
      position: relative;
      z-index: 1;
    }
    header p {
      font-size: 1.2em;
      margin: 10px 0 20px;
      position: relative;
      z-index: 1;
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
      position: relative;
      z-index: 1;
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
      overflow: hidden;
    }
    .features div img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 6px;
      margin-bottom: 15px;
      transition: transform 0.3s ease;
    }
    .features div:hover img {
      transform: scale(1.05);
    }
    #benefits {
      position: relative;
      padding-left: 40px;
      padding-right: 40px;
    }
    #benefits::after {
      content: '';
      position: absolute;
      top: 20px;
      left: 0;
      width: 6px;
      height: 100%;
      background: linear-gradient(180deg, #004aad, #87a8ff);
      border-radius: 3px;
      opacity: 0.8;
      z-index: 0;
    }
    #benefits ul {
      position: relative;
      z-index: 1;
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
      position: relative;
      z-index: 1;
    }
    .contact a {
      color: #004aad;
      text-decoration: none;
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
      <li><strong>Physical Goods</strong>: Clothing, electronics, furniture, etc.</li>
      <li><strong>Digital Products</strong>: E-books, software, courses</li>
      <li><strong>Services</strong>: Consulting, design, marketing</li>
      <li><strong>Handmade Items</strong>: Jewelry, crafts, art</li>
    </ul>
    <p>Webi helps users compare prices, features, and deals across online retailers.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="features">
      <div>
        <img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=400&q=80" alt="Product Comparison" />
        <h3>🔍 Product Comparison</h3>
        <p>
          Compare features and prices across stores.<br />
          <a href="https://www.google.com/search?q=compare+products" target="_blank">Search Products on Google</a>
        </p>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=400&q=80" alt="Price Tracking" />
        <h3>📈 Price Tracking</h3>
        <p>
          Get alerts for deals on:<br />
          <a href="https://www.amazon.in" target="_blank">Amazon</a>,
          <a href="https://www.flipkart.com" target="_blank">Flipkart</a>,
          <a href="https://www.91mobiles.com" target="_blank">91Mobiles</a>,
          <a href="https://www.bestreviewsonline.in/new-deals" target="_blank">BestReviewsOnline</a>
        </p>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=400&q=80" alt="Buying Guides" />
        <h3>🧠 Buying Guides</h3>
        <p>
          Expert tips for smarter shopping.<br />
          <a href="https://webi1008.github.io/Webi/" target="_blank">View Webi Guides</a>
        </p>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1551836022-d5d88e9218df?auto=format&fit=crop&w=400&q=80" alt="User Reviews" />
        <h3>🗣️ User Reviews</h3>
        <p>
          “I had a fantastic experience with Webi! Their team was incredibly responsive and knowledgeable. I appreciated their transparency and efficiency. Highly recommend!” – Jon Bein<br /><br />
          <strong>Tips for Good Reviews:</strong><br />
          ✅ Be specific<br />
          ✅ Be excited<br />
          ✅ Recommend clearly<br />
          ✅ Keep it clear<br />
          ✅ Focus on positives
        </p>
      </div>
    </div>
  </section>

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
