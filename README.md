<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nqabane | Web Designer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #1e1e1e;
      color: #fff;
      padding: 2rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      color: #fff;
      text-decoration: none;
    }
    section {
      padding: 2rem;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .card {
      background: white;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    footer {
      background: #1e1e1e;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Nqabane Matshona</h1>
    <p>Web Designer & Developer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#work">My Work</a>
      <a href="#pricing">Pricing</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a passionate web designer based in South Africa. I help small businesses, creators, and startups build modern, responsive websites at affordable prices.</p>
  </section>

  <section id="work">
    <h2>My Work</h2>
    <div class="projects">
      <div class="card">
        <h3>Business Site</h3>
        <p>Clean 3-page website for a local barber shop.</p>
      </div>
      <div class="card">
        <h3>Portfolio</h3>
        <p>Simple scroll website with gallery and contact form.</p>
      </div>
    </div>
  </section>

  <section id="pricing">
    <h2>Pricing</h2>
    <ul>
      <li>1-page site — <strong>R700</strong></li>
      <li>3-page business site — <strong>R2,000</strong></li>
      <li>Online portfolio — <strong>R1,500</strong></li>
      <li>Domain setup — <strong>R500</strong></li>
      <li>Monthly updates — <strong>R200/month</strong></li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:nqabanewebsites@gmail.com">nqabanematshona@gmail.com</a></p>
    <p>WhatsApp: <a href="https://wa.me/27xxxxxxxxx">+27 791518098</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Nqabane Matshona. All rights reserved.</p>
  </footer>
</body>
</html>
