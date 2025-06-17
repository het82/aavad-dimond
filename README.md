# aavad-dimond
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aavad Diamond Grooving</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background-color: #222;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background-image: url('your-main-diamond-banner.jpg');
      background-size: cover;
      background-position: center;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2rem;
      font-weight: bold;
      text-shadow: 2px 2px 5px #000;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: white;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .product img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Aavad Diamond Grooving</h1>
    <p>Crafting Artistic Diamond Shapes with Precision</p>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#shapes">Custom Shapes</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    Unique Diamond Shapes Like Never Before
  </div>

  <section id="products" class="section">
    <h2>Our Diamond Products</h2>
    <div class="products">
      <div class="product">
        <img src="diamond1.jpg" alt="Diamond Product 1" />
        <p>Classic Diamond</p>
      </div>
      <div class="product">
        <img src="diamond2.jpg" alt="Diamond Product 2" />
        <p>Heart Shape Diamond</p>
      </div>
      <div class="product">
        <img src="diamond3.jpg" alt="Diamond Product 3" />
        <p>Fish Shape Diamond</p>
      </div>
    </div>
  </section>

  <section id="shapes" class="section">
    <h2>Custom Diamond Shapes</h2>
    <p>We create stunning diamond shapes like Horse, Deer, Heart, Fish, A to Z Alphabets, and many more as per your custom needs.</p>
    <img src="custom-shapes.jpg" alt="Custom Diamond Shapes" style="max-width: 90%; border-radius: 10px; margin-top: 20px;">
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>Aavad Diamond Grooving is known for precision-crafted diamond artwork. We specialize in unique grooving and custom shapes that make your diamond truly special.</p>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: info@aavaddiamond.com<br>Phone: +91-XXXXXXXXXX<br>Address: Surat, Gujarat, India</p>
    <h3>How to View This Website on GitHub</h3>
    <ol style="text-align:left; max-width:600px; margin:20px auto;">
      <li>After you create your repository and upload the <code>index.html</code> file, go to the repository homepage.</li>
      <li>Click the <strong>Settings</strong> tab.</li>
      <li>Scroll down to the <strong>Pages</strong> section on the left menu.</li>
      <li>Under "Deploy from a branch", choose:
        <ul>
          <li><strong>Branch</strong>: <code>main</code></li>
          <li><strong>Folder</strong>: <code>/ (root)</code></li>
        </ul>
      </li>
      <li>Click <strong>Save</strong>.</li>
      <li>Wait 1–2 minutes. GitHub will give you a link at the top like:
        <br><code>https://yourusername.github.io/aavad-diamond</code>
      </li>
      <li>Click the link to view your live website.</li>
    </ol>
  </section>

  <footer>
    &copy; 2025 Aavad Diamond Grooving. All rights reserved.
  </footer>
</body>
</html>
