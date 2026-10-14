

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#100b1b">
  <meta name="description" content="Enter the dreamy world of BerryxFairy — magical wallpapers and fairy-inspired digital art.">
  <title>BerryxFairy | A Little Magic</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background: #100b1b;
      color: #f7edf9;
      font-family: Georgia, "Times New Roman", serif;
      line-height: 1.7;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    header {
      padding: 22px 7%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 16px;
      border-bottom: 1px solid #30213e;
    }

    .logo {
      font-size: 1.35rem;
      letter-spacing: 2px;
      color: #e7c5ff;
    }

    nav {
      display: flex;
      gap: 18px;
      flex-wrap: wrap;
      font-family: Arial, sans-serif;
      font-size: 0.85rem;
    }

    nav a:hover {
      color: #e7c5ff;
    }

    .hero {
      min-height: 74vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 75px 8%;
      background:
        radial-gradient(ellipse at 50% 30%,
        #4a285d 0%, #241632 42%, #100b1b 78%);
    }

    .moon {
      font-size: 3.3rem;
      margin-bottom: 12px;
    }

    .eyebrow {
      text-transform: uppercase;
      letter-spacing: 4px;
      font: 0.72rem Arial, sans-serif;
      color: #d7b2ed;
    }

    h1 {
      font-size: clamp(2.8rem, 10vw, 5.5rem);
      line-height: 1.1;
      margin: 18px 0;
      font-weight: normal;
    }

    .hero p {
      max-width: 480px;
      margin: 0 auto 28px;
      color: #d5c5dd;
    }

    .button {
      display: inline-block;
      padding: 12px 25px;
      border: 1px solid #d8b5ef;
      border-radius: 30px;
      color: #fff;
      background: #533566;
      font: 0.9rem Arial, sans-serif;
      transition: 0.2s;
    }

    .button:hover {
      background: #70478a;
    }

    section {
      padding: 65px 7%;
    }

    .section-heading {
      text-align: center;
      margin-bottom: 30px;
    }

    h2 {
      font-size: 2.1rem;
      font-weight: normal;
      color: #e7c5ff;
      margin-bottom: 8px;
    }

    .muted {
      color: #c2b2cd;
      font-size: 0.95rem;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 22px;
      max-width: 900px;
      margin: auto;
    }

    .product {
      background: #1b1227;
      border: 1px solid #392748;
      border-radius: 16px;
      overflow: hidden;
      text-align: center;
      padding-bottom: 25px;
    }

    .art {
      min-height: 190px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 4rem;
      background:
        radial-gradient(circle at 50% 35%,
        #74518c, #30203e 60%, #171020);
    }

    .product h3 {
      font-size: 1.3rem;
      font-weight: normal;
      margin: 18px 10px 5px;
    }

    .product p {
      color: #c2b2cd;
      font: 0.88rem Arial, sans-serif;
      padding: 0 15px;
      margin-bottom: 18px;
    }

    .about {
      text-align: center;
      background: #181020;
    }

    .about p {
      max-width: 600px;
      margin: auto;
      color: #d5c5dd;
    }

    .contact {
      text-align: center;
    }

    footer {
      padding: 25px 7%;
      border-top: 1px solid #30213e;
      text-align: center;
      color: #b9a7c4;
      font: 0.8rem Arial, sans-serif;
    }

    @media (max-width: 480px) {
      header {
        flex-direction: column;
      }

      nav {
        justify-content: center;
      }

      .hero {
        min-height: 65vh;
      }
    }
  </style>
</head>

<body>
  <header>
    <a class="logo" href="#">BerryxFairy ✧</a>
    <nav>
      <a href="#home">Home</a>
      <a href="#collection">Collection</a>
      <a href="#about">Our world</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div>
        <div class="moon">☾</div>
        <div class="eyebrow">A little magic for your world</div>
        <h1>Welcome to<br>BerryxFairy</h1>
        <p>
          Dreamy wallpapers, midnight magic, and little
          pieces of fantasy made for your everyday world.
        </p>
        <a class="button" href="#collection">Explore the collection ✧</a>
      </div>
    </section>

    <section id="collection">
      <div class="section-heading">
        <div class="eyebrow">Made for dreamers</div>
        <h2>The Fairy Collection</h2>
        <p class="muted">
          A glimpse into our magical universe.
        </p>
      </div>

      <div class="products">
        <article class="product">
          <div class="art">🌙</div>
          <h3>Dreamy Phone Wallpapers</h3>
          <p>Moonlit skies and dreamy screens.</p>
          <a class="button" href="#contact">Coming soon</a>
        </article>

        <article class="product">
          <div class="art">🦋</div>
          <h3>Dark Fairy Dreams</h3>
          <p>Soft shadows and enchanted wings.</p>
          <a class="button" href="#contact">Coming soon</a>
        </article>

        <article class="product">
          <div class="art">✨</div>
          <h3>Fairy Study</h3>
          <p>Little sparks of inspiration for your day.</p>
          <a class="button" href="#contact">Coming soon</a>
        </article>
      </div>
    </section>

    <section class="about" id="about">
      <div class="section-heading">
        <h2>A world beyond ordinary</h2>
      </div>
      <p>
        BerryxFairy is a little corner of the internet
        inspired by fantasy, moonlight, mysterious beauty,
        and creativity. Every creation begins with a dream.
      </p>
    </section>

    <section class="contact" id="contact">
      <div class="eyebrow">Stay in our orbit</div>
      <h2>Something magical is coming</h2>
      <p class="muted">
        Our digital collection is being prepared.
        Come back soon to discover more.
      </p>
    </section>
  </main>

  <footer>
    <p>☾ BerryxFairy ✧ Made for dreamers.</p>
    <p>© 2026 BerryxFairy. All rights reserved.</p>
  </footer>
</body>
</html>
