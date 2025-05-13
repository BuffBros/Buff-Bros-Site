<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Buff Bros | Car Detailing</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #111;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header img {
      max-width: 200px;
      margin-bottom: 1rem;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      background: #222;
      text-align: center;
      padding: 0.75rem;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    .section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .gallery img {
      width: 300px;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.2);
    }
    .price-list {
      background: #f0f0f0;
      padding: 1.5rem;
      border-radius: 8px;
    }
    .price-list h3 {
      margin-top: 1rem;
      color: #222;
    }
    .price-list ul {
      list-style: none;
      padding-left: 1rem;
    }
    .price-list li {
      margin-bottom: 0.5rem;
    }
    .contact {
      background: #111;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    .contact p {
      margin: 0.5rem 0;
    }
    footer {
      background: #222;
      color: #bbb;
      text-align: center;
      padding: 1rem;
    }
    a {
      color: #1e90ff;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.jpeg" alt="Buff Bros Logo" />
    <h1>Buff Bros</h1>
    <p>Specialized Details and More</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#process">Our Process</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services" class="section">
    <h2>Pricing</h2>
    <div class="price-list">
      <h3>Interior Only</h3>
      <p>Starting at <strong>$150</strong></p>
      <ul>
        <li>Level 1: no extra cost</li>
        <li>Level 2: +$20</li>
        <li>Level 3: +$40</li>
      </ul>

      <h3>Exterior Wash</h3>
      <p>$40</p>

      <h3>Wax</h3>
      <p>$30</p>

      <h3>Combo Package</h3>
      <p><strong>Interior + Exterior + Wax = $20 off</strong></p>
    </div>
  </section>

  <section id="gallery" class="section">
    <h2>Image Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Before+1" alt="Before 1" />
      <img src="https://via.placeholder.com/300x200?text=After+1" alt="After 1" />
      <img src="https://via.placeholder.com/300x200?text=Before+2" alt="Before 2" />
      <img src="https://via.placeholder.com/300x200?text=After+2" alt="After 2" />
    </div>
  </section>

  <section id="process" class="section">
    <h2>Our Process</h2>
    <p>We take pride in delivering the highest quality detailing service with care and precision. Here's how we do it:</p>
    <ul>
      <li>Vacuuming and deep interior clean</li>
      <li>Stain treatment and surface shampooing</li>
      <li>Dashboard, vents, and trim detailed</li>
      <li>Hand wash exterior and tire shine</li>
      <li>Waxing and optional polish upgrade</li>
      <li>Final inspection and client satisfaction check</li>
    </ul>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p><strong>Cole Thomas</strong></p>
    <p>Phone: <a href="tel:5038034083">503-803-4083</a></p>
    <p>Email: <a href="mailto:Elocstarr@icloud.com">Elocstarr@icloud.com</a></p>
  </section>

  <footer>
    &copy; 2025 Buff Bros. All rights reserved.
  </footer>
<form action="https://formspree.io/f/xeogpkdl" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <label for="message">Message:</label>
  <textarea id="message" name="message" required></textarea>

  <button type="submit">Send</button>
</form>
</body>
</html>
