# index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trend Philosopher | Forex Trading</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #07111f;
      color: #f1f5f9;
      line-height: 1.6;
    }

    header {
      background: #0c1b30;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #168cff;
    }

    header h1 {
      color: #168cff;
      font-size: 30px;
    }

    header p {
      color: #b8c7dc;
    }

    nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 18px;
      padding: 15px 10px;
      background: #10233b;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #168cff;
    }

    .hero {
      text-align: center;
      padding: 75px 20px;
      background: linear-gradient(135deg, #07111f, #123d70);
    }

    .hero h2 {
      font-size: 38px;
      margin-bottom: 15px;
    }

    .blue {
      color: #36a0ff;
    }

    .hero p {
      max-width: 650px;
      margin: 0 auto 25px;
      color: #d2ddeb;
    }

    .btn {
      display: inline-block;
      background: #168cff;
      color: white;
      text-decoration: none;
      padding: 12px 20px;
      border-radius: 7px;
      margin: 6px;
      font-weight: bold;
    }

    .btn:hover {
      background: #0066cc;
    }

    .whatsapp {
      background: #168cff;
    }

    section {
      padding: 45px 20px;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 25px;
      color: #36a0ff;
      font-size: 28px;
    }

    .intro {
      text-align: center;
      max-width: 750px;
      margin: auto;
      color: #c6d3e3;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
    }

    .card {
      background: #10233b;
      border: 1px solid #203c5d;
      padding: 22px;
      border-radius: 12px;
    }

    .card h3 {
      color: #36a0ff;
      margin-bottom: 10px;
    }

    .card p {
      color: #c6d3e3;
    }

    .price {
      font-size: 25px;
      font-weight: bold;
      margin: 12px 0;
      color: white;
    }

    .notice {
      background: #10233b;
      border-left: 4px solid #168cff;
      padding: 15px;
      margin-top: 22px;
      border-radius: 5px;
      color: #c6d3e3;
    }

    #contact {
      text-align: center;
    }

    footer {
      background: #0c1b30;
      padding: 22px;
      text-align: center;
      color: #a9bbd1;
      border-top: 1px solid #203c5d;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 29px;
      }

      nav {
        gap: 12px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Trend Philosopher</h1>
    <p>Trade Smartly, Not Aggressively</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#analysis">Analysis</a>
    <a href="#learn">Learn</a>
    <a href="#plans">Plans</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero" id="home">
    <h2>Welcome to <span class="blue">Trend Philosopher</span></h2>

    <p>
      Explore forex market analysis, learn Smart Money Concepts (SMC),
      understand risk management, and develop your own trading skills.
    </p>

    <a class="btn"
       href="https://t.me/+aiMm4N2v1UpiNTY0"
       target="_blank" rel="noopener">
      Join Our Telegram
    </a>

    <a class="btn whatsapp"
       href="https://wa.me/256731717229"
       target="_blank" rel="noopener">
      Chat on WhatsApp
    </a>
  </div>

  <section id="about">
    <h2>About Us</h2>

    <p class="intro">
      Trend Philosopher is a trading education community focused on
      market structure, Smart Money Concepts, trade planning, and
      disciplined risk management. Our goal is to help traders learn
      to make informed decisions instead of chasing the market.
    </p>
  </section>

  <section id="analysis">
    <h2>Market Analysis</h2>

    <div class="cards">
      <div class="card">
        <h3>Forex Analysis</h3>
        <p>
          Study currency pairs, market structure, liquidity,
          and possible trading setups.
        </p>
      </div>

      <div class="card">
        <h3>SMC Concepts</h3>
        <p>
          Learn about order blocks, fair value gaps, break of structure,
          and changes in market character.
        </p>
      </div>

      <div class="card">
        <h3>Trade Planning</h3>
        <p>
          Plan entry conditions, invalidation levels, stop losses,
          and realistic profit targets before entering a trade.
        </p>
      </div>
    </div>

    <p class="notice">
      Important: The analysis section currently contains educational
      information, not live market signals. Add your own dated analysis
      before publishing it as current market commentary.
    </p>
  </section>

  <section id="learn">
    <h2>Learn Trading</h2>

    <div class="cards">
      <div class="card">
        <h3>Beginner Forex</h3>
        <p>
          Understand currency pairs, pips, spreads, leverage,
          and how the forex market works.
        </p>
      </div>

      <div class="card">
        <h3>Smart Money Concepts</h3>
        <p>
          Study liquidity, market structure, order blocks,
          and fair value gaps with practice charts.
        </p>
      </div>

      <div class="card">
        <h3>Risk Management</h3>
        <p>
          Learn position sizing, risk-to-reward ratios,
          trading journals, and how to protect your capital.
        </p>
      </div>
    </div>
  </section>

  <section id="plans">
    <h2>Membership Plans</h2>

    <div class="cards">
      <div class="card">
        <h3>Free Community</h3>
        <p class="price">Free</p>
        <p>Join the community and explore educational content.</p>

        <a class="btn"
           href="https://t.me/+aiMm4N2v1UpiNTY0"
           target="_blank" rel="noopener">
          Join Free
        </a>
      </div>

      <div class="card">
        <h3>Premium Access</h3>
        <p class="price">Coming Soon</p>
        <p>
          A planned membership for premium analysis and additional
          learning resources.
        </p>

        <a class="btn"
           href="https://wa.me/256731717229"
           target="_blank" rel="noopener">
          Ask About Membership
        </a>
      </div>

      <div class="card">
        <h3>Trading Books</h3>
        <p class="price">Coming Soon</p>
        <p>
          Educational books and study materials will be listed here
          when they are ready.
        </p>

        <a class="btn"
           href="https://wa.me/256731717229"
           target="_blank" rel="noopener">
          Ask About Books
        </a>
      </div>
    </div>

    <p class="notice">
      Memberships and books are not available for purchase through this
      demo page yet. Confirm prices, payment methods, and access rules
      before accepting payments.
    </p>
  </section>

  <section id="contact">
    <h2>Join the Community</h2>

    <p class="intro">
      Have a question about our educational content or community?
      Contact us using either link below.
    </p>

    <a class="btn"
       href="https://t.me/+aiMm4N2v1UpiNTY0"
       target="_blank" rel="noopener">
      Telegram Community
    </a>

    <a class="btn whatsapp"
       href="https://wa.me/256731717229"
       target="_blank" rel="noopener">
      WhatsApp: 0731717229
    </a>
  </section>

  <footer>
    <p>&copy; 2026 Trend Philosopher. All rights reserved.</p>
    <p>Educational content only. Forex trading involves risk.</p>
  </footer>

</body>
</html>
