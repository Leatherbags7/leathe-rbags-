# leathe-rbags-
Leather Bags Store offers handmade, high-quality leather bags combining style and durability. Perfect for everyday use, our bags are crafted to last and age beautifully. Shop securely with PayPal and enjoy excellent customer support.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Leather Bags Store</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f5f5f5; }
    header { background-color: #333; color: white; text-align: center; padding: 1rem 0; }
    h1 { margin: 0; }
    .container { max-width: 900px; margin: 20px auto; padding: 0 1rem; }
    .products { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
    .product-card {
      background: white; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 280px; padding: 15px; display: flex; flex-direction: column; align-items: center;
    }
    .product-card img { width: 100%; border-radius: 8px; }
    .product-name { font-weight: bold; font-size: 1.1rem; margin: 10px 0 5px; }
    .product-desc { font-size: 0.9rem; color: #555; text-align: center; }
    .product-price { font-size: 1.2rem; color: #2c3e50; margin: 10px 0; }
    .paypal-button {
      background-color: #ffc439; border: none; border-radius: 5px; padding: 10px 20px;
      font-weight: bold; cursor: pointer; transition: background-color 0.3s ease;
      text-decoration: none; color: #111;
      display: inline-block;
    }
    .paypal-button:hover { background-color: #ffb933; }
    footer { text-align: center; color: #888; padding: 15px 0; margin-top: 40px; font-size: 0.9rem; }
    @media (max-width: 600px) {
      .products { flex-direction: column; align-items: center; }
      .product-card { width: 90%; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Leather Bags Store</h1>
    <p>Premium Handmade Leather Bags</p>
  </header>

  <main class="container">
    <section class="products">

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=400&q=80" alt="Classic Leather Tote" />
        <div class="product-name">Classic Leather Tote</div>
        <div class="product-desc">Spacious and elegant, perfect for daily use.</div>
        <div class="product-price">$120.00</div>
        <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=YOUR_PAYPAL_EMAIL&item_name=Classic+Leather+Tote&amount=120.00&currency_code=USD" class="paypal-button" target="_blank" rel="noopener">Buy with PayPal</a>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1542834369-f10ebf06d3cb?auto=format&fit=crop&w=400&q=80" alt="Vintage Leather Backpack" />
        <div class="product-name">Vintage Leather Backpack</div>
        <div class="product-desc">Stylish and durable for your adventures.</div>
        <div class="product-price">$150.00</div>
        <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=YOUR_PAYPAL_EMAIL&item_name=Vintage+Leather+Backpack&amount=150.00&currency_code=USD" class="paypal-button" target="_blank" rel="noopener">Buy with PayPal</a>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1491553895911-0055eca6402d?auto=format&fit=crop&w=400&q=80" alt="Leather Crossbody Bag" />
        <div class="product-name">Leather Crossbody Bag</div>
        <div class="product-desc">Compact and perfect for hands-free convenience.</div>
        <div class="product-price">$95.00</div>
        <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=YOUR_PAYPAL_EMAIL&item_name=Leather+Crossbody+Bag&amount=95.00&currency_code=USD" class="paypal-button" target="_blank" rel="noopener">Buy with PayPal</a>
      </div>

    </section>
  </main>

  <footer>
    &copy; 2025 Leather Bags Store. All rights reserved.
  </footer>
</body>
</html>
