<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Farsan Shop - Delicious Snacks</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: #fff8f0;
      color: #4b2e05;
      line-height: 1.6;
    }

    header {
      background: #d97e00;
      padding: 20px 40px;
      text-align: center;
      color: white;
      font-size: 2rem;
      font-weight: bold;
      letter-spacing: 2px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1602537277812-5caa70a17f9b?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      text-shadow: 2px 2px 6px #000;
      font-size: 2.5rem;
      font-weight: 700;
      text-align: center;
      padding: 0 20px;
    }

    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
      font-weight: 700;
      letter-spacing: 1px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
      gap: 20px;
    }

    .product-card {
      background: #fff3e6;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s ease;
    }

    .product-card:hover {
      transform: scale(1.05);
    }

    .product-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    .product-card h3 {
      margin-bottom: 10px;
      font-size: 1.2rem;
      color: #9c5b00;
    }

    .product-card p {
      font-size: 1rem;
      margin-bottom: 10px;
      color: #6e4b03;
    }

    .product-card .price {
      font-weight: 700;
      font-size: 1.1rem;
      color: #d97e00;
    }

    footer {
      background: #d97e00;
      text-align: center;
      padding: 15px 20px;
      color: white;
      margin-top: 40px;
      font-size: 0.9rem;
      letter-spacing: 0.5px;
    }

    @media (max-width: 600px) {
      .hero {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>

  <header>
    Farsan Shop
  </header>

  <section class="hero">
    Taste the Best Traditional Snacks!
  </section>

  <div class="container">
    <h2>Our Featured Farsan</h2>
    <div class="products">
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1590080877777-2d422f6b3509?auto=format&fit=crop&w=400&q=80" alt="Bhujia" />
        <h3>Bhujia</h3>
        <p>Crispy and spicy gram flour noodles.</p>
        <div class="price">₹120 / 250g</div>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1610217461832-3fa4d9f233e4?auto=format&fit=crop&w=400&q=80" alt="Chakli" />
        <h3>Chakli</h3>
        <p>Spiral shaped crunchy snack made from rice flour.</p>
        <div class="price">₹150 / 300g</div>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1614696007201-cb3b7553b13d?auto=format&fit=crop&w=400&q=80" alt="Fafda" />
        <h3>Fafda</h3>
        <p>Golden fried gram flour strips, a Gujarati favorite.</p>
        <div class="price">₹130 / 250g</div>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1600872282271-6c3f38df47de?auto=format&fit=crop&w=400&q=80" alt="Sev" />
        <h3>Sev</h3>
        <p>Thin and crunchy noodles with spicy flavor.</p>
        <div class="price">₹110 / 200g</div>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 Farsan Shop. All rights reserved.
  </footer>

</body>
</html>

