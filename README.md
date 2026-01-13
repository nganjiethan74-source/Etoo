<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title> NGANJI Ethan | Professional Photography</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #1f2933;
      --secondary: #c9a24d;
      --accent: #3b82f6;
      --light: #f9fafb;
      --dark: #111827;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: var(--light);
      color: var(--primary);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(rgba(17,24,39,0.7), rgba(17,24,39,0.7)),
                  url('https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f') center/cover no-repeat;
      height: 100vh;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      max-width: 600px;
      margin-bottom: 20px;
    }

    .btn {
      background: var(--secondary);
      color: var(--dark);
      padding: 12px 30px;
      border: none;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s ease;
    }

    .btn:hover {
      background: var(--accent);
      color: white;
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(17,24,39,0.95);
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
    }

    nav h2 {
      color: var(--secondary);
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 0.9rem;
    }

    section {
      padding: 80px 40px;
      max-width: 1200px;
      margin: auto;
    }

    .section-title {
      text-align: center;
      margin-bottom: 50px;
    }

    .section-title h2 {
      font-size: 2.2rem;
      margin-bottom: 10px;
      color: var(--dark);
    }

    .about {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 40px;
      align-items: center;
    }

    .about img {
      width: 100%;
      border-radius: 15px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    .card h3 {
      margin-bottom: 10px;
      color: var(--secondary);
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 15px;
      transition: 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    form {
      max-width: 600px;
      margin: auto;
      display: grid;
      gap: 15px;
    }

    input, textarea {
      padding: 12px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }

    footer {
      background: var(--dark);
      color: white;
      text-align: center;
      padding: 30px 20px;
      margin-top: 50px;
    }

    @media (max-width: 600px) {
      header h1 { font-size: 2.2rem; }
    }
  </style>
</head>
<body>

  <nav>
    <h2>Lumière Studio</h2>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header>
    <h1>Capturing Moments That Last Forever</h1>
    <p>Professional photography studio specializing in weddings, portraits, events, and commercial shoots.</p>
    <a href="#contact" class="btn">Book a Session</a>
  </header>

  <section id="about">
    <div class="section-title">
      <h2>About Us</h2>
      <p>Creative. Professional. Reliable.</p>
    </div>
    <div class="about">
      <div>
        <p>Lumière Studio is a premium photography brand dedicated to telling stories through powerful images. With years of experience and modern equipment, we deliver high-quality photos that meet international standards.</p>
        <p>Our mission is to capture genuine emotions and transform them into timeless memories.</p>
      </div>
      <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="Photography">
    </div>
  </section>

  <section id="services">
    <div class="section-title">
      <h2>Our Services</h2>
    </div>
    <div class="services">
      <div class="card">
        <h3>Wedding Photography</h3>
        <p>Elegant and emotional coverage of your special day.</p>
      </div>
      <div class="card">
        <h3>Portrait Sessions</h3>
        <p>Professional portraits for individuals, families, and brands.</p>
      </div>
      <div class="card">
        <h3>Event Coverage</h3>
        <p>Corporate and private events captured with precision.</p>
      </div>
      <div class="card">
        <h3>Commercial Shoots</h3>
        <p>High-quality visuals for marketing and advertising.</p>
      </div>
    </div>
  </section>

  <section id="gallery">
    <div class="section-title">
      <h2>Gallery</h2>
    </div>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e" alt="Gallery 1">
      <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330" alt="Gallery 2">
      <img src="https://images.unsplash.com/photo-1508214751196-bcfd4ca60f91" alt="Gallery 3">
      <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9" alt="Gallery 4">
    </div>
  </section>

  <section id="contact">
    <div class="section-title">
      <h2>Contact Us</h2>
      <p>Let’s work together</p>
    </div>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button class="btn" type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2026 NGANJI Ethan Photography. All Rights Reserved.</p>
  </footer>

</body>
</html>
