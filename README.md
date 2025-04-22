# Sieger-studios
online marketing firm 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Simple Digital Marketing</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f7f7f7;
      color: #333;
    }
    header {
      background: #4a90e2;
      color: white;
      padding: 20px;
      text-align: center;
      animation: fadeIn 1.5s ease-in;
    }
    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background: #357ABD;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: block;
      transition: background 0.3s;
    }
    nav a:hover {
      background-color: #285a8d;
    }
    .container {
      max-width: 960px;
      margin: 30px auto;
      padding: 0 20px;
      animation: slideUp 1s ease-in;
    }
    .section {
      background: white;
      margin-bottom: 20px;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input, textarea, button {
      padding: 10px;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background: #4a90e2;
      color: white;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #357ABD;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #4a90e2;
      color: white;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes slideUp {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <header>
    <h1>BrightPath Marketing</h1>
    <p>Your Path to Digital Growth</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <div id="services" class="section">
      <h2>Our Services</h2>
      <ul>
        <li>Search Engine Optimization (SEO)</li>
        <li>Social Media Management</li>
        <li>Email Marketing Campaigns</li>
        <li>Pay-Per-Click Advertising</li>
      </ul>
    </div>

    <div id="about" class="section">
      <h2>About Us</h2>
      <p>We help small businesses grow online through smart and effective marketing strategies.</p>
    </div>

    <div id="contact" class="section">
      <h2>Contact Us</h2>
      <form action="#" method="post">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>

  <footer>
    &copy; 2025 BrightPath Marketing. All rights reserved.
  </footer>
</body>
</html>
