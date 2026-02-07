<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>List file vynn</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f5f5f5; }
    header { background: #2c3e50; color: white; padding: 20px; text-align: center; }
    nav a { color: white; margin: 0 10px; text-decoration: none; font-weight: bold; }
    .container { padding: 20px; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
    .card { background: white; padding: 15px; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    .card img { width: 100%; border-radius: 6px; }
    .card h3 { margin: 10px 0 5px; }
    .card p { margin: 5px 0; }
    .btn { display: inline-block; margin-top: 10px; padding: 10px 15px; background: #27ae60; color: white; text-decoration: none; border-radius: 5px; }
    footer { background: #2c3e50; color: white; text-align: center; padding: 15px; margin-top: 30px; }
  </style>
</head>
<body>
  <header>
    <h1>List file vynn</h1>
    <nav>
      <a href="#produk">Produk</a>
      <a href="#kontak">0816331836</a>
    </nav>
  </header>  <div class="container" id="produk">
    <h2>Produk Kami</h2>
    <div class="products">
      <div class="card">
        <img src="https://via.placeholder.com/300" alt="Produk 1" />
        <h3>gloowall mini</h3>
        <p>Harga: Rp8.000</p>
        <a class="btn" href="https://wa.me/62816331836">Beli via WhatsApp</a>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300" alt="Produk 2" />
        <h3>40% hs</h3>
        <p>Harga: Rp30.000</p>
        <a class="btn" href="https://wa.me/62816331836">Beli via WhatsApp</a>
      </div>
    </div>
  </div>  <div class="container" id="kontak">
    <h2>Kontak</h2>
    <p>WhatsApp: 0816331836</p>
  </div>  <footer>
    <p>&copy; 2026 LIST PANEL VYNN</p>
  </footer>
</body>
</html>
