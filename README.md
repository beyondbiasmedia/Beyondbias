<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Beyond Bias — News Without The Noise</title>
  <meta name="description" content="Beyond Bias — Independent news, facts, analysis and stories that matter.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f7f7f5;
      color: #111;
    }

    header {
      background: #111;
      color: white;
      padding: 18px 6%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    .logo {
      font-size: 25px;
      font-weight: 800;
      letter-spacing: 1px;
    }

    .logo span {
      font-weight: 400;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-size: 14px;
    }

    .ticker {
      background: #d71920;
      color: white;
      padding: 10px 6%;
      font-size: 14px;
      font-weight: bold;
    }

    main {
      width: 88%;
      max-width: 1250px;
      margin: 35px auto;
    }

    .hero {
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 25px;
      margin-bottom: 45px;
    }

    .hero-main {
      min-height: 380px;
      background: linear-gradient(135deg, #222, #555);
      color: white;
      padding: 35px;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      border-radius: 14px;
    }

    .tag {
      color: #e21d25;
      font-size: 13px;
      font-weight: bold;
      text-transform: uppercase;
      margin-bottom: 10px;
    }

    .hero-main .tag {
      color: #ff5960;
    }

    h1 {
      font-size: clamp(34px, 5vw, 58px);
      line-height: 1.05;
      margin-bottom: 15px;
    }

    .hero-main p {
      color: #ddd;
      max-width: 700px;
      line-height: 1.6;
    }

    .side-news {
      background: white;
      padding: 25px;
      border-radius: 14px;
      box-shadow: 0 5px 25px rgba(0,0,0,0.06);
    }

    .side-news article {
      padding: 18px 0;
      border-bottom: 1px solid #ddd;
    }

    .side-news article:last-child {
      border-bottom: none;
    }

    .side-news h3 {
      font-size: 18px;
      line-height: 1.35;
    }

    .section-title {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
      border-bottom: 2px solid #111;
      padding-bottom: 10px;
    }

    .section-title h2 {
      font-size: 27px;
    }

    .news-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .card {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 5px 20px rgba(0,0,0,0.05);
    }

    .image-placeholder {
      height: 180px;
      background: #ddd;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #777;
      font-size: 13px;
    }

    .card-content {
      padding: 20px;
    }

    .card h3 {
      font-size: 20px;
      line-height: 1.3;
      margin: 8px 0;
    }

    .card p {
      color: #666;
      font-size: 14px;
      line-height: 1.5;
    }

    .fact-check {
      margin-top: 50px;
      background: #111;
      color: white;
      border-radius: 14px;
      padding: 30px;
    }

    .fact-check h2 {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .fact-check p {
      color: #ccc;
      line-height: 1.6;
    }

    footer {
      margin-top: 60px;
      background: #111;
      color: white;
      padding: 40px 6%;
      text-align: center;
    }

    footer p {
      color: #aaa;
      margin-top: 10px;
      font-size: 14px;
    }

    @media (max-width: 800px) {
      nav {
        display: none;
      }

      .hero {
        grid-template-columns: 1fr;
      }

      .news-grid {
        grid-template-columns: 1fr;
      }

      main {
        width: 92%;
      }

      .hero-main {
        min-height: 350px;
        padding: 25px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">BEYOND<span>BIAS</span></div>

    <nav>
      <a href="#">Latest</a>
      <a href="#">India</a>
      <a href="#">World</a>
      <a href="#">Politics</a>
      <a href="#">Society</a>
      <a href="#">Fact Check</a>
    </nav>
  </header>

  <div class="ticker">
    BREAKING NEWS • BEYOND HEADLINES. BEYOND BIAS.
  </div>

  <main>

    <section class="hero">

      <div class="hero-main">
        <div class="tag">Top Story</div>

        <h1>News that informs. Facts that matter.</h1>

        <p>
          Beyond Bias brings you important stories, independent reporting,
          explainers and fact-based analysis without unnecessary noise.
        </p>
      </div>

      <div class="side-news">

        <div class="section-title">
          <h2>Latest</h2>
        </div>

        <article>
          <div class="tag">India</div>
          <h3>Latest developments from across the country</h3>
        </article>

        <article>
          <div class="tag">World</div>
          <h3>What is happening around the world?</h3>
        </article>

        <article>
          <div class="tag">Politics</div>
          <h3>Political developments and public affairs</h3>
        </article>

      </div>

    </section>


    <section>

      <div class="section-title">
        <h2>Latest News</h2>
      </div>

      <div class="news-grid">

        <article class="card">
          <div class="image-placeholder">NEWS IMAGE</div>

          <div class="card-content">
            <div class="tag">India</div>
            <h3>India's latest news and developments</h3>
            <p>
              Read the latest updates and important developments.
            </p>
          </div>
        </article>


        <article class="card">
          <div class="image-placeholder">NEWS IMAGE</div>

          <div class="card-content">
            <div class="tag">World</div>
            <h3>Major developments making headlines worldwide</h3>
            <p>
              Important international stories explained clearly.
            </p>
          </div>
        </article>


        <article class="card">
          <div class="image-placeholder">NEWS IMAGE</div>

          <div class="card-content">
            <div class="tag">Society</div>
            <h3>Stories from society that deserve attention</h3>
            <p>
              People, communities and issues that matter.
            </p>
          </div>
        </article>

      </div>

    </section>


    <section class="fact-check">

      <h2>Beyond Bias — Fact Check</h2>

      <p>
        Viral claims can spread quickly. Our fact-check section examines
        important claims and provides context so readers
