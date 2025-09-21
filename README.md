<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DROP Store</title>
  <style>
    /* GENERAL STYLES */
    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      background: linear-gradient(to bottom, #000000, #111111);
      color: #fff;
      text-align: center;
    }

    header {
      padding: 40px 20px;
      background: linear-gradient(90deg, #ff416c, #ff4b2b);
      border-bottom: 2px solid #222;
      box-shadow: 0 4px 20px rgba(255,255,255,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 48px;
      font-weight: 900;
      letter-spacing: 6px;
      background: linear-gradient(90deg, #ffffff, #ffd700);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    /* PRODUCTS SECTION */
    .products {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 35px;
      padding: 60px 20px;
    }

    .product {
      background: linear-gradient(145deg, #1a1a1a, #0d0d0d);
      border-radius: 20px;
      padding: 25px;
      width: 300px;
      text-align: center;
      box-shadow: 0 8px 25px rgba(255, 255, 255, 0.1);
      transition: transform 0.4s ease, box-shadow 0.4s ease;
    }

    .product:hover {
      transform: translateY(-12px);
      box-shadow: 0 15px 40px rgba(255, 215, 0, 0.3);
    }

    .product img {
      width: 100%;
      border-radius: 15px;
      margin-bottom: 15px;
      transition: transform 0.3s ease;
    }

    .product img:hover {
      transform: scale(1.05);
    }

    .limited {
      color: #ff6b6b;
      font-weight: bold;
      margin-bottom: 12px;
      font-size: 15px;
    }

    .soldout {
      color: #ff3333;
      font-size: 18px;
      font-weight: bold;
      margin: 15px 0;
    }

    .pay {
      margin-top: 15px;
      font-size: 15px;
      line-height: 1.6;
    }

    /* BUTTON STYLES */
    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 12px 25px;
      border-radius: 12px;
      font-weight: bold;
      text-decoration: none;
      transition: all 0.3s ease;
      box-shadow: 0 4px 15px rgba(255, 255, 255, 0.1);
    }

    .whatsapp-btn {
      background: linear-gradient(135deg, #25D366, #1ebe5b);
      color: #fff;
    }

    .whatsapp-btn:hover {
      background: linear-gradient(135deg, #1ebe5b, #17a34a);
      box-shadow: 0 6px 20px rgba(30, 190, 91, 0.4);
    }

    .pay-btn {
      background: linear-gradient(135deg, #007bff, #0056b3);
      color: #fff;
    }

    .pay-btn:hover {
      background: linear-gradient(135deg, #0056b3, #003f7f);
      box-shadow: 0 6px 20px rgba(0, 123, 255, 0.4);
    }

    /* FOOTER */
    footer {
      margin-top: 50px;
      padding: 25px 20px;
      font-size: 16px;
      background: #000;
      border-top: 1px solid #222;
      box-shadow: inset 0 4px 8px rgba(255,255,255,0.05);
    }

    /* RESPONSIVE */
    @media (max-width: 650px) {
      .product {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <h1>DROP</h1>
  </header>

  <!-- PRODUCTS -->
  <section class="products">

    <!-- PRODUCT 1 -->
    <div class="product">
      <img src="IMG-20250921-WA0001.jpg" alt="Black Mobile Cover for Redmi 13 Pro Plus">
      <div class="limited">🔥 LIMITED STOCK</div>
      <div class="pay">
        <a class="btn whatsapp-btn" href="https://wa.me/917668715335" target="_blank">💬 Chat on WhatsApp</a><br>
        <a class="btn pay-btn" href="upi://pay?pa=yourupiid@upi&pn=DROP%20Store" target="_blank">💳 Pay Now</a><br>
        Or choose <b>COD</b>
      </div>
    </div>

    <!-- PRODUCT 2 -->
    <div class="product">
      <img src="bluecover.jpg" alt="Blue Mobile Cover for Infinix Note 50X">
      <div class="soldout">🚫 SOLD OUT</div>
    </div>

  </section>

  <!-- FOOTER -->
  <footer>
    ✨ Thanks for shopping with us ✨
  </footer>

</body>
</html>
