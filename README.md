# Dr-Hassan's 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dr Hassens</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="logo.png" alt="Dr Hassens logo">
    <nav> 
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <section class="hero">
    <h1>Your source for quality vitamin supplements</h1>
    <p>Natural, effective, and easy to use once a day</p>
    <a href="products.html" class="btn">Shop Now</a>
  </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Products – Dr Hassens</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="logo.png" alt="Dr Hassens logo">
    <nav>
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <h1>Our Supplements</h1>
  <!-- Cod Liver Oil -->
  <div class="product">
    <img src="cod-liver.jpg" alt="Cod Liver Oil">
    <div class="product-details">
      <h2>Cod Liver Oil – 285 mg • 60 Capsules</h2>
      <p>High-quality, natural cod liver oil rich in vitamins A & D.<br>
         <strong>Soft capsule dietary supplement</strong></p>
      <div class="actions">
        <select id="cod-sub" name="subscription">
          <option value="one">One‑time purchase</option>
          <option value="month">Subscribe monthly</option>
        </select>
        <button onclick="addToCart('Cod Liver Oil', document.getElementById('cod-sub').value)">Add to Cart</button>
      </div>
    </div>
  </div>
  <!-- E Cap -->
  <div class="product">
    <img src="e-cap.jpg" alt="E Cap">
    <div class="product-details">
      <h2>E-Cap 600 – 600 IU • 30 Capsules</h2>
      <p>Vitamin E soft capsules for antioxidant protection.<br>
         Manufactured by Drug International Ltd.</p>
      <div class="actions">
        <select id="e-sub" name="subscription">
          <option value="one">One‑time purchase</option>
          <option value="month">Subscribe monthly</option>
        </select>
        <button onclick="addToCart('E Cap', document.getElementById('e-sub').value)">Add to Cart</button>
      </div>
    </div>
  </div>
  <!-- B Complex Plus Mineral -->
  <div class="product">
    <img src="b-complex.jpg" alt="B Complex Plus Mineral">
    <div class="product-details">
      <h2>B-Complex Plus Mineral – 30 Capsules</h2>
      <p>Soft capsule dietary supplement for balanced B vitamins and minerals.<br>
         Manufactured by Drug International Ltd.</p>
      <div class="actions">
        <select id="b-sub" name="subscription">
          <option value="one">One‑time purchase</option>
          <option value="month">Subscribe monthly</option>
        </select>
        <button onclick="addToCart('B-Complex Plus Mineral', document.getElementById('b-sub').value)">Add to Cart</button>
      </div>
    </div>
  </div>
  <!-- Calcium Plus Vitamin D -->
  <div class="product">
    <img src="calcium.jpg" alt="Calcium Plus Vitamin D">
    <div class="product-details">
      <h2>Calcium Plus Vitamin D – 1500 mg • 30 Capsules</h2>
      <p>Calcium carbonate with Vitamin D3 for bone strength and active lifestyle.<br>
         Soft capsule dietary supplement.</p>
      <div class="actions">
        <select id="calcium-sub" name="subscription">
          <option value="one">One‑time purchase</option>
          <option value="month">Subscribe monthly</option>
        </select>
        <button onclick="addToCart('Calcium Plus Vitamin D', document.getElementById('calcium-sub').value)">Add to Cart</button>
      </div>
    </div>
  </div>
  <!-- Magnesium Plus Vitamin -->
  <div class="product">
    <img src="magnesium.jpg" alt="Magnesium Plus Vitamin">
    <div class="product-details">
      <h2>Magnesium Plus Vitamin – 30 Capsules</h2>
      <p>Magnesium oxide soft capsules with multi-vitamins (B5, E, B2, B1, B3, A).<br>
         Supports muscle function, relaxation, and overall well-being.</p>
      <div class="actions">
        <select id="magnesium-sub" name="subscription">
          <option value="one">One‑time purchase</option>
          <option value="month">Subscribe monthly</option>
        </select>
        <button onclick="addToCart('Magnesium Plus Vitamin', document.getElementById('magnesium-sub').value)">Add to Cart</button>
      </div>
    </div>
  </div>
  <script>
    function addToCart(name, sub) {
      alert(`Added ${name} (${sub}) to cart!`);
      // Replace with real cart logic.
    }
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About – Dr Hassens</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="logo.png" alt="Dr Hassens logo">
    <nav>
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <section class="about">
    <h1>About Dr Hassens</h1>
    <p>Dr Hassens is dedicated to providing high-quality, natural vitamin supplements to support your well-being. Our products are formulated with care and scientific expertise to ensure you get the best nutrition for your health.</p>
    <p>We believe in transparency, quality, and making wellness accessible and easy for everyone.</p>
  </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact – Dr Hassens</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="logo.png" alt="Dr Hassens logo">
    <nav>
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <section class="contact">
    <h1>Contact Us</h1>
    <form class="contact-form">
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name" required><br>
      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email" required><br>
      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5" required></textarea><br>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </section>
  <script>
    document.querySelector('.contact-form').onsubmit = function(e) {
      e.preventDefault();
      alert("Thank you for contacting us!");
      this.reset();
    };
  </script>
</body>
</html>
