<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Webi | Compare & Choose Smart</title>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Poppins:wght@600&display=swap" rel="stylesheet" />
<style>
  :root {
    --primary-color: #004aad;
    --secondary-color: #ffffff;
    --accent-color: #0077ff;
    --text-color: #1a1a1a;
  }

  html {
    scroll-behavior: smooth;
  }

  body {
    margin: 0;
    font-family: 'Open Sans', sans-serif;
    background-color: #f4f6f8;
    color: var(--text-color);
  }

  header {
    background: linear-gradient(135deg, #004aad, #0066cc);
    color: var(--secondary-color);
    text-align: center;
    padding: 80px 20px;
    position: relative;
  }

  header::after {
    content: "";
    background: url('https://source.unsplash.com/1600x600/?technology,shopping') center/cover no-repeat;
    opacity: 0.2;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    position: absolute;
    z-index: 0;
  }

  header h1 {
    font-family: 'Poppins', sans-serif;
    font-size: 3em;
    margin: 0;
    position: relative;
    z-index: 1;
  }

  header p {
    font-size: 1.2em;
    margin-top: 10px;
    position: relative;
    z-index: 1;
  }

  nav {
    background: var(--secondary-color);
    padding: 15px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    position: sticky;
    top: 0;
    z-index: 100;
  }

  nav a {
    color: var(--primary-color);
    text-decoration: none;
    margin: 0 10px;
    font-weight: 600;
  }

  nav a:hover {
    color: var(--accent-color);
  }

  section {
    padding: 60px 20px;
    max-width: 1200px;
    margin: auto;
  }

  h2 {
    color: var(--primary-color);
    font-family: 'Poppins', sans-serif;
    margin-bottom: 20px;
  }

  ul {
    padding-left: 20px;
  }

  .features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
  }

  .features div {
    background: var(--secondary-color);
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.05);
    transition: transform 0.3s;
  }

  .features div:hover {
    transform: translateY(-5px);
  }

  .features img {
    width: 100%;
    border-radius: 8px;
    margin-bottom: 15px;
  }

  footer {
    background-color: #1a1a1a;
    color: var(--secondary-color);
    text-align: center;
    padding: 20px;
  }

  .contact a {
    color: var(--accent-color);
    text-decoration: none;
  }

  .btn {
    background-color: var(--primary-color);
    color: var(--secondary-color);
    padding: 12px 25px;
    border: none;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .btn:hover {
    background-color: #003a8c;
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

<main>
  <section id="about">
    <h2>About Webi</h2>
    <p><strong>Webi</strong> is an online comparison and research platform for:</p>
    <ul>
      <li>✔️ Physical Goods: clothing, shoes, electronics, furniture, etc.</li>
      <li>✔️ Digital Products: e-books, software, online courses, music, etc.</li>
      <li>✔️ Services: consulting, design, writing, marketing</li>
      <li>✔️ Handmade Items: jewelry, crafts, art, and more</li>
    </ul>
    <p>Webi helps users compare prices, features, and deals across online retailers.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="features">
      <div>
        <img src="https://source.unsplash.com/400x250/?comparison,shopping" alt="Product Comparison" />
        <h3>🔍 Product Comparison</h3>
        <p>Side-by-side feature and price comparisons from multiple stores.</p>
      </div>
      <div>
        <img src="https://source.unsplash.com/400x250/?analytics,price" alt="Price Tracking" />
        <h3>📈 Price Tracking</h3>
        <p>Track product prices and get alerts for the best deals.</p>
      </div>
      <div>
        <img src="https://source.unsplash.com/400x250/?guide,review" alt="Buying Guides" />
        <h3>🧠 Buying Guides</h3>
        <p>Expert tips and curated recommendations for every category.</p>
      </div>
      <div>
        <img src="https://source.unsplash.com/400x250/?feedback,review" alt="User Reviews" />
        <h3>🗣️ User Reviews</h3>
        <p>Honest reviews and ratings from real customers.</p>
      </div>
    </div>
  </section>

  <section id="benefits">
    <h2>Why Choose Webi?</h2>
    <ul>
      <li>✔️ Fast & easy product search</li>
      <li>✔️ Real-time price and deal updates</li>
      <li>✔️ Expert-reviewed comparisons</li>
      <li>✔️ Trusted by thousands of smart shoppers</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:email@123.com">email@123.com</a></p>
    <p><button class="btn">Send Us a Message</button></p>
  </section>
</main>

<footer>
  &copy; 2025 Webi. All rights reserved.
</footer>

</body>
</html>
