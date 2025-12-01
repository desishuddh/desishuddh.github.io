<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Desi Shuddh - Official Store</title>

  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #f3eedf; }
    header { display: flex; justify-content: space-between; align-items: center; padding: 15px; background: #f3eedf; border-bottom: 1px solid #ddd; position: sticky; top: 0; z-index: 100; }
    .menu-icon, .icon { font-size: 22px; cursor: pointer; }
    .logo { font-weight: bold; font-size: 22px; color: #4a1f26; }

    .banner img { width: 100%; border-radius: 5px; }

    .section-title { font-size: 28px; font-weight: bold; padding: 15px; color: #4a1f26; }

    .products { display: grid; grid-template-columns: 1fr 1fr; gap: 15px; padding: 15px; }
    .product-card { background: #fff; padding: 10px; border-radius: 10px; border: 1px solid #ddd; text-align: center; transition: 0.3s; }
    .product-card:hover { transform: scale(1.03); }
    .product-card img { width: 100%; border-radius: 8px; }

    .price { color: #4a1f26; font-weight: bold; margin-top: 5px; }
    .old-price { text-decoration: line-through; color: #777; font-size: 14px; }

    button { width: 100%; padding: 10px; border-radius: 25px; border: 1px solid #4a1f26; background: none; margin-top: 10px; font-size: 16px; cursor: pointer; transition: 0.2s; }
    button:hover { background: #4a1f26; color: white; }
  </style>
</head>
<body>

  <header>
    <div class="menu-icon">☰</div>
    <div class="logo">DESI SHUDDH</div>
    <div>
      <span class="icon">🔍</span>
      <span class="icon">👤</span>
      <span class="icon">🛍️</span>
    </div>
  </header>

  <div class="banner">
    <img src="https://via.placeholder.com/800x300" alt="Desi Shuddh Banner">
  </div>

  <div class="section-title">हमारे प्रोडक्ट्स</div>

  <div class="products">
    <div class="product-card">
      <img src="https://via.placeholder.com/400x400" alt="Traditional Thekua">
      <div>Traditional Thekua</div>
      <div class="old-price">₹699.00</div>
      <div class="price">₹399.00</div>
      <button>कार्ट में जोड़ें</button>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/400x400" alt=Dasi Thekua">
      <div>Dasi Thekua</div>
      <div class="old-price">₹699.00</div>
      <div class="price">₹399.00</div>
      <button>कार्ट में जोड़ें</button>
    </div>
  </div>

</body>
</html>
