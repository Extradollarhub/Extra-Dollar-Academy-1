# Extra-Dollar-Academy-1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ecommerce Website</title>

  <link rel="stylesheet" href="style.css" />

  <script
    src="https://kit.fontawesome.com/0e53af926d.js"
    crossorigin="anonymous">
  </script>
</head>

<body>

<!-- HEADER -->
<header id="header">
  <div class="header-logo">
    <a href="index.html">
      <img src="images/logo.png" alt="Logo">
    </a>
  </div>

  <nav class="header-list-nav">
    <ul>
      <li><a class="active" href="index.html">Home</a></li>
      <li><a href="#">Shop</a></li>
      <li><a href="#">Blog</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <div class="header-list-icon">
    <a href="#"><i class="fa fa-bag-shopping"></i></a>
  </div>
</header>

<!-- HERO -->
<section id="hero">
  <h4>Trade-in-offer</h4>
  <h2>Super value deals</h2>
  <h1>On all products</h1>
  <p>Save more with coupons & up to 70% off!</p>
  <button>Shop Now</button>
</section>

<!-- FEATURES -->
<section id="features" class="section-p1">
  <div class="f-box"><h6>Free Shipping</h6></div>
  <div class="f-box"><h6>Online Order</h6></div>
  <div class="f-box"><h6>Save Money</h6></div>
  <div class="f-box"><h6>Promotions</h6></div>
  <div class="f-box"><h6>Happy Sell</h6></div>
  <div class="f-box"><h6>24/7 Support</h6></div>
</section>

<!-- PRODUCTS -->
<section class="product-section section-p1">
  <h1>Featured Products</h1>
  <p>Summer Collection New Modern Design</p>

  <div class="pro-collection">
    <div class="product-cart">
      <img src="images/products/f1.jpg" alt="">
      <h4>T-Shirt</h4>
      <h4 class="price">$78</h4>
      <i class="fa-solid fa-cart-shopping buy-icon"></i>
    </div>
  </div>
</section>

<!-- NEWSLETTER -->
<section id="newsletter">
  <h3>Sign Up For Newsletters</h3>
  <input type="email" placeholder="Your email">
  <button>Sign Up</button>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2025 Your Store. All rights reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #f5f5f5;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 30px;
  background: #222;
  color: white;
}

header a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
}

#hero {
  text-align: center;
  padding: 60px 20px;
  background: #e3e6f3;
}

button {
  padding: 10px 20px;
  border: none;
  background: black;
  color: white;
  cursor: pointer;
}

.product-cart {
  background: white;
  padding: 15px;
  margin: 15px;
  display: inline-block;
}
