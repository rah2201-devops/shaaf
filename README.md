<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aarah Candles</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0; padding: 0;
      box-sizing: border-box;
      font-family: 'Open Sans', sans-serif;
    }

    body {
      background: #fff8f0;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #f9e5d8;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3em;
      color: #5e3c28;
    }

    header p {
      font-size: 1.2em;
      margin: 10px 0 20px;
    }

    header a {
      display: inline-block;
      padding: 10px 25px;
      background: #5e3c28;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .about {
      text-align: center;
    }

    .about h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2em;
      margin-bottom: 10px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      object-fit: cover;
    }

    .contact {
      text-align: center;
      margin-top: 40px;
    }

    .contact a {
      color: #5e3c28;
      text-decoration: underline;
    }

    footer {
      background: #f3d9c3;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Aarah Candles</h1>
    <p>Hand-poured | Natural | Soul-soothing</p>
    <a href="https://instagram.com/aarah_candles" target="_blank">Follow us on Instagram</a>
  </header>

  <section class="about">
    <h2>About Aarah Candles</h2>
    <p>
      At Aarah Candles, we craft hand-poured candles with love, intention, and sustainable ingredients.
      Each scent is designed to bring calm, warmth, and joy into your space.
    </p>
  </section>

  <section>
    <h2 style="text-align:center;">Our Candles</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x300?text=Candle+1" alt="Candle 1">
      <img src="https://via.placeholder.com/300x300?text=Candle+2" alt="Candle 2">
      <img src="https://via.placeholder.com/300x300?text=Candle+3" alt="Candle 3">
      <img src="https://via.placeholder.com/300x300?text=Candle+4" alt="Candle 4">
    </div>
  </section>

  <section class="contact">
    <h2>Order or Collaborate</h2>
    <p>DM us on <a href="https://instagram.com/aarah_candles" target="_blank">@aarah_candles</a> to place an order or inquire about custom candles.</p>
  </section>

  <footer>
    &copy; 2025 Aarah Candles. All rights reserved.
  </footer>

</body>
</html>
