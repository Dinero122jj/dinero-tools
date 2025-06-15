<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DINERO TOOLS TECH SUPPORT</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #111827;
      color: #fff;
      padding: 1.5rem;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
    }
    section {
      padding: 2rem;
    }
    .services, .portfolio {
      display: grid;
      gap: 1.5rem;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
    .card {
      background: #fff;
      padding: 1rem;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    footer {
      background: #111827;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    button {
      background: #2563eb;
      color: #fff;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 600;
    }
    button:hover {
      background: #1d4ed8;
    }
  </style>
</head>
<body>
  <header>
    <h1>DINERO TOOLS TECH SUPPORT</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Technical Support</h3>
        <p>Fast and reliable tech support for hardware and software issues.</p>
      </div>
      <div class="card">
        <h3>Device Repair</h3>
        <p>Expert repair services for mobile phones, laptops, and gadgets.</p>
      </div>
      <div class="card">
        <h3>AI Integration</h3>
        <p>Automate your business or personal tasks using smart AI solutions.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2>Recent Projects</h2>
    <div class="portfolio">
      <div class="card">
        <h4>Remote PC Support</h4>
        <p>Resolved over 500+ client system issues remotely.</p>
      </div>
      <div class="card">
        <h4>AI Bot Setup</h4>
        <p>Created automated customer service bots for small businesses.</p>
      </div>
      <div class="card">
        <h4>Device Optimization</h4>
        <p>Speed and performance boost for low-end devices.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact & Patronize Us</h2>
    <p>Interested in our services? Reach out below!</p>
    <form action="mailto:your@email.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required style="padding:10px;width:100%;margin-bottom:10px;border-radius:8px;border:1px solid #ccc;">
      <input type="email" name="email" placeholder="Your Email" required style="padding:10px;width:100%;margin-bottom:10px;border-radius:8px;border:1px solid #ccc;">
      <textarea name="message" placeholder="Your message..." rows="5" required style="padding:10px;width:100%;margin-bottom:10px;border-radius:8px;border:1px solid #ccc;"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 DINERO TOOLS TECH SUPPORT. All rights reserved.</p>
  </footer>
</body>
</html>
</index.html> 
