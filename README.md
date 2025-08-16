<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Radha Flour Mill</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #e6d3a3; padding: 20px; text-align: center; }
    header h1 { margin: 0; color: #4b3621; }
    nav { background: #4b3621; padding: 10px; text-align: center; }
    nav a { color: #fff; text-decoration: none; margin: 0 15px; font-weight: bold; }
    section { padding: 40px; max-width: 1000px; margin: auto; }
    .hero { background: url('https://images.unsplash.com/photo-1560807707-8cc77767d783') no-repeat center/cover; 
            height: 400px; display: flex; justify-content: center; align-items: center; color: white; font-size: 2em; text-shadow: 2px 2px 5px #000; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { border: 1px solid #ddd; border-radius: 10px; overflow: hidden; box-shadow: 2px 2px 10px rgba(0,0,0,0.1); }
    .card img { width: 100%; height: 200px; object-fit: cover; }
    .card h3 { margin: 10px; }
    footer { background: #4b3621; color: white; text-align: center; padding: 15px; }
  </style>
</head>
<body>

  <header>
    <h1>Radha Flour Mill</h1>
    <p>Freshly Ground • Pure • Healthy</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="hero">
    <div>Welcome to Radha Flour Mill</div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Radha Flour Mill has been serving pure, fresh, and healthy flour to our community with trust and tradition. 
       Our focus is on quality and hygiene, ensuring every pack delivers freshness from the mill to your kitchen.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1606755962773-d324e3e9c9f5" alt="Wheat Flour">
        <h3>Wheat Flour (10kg)</h3>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1627328715728-7bcc1b5db87d" alt="Multigrain Flour">
        <h3>Multigrain Flour (5kg)</h3>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1590080875832-3d4a66e87c7e" alt="Besan Flour">
        <h3>Besan Flour (1kg)</h3>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><b>Proprietors:</b> Parvin Kumar & Rishabh Goel</p>
    <p><b>Address:</b> Village Malimajra, Mustafabad, District Yamunanagar, Haryana</p>
    <p><b>Phone:</b> +91-9467119739 | +91-8168090527</p>
    <p><b>Email:</b> radhaflourmill@gmail.com</p>
    <p><a href="https://wa.me/919467119739" target="_blank">Chat on WhatsApp (Parvin Kumar)</a></p>
    <p><a href="https://wa.me/918168090527" target="_blank">Chat on WhatsApp (Rishabh Goel)</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Radha Flour Mill | All Rights Reserved</p>
  </footer>

</body>
</html>
