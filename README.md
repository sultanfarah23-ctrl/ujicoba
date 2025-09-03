<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fastidious Apparel</title>
  <style>
    /* Reset */
    * {margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif;}
    body {background: #fff; color: #111;}
    a {text-decoration: none; color: inherit;}
    /* Header */
    header {display: flex; justify-content: space-between; align-items: center; padding: 1rem 2rem; border-bottom: 1px solid #ddd; position: sticky; top: 0; background: #fff; z-index: 100;}
    .logo {font-size: 1.5rem; font-weight: bold;}
    nav a {margin-left: 1.5rem; font-size: 0.95rem; color: #333;}
    /* Search */
    .search-bar {display: flex; justify-content: center; align-items: center; padding: 1rem; gap: 0.5rem; border-bottom: 1px solid #eee;}
    .search-bar input, .search-bar select, .search-bar button {padding: 0.5rem 0.8rem; border: 1px solid #ccc; border-radius: 6px; font-size: 0.9rem;}
    .search-bar input {flex: 1; min-width: 200px;}
    .search-bar button {background: #111; color: #fff; cursor: pointer;}
    /* Produk Grid */
    .products {display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1.5rem; padding: 2rem;}
    .product {border: 1px solid #eee; border-radius: 10px; padding: 1rem; background: #fafafa; transition: 0.2s;}
    .product:hover {box-shadow: 0 4px 10px rgba(0,0,0,0.08);}
    .product img {width: 100%; border-radius: 8px; margin-bottom: 0.8rem;}
    .product h3 {font-size: 1rem; margin-bottom: 0.5rem;}
    .product p {font-size: 0.9rem; color: #555; margin-bottom: 0.5rem;}
    .product .price {font-weight: bold; color: #000;}
    /* Detail Produk */
    .product-detail {max-width: 1000px; margin: 2rem auto; display: flex; gap: 2rem; padding: 1rem;}
    .product-detail img {width: 50%; border-radius: 10px;}
    .detail-info {flex: 1;}
    .detail-info h2 {margin-bottom: 1rem;}
    .detail-info p {margin-bottom: 0.8rem; color: #444; line-height: 1.5;}
    .detail-info .price {font-size: 1.2rem; margin-bottom: 1rem;}
    .detail-info button {padding: 0.7rem 1.5rem; background: #111; color: #fff; border: none; border-radius: 8px; cursor: pointer;}
    /* Footer */
    footer {text-align: center; padding: 1.5rem; border-top: 1px solid #eee; margin-top: 2rem; font-size: 0.9rem; color: #555;}
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">Fastidious Apparel</div>
    <nav>
      <a href="#">Beranda</a>
      <a href="#">Kategori</a>
      <a href="#">Tentang</a>
      <a href="#">Kontak</a>
    </nav>
  </header>
  <!-- Search -->
  <div class="search-bar">
    <input type="text" placeholder="Cari kaos limited...">
    <select>
      <option>Semua Kategori</option>
      <option>Oversized</option>
      <option>Regular Fit</option>
      <option>Premium</option>
    </select>
    <button>Cari</button>
  </div>
  <!-- Produk Grid -->
  <section class="products">
    <div class="product">
      <img src="produk1.jpg" alt="Produk 1">
      <h3>Kaos Premium Hitam</h3>
      <p>Material 100% katun, nyaman dipakai.</p>
      <div class="price">Rp 250.000</div>
    </div>
    <div class="product">
      <img src="produk2.jpg" alt="Produk 2">
      <h3>Kaos Oversized Putih</h3>
      <p>Desain minimalis, cocok untuk casual look.</p>
      <div class="price">Rp 230.000</div>
    </div>
    <div class="product">
      <img src="produk3.jpg" alt="Produk 3">
      <h3>Kaos Abu Limited</h3>
      <p>Edisi terbatas dengan potongan modern.</p>
      <div class="price">Rp 270.000</div>
    </div>
  </section>
  <!-- Detail Produk (contoh halaman terpisah) -->
  <section class="product-detail">
    <img src="produk1.jpg" alt="Detail Produk">
    <div class="detail-info">
      <h2>Kaos Premium Hitam</h2>
      <p>Kaos limited edition dengan bahan katun premium, nyaman dipakai sehari-hari maupun untuk acara casual. Jahitan rapi dan desain eksklusif hanya tersedia di Fastidious Apparel.</p>
      <div class="price">Rp 250.000</div>
      <button>Tambah ke Keranjang</button>
    </div>
  </section>
  <!-- Footer -->
  <footer>
    © 2025 Fastidious Apparel. All rights reserved.
  </footer>
</body>
</html>
