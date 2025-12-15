<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Agrodutt – Sustainable Agro Enterprise</title>

  <meta name="description" content="Agrodutt is a professional, sustainable agro-enterprise focused on horticulture, ethical beekeeping, agro-tourism, fresh fruits, and future-ready food processing." />
  <meta http-equiv="Content-Language" content="en" />

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

  <style>
    :root {
      --green: #2f5d50;
      --gold: #c9a44c;
      --brown: #3a2f2a;
      --white: #ffffff;
      --light: #f6f7f4;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--white);
      color: #333;
      line-height: 1.6;
    }

    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
      color: var(--green);
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* HEADER */
    header {
      position: sticky;
      top: 0;
      background: rgba(255,255,255,0.95);
      padding: 1rem 3rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      z-index: 1000;
    }

    header h2 {
      color: var(--brown);
    }

    nav a {
      margin-left: 1.5rem;
      font-weight: 500;
    }

    /* HERO */
    .hero {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
      url("https://images.unsplash.com/photo-1524594227084-4c6e3ad1a79b") center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      padding: 2rem;
    }

    .hero h1 {
      font-size: 3.2rem;
      color: white;
    }

    .hero p {
      margin: 1rem 0 2rem;
      font-size: 1.2rem;
    }

    .btn {
      background: var(--gold);
      padding: 0.8rem 1.6rem;
      border-radius: 30px;
      margin: 0 0.5rem;
      font-weight: 600;
      color: #000;
      display: inline-block;
    }

    /* SECTIONS */
    section {
      padding: 5rem 8%;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .card {
      background: var(--light);
      padding: 2rem;
      border-radius: 16px;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    /* STATS */
    .stats {
      display: flex;
      justify-content: space-around;
      text-align: center;
      background: var(--green);
      color: white;
      padding: 4rem 2rem;
    }

    .stats h2 {
      color: var(--gold);
    }

    /* CONTACT */
    form {
      max-width: 600px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }

    form input,
    form textarea {
      padding: 0.8rem;
      margin-bottom: 1rem;
      border-radius: 8px;
      border: 1px solid #ccc;
    }

    footer {
      background: var(--brown);
      color: white;
      text-align: center;
      padding: 2rem;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
      }
      nav {
        margin-top: 1rem;
      }
      .hero h1 {
        font-size: 2.4rem;
      }
    }
  </style>
</head>

<body>

<header>
  <h2>Agrodutt</h2>
  <nav>
    <a href="#about">About</a>
    <a href="#farms">Farms</a>
    <a href="#honey">Honey</a>
    <a href="#tourism">Agro-Tourism</a>
    <a href="#future">Future</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <div>
    <h1>Where Sustainable Farming Meets Nature</h1>
    <p>Cultivating health, honey & happiness from farm to future</p>
    <a class="btn" href="#farms">Explore Our Farms</a>
    <a class="btn" href="#tourism">Book an Agro-Tour</a>
  </div>
</section>

<section id="about">
  <h2>About Agrodutt</h2>
  <p>
    Agrodutt is a professional, future-ready agro enterprise built on sustainable horticulture,
    ethical beekeeping, responsible agro-tourism, premium fresh produce, and environmentally
    conscious food processing. Every operation follows transparent, science-backed,
    and globally accepted agricultural practices.
  </p>
</section>

<section id="farms">
  <h2>Our Farms</h2>
  <div class="grid">
    <div class="card">Horticulture Orchards</div>
    <div class="card">Beekeeping Apiaries</div>
    <div class="card">Agro-Tourism Locations</div>
  </div>
</section>

<section id="honey">
  <h2>Beekeeping & Honey</h2>
  <div class="grid">
    <div class="card">Wild Blossom Honey</div>
    <div class="card">Forest Honey</div>
    <div class="card">Seasonal Special Honey</div>
  </div>
</section>

<section id="tourism">
  <h2>Agro-Tourism Experiences</h2>
  <div class="grid">
    <div class="card">Farm Stay</div>
    <div class="card">Fruit Picking</div>
    <div class="card">Beekeeping Workshops</div>
  </div>
</section>

<section id="future">
  <h2>Future Food Processing</h2>
  <p>
    Agrodutt is expanding into food processing with value-added products like jams,
    dried fruits, and honey blends using sustainable practices.
  </p>
</section>

<section class="stats">
  <div>
    <h2>10,000+</h2>
    <p>Trees Planted</p>
  </div>
  <div>
    <h2>2M+</h2>
    <p>Bees Protected</p>
  </div>
  <div>
    <h2>50+</h2>
    <p>Villages Impacted</p>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>

  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Email Address" required>
    <textarea rows="5" placeholder="Your Message"></textarea>
    <button class="btn" type="submit">Connect With Us</button>
  </form>

  <div style="margin-top:3rem;">
    <h3>Our Farm Location</h3>
    <p>Visit our farms and experience sustainable agriculture firsthand.</p>

    <iframe
      src="https://www.google.com/maps?q=Uttar+Chatra,+Dakshin+Chatra,+North+24+Parganas,+West+Bengal+743247,+India&hl=en&z=14&output=embed"
      width="100%"
      height="350"
      style="border:0; border-radius:16px;"
      loading="lazy"
      allowfullscreen>
    </iframe>

    <p style="margin-top:1rem;">
      <strong>Address:</strong>
      Village: Uttar Chatra, Post Office: Dakshin Chatra,
      District: North 24 Parganas, State: West Bengal,
      PIN: 743247, India
    </p>
  </div>
</section>

<footer>
  <p>© 2025 Agrodutt. Sustainable Farming for the Future.</p>
</footer>

</body>
</html>
