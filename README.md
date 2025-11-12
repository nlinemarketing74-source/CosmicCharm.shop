<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cosmic Charm | Aksesori Handmade</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #ffffff;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      text-align: center;
      padding: 40px 20px;
      background-color: #f8f2ff;
      border-bottom: 2px solid #e6dafc;
    }
    header img {
      width: 160px;
      border-radius: 12px;
    }
    h1 {
      color: #6b40b9;
      margin: 15px 0 5px;
    }
    p.tagline {
      color: #9b59b6;
      font-size: 1.1em;
    }
    .catalog {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
      padding: 40px;
      max-width: 1000px;
      margin: auto;
    }
    .product {
      background: #fff;
      border-radius: 15px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.08);
      padding: 15px;
      text-align: center;
      transition: transform 0.2s;
    }
    .product:hover {
      transform: scale(1.03);
    }
    .product img {
      width: 100%;
      border-radius: 12px;
      object-fit: cover;
      height: 200px;
    }
    .product h3 {
      color: #663399;
      margin: 10px 0 5px;
    }
    .product p {
      color: #9b59b6;
      font-weight: bold;
    }
    .order-btn {
      background-color: #9b59b6;
      color: white;
      padding: 8px 15px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 8px;
      text-decoration: none;
      display: inline-block;
      font-weight: 600;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #f8f2ff;
      color: #6b40b9;
      font-size: 0.9em;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.jpg" alt="Cosmic Charm Logo">
    <h1>Cosmic Charm</h1>
    <p class="tagline">Aksesori handmade minimalis yang penuh pesona ✨</p>
  </header>

  <section class="catalog">
    <!-- Cincin -->
    <div class="product">
      <img src="cincin.jpg" alt="Cincin Manik">
      <h3>Cincin Manik</h3>
      <p>Rp3.000</p>
      <a class="order-btn" href="https://wa.me/6285129091034?text=Halo%20Cosmic%20Charm!%20Saya%20ingin%20pesan%20Cincin%20Manik.">Order via WhatsApp</a>
    </div>

    <!-- Gelang -->
    <div class="product">
      <img src="gelang.jpg" alt="Gelang Manik">
      <h3>Gelang Manik</h3>
      <p>Rp5.000</p>
      <a class="order-btn" href="https://wa.me/6285129091034?text=Halo%20Cosmic%20Charm!%20Saya%20ingin%20pesan%20Gelang%20Manik.">Order via WhatsApp</a>
    </div>

    <!-- Gantungan -->
    <div class="product">
      <img src="gantungan.jpg" alt="Gantungan Manik">
      <h3>Gantungan Manik</h3>
      <p>Rp10.000</p>
      <a class="order-btn" href="https://wa.me/6285129091034?text=Halo%20Cosmic%20Charm!%20Saya%20ingin%20pesan%20Gantungan%20Manik.">Order via WhatsApp</a>
    </div>
  </section>

  <footer>
    © 2025 Cosmic Charm | Handmade Accessories ✨
  </footer>
</body>
</html>
