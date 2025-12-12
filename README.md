# vishal.co.in
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vishal.co.in</title>
  <meta name="description" content="Official website of Vishal – portfolio, projects, and contact." />

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #222;
    }

    header {
      background: #111;
      padding: 20px;
      color: #fff;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 1px;
    }

    .hero {
      background: linear-gradient(#00000099, #00000099), url('https://source.unsplash.com/1600x800/?tech');
      height: 70vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
      background-size: cover;
      background-position: center;
    }

    .hero h1 {
      font-size: 50px;
      margin: 0;
    }

    .section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 7px rgba(0,0,0,0.1);
    }

    footer {
      background: #111;
      color: #bbb;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }

    .contact-form input, .contact-form textarea {
      width: 90%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    .contact-form button {
      padding: 12px 20px;
      background: #111;
      color: #fff;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

  </style>
</head>
<body>

<header>Vishal.co.in</header>

<section class="hero">
  <h1>Welcome to Vishal's World</h1>
</section>

<section class="section" id="about">
  <h2>About Me</h2>
  <p>Hey! I'm Vishal. This is my personal website where I share my projects, ideas, and journey. Stay tuned!</p>
</section>

<section class="section" id="projects">
  <h2>My Projects</h2>
  <div class="projects">
    <div class="card"><h3>Project 1</h3><p>Coming soon...</p></div>
    <div class="card"><h3>Project 2</h3><p>Work in progress...</p></div>
    <div class="card"><h3>Project 3</h3><p>Stay tuned!</p></div>
  </div>
</section>

<section class="section" id="contact">
  <h2>Contact Me</h2>
  <form class="contact-form">
    <input type="text" placeholder="Your Name" required />
    <input type="email" placeholder="Your Email" required />
    <textarea rows="5" placeholder="Your Message"></textarea>
    <button type="submit">Send</button>
  </form>
</section>

<footer>
  © 2025 Vishal.co.in — All Rights Reserved.
</footer>

</body>
</html>
