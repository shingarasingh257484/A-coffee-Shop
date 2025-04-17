# A-coffee-Shop
A coffee shop where we can see the variety of coffee
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Coffee Shop</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f8f1e4;
      color: #4e342e;
    }
    header {
      background-color: #3e2723;
      padding: 1rem 0;
      color: white;
    }
    .navbar-brand {
      font-weight: bold;
      font-size: 1.5rem;
    }
    .menu-item {
      text-align: center;
    }
    .menu-item img {
      width: 100%;
      max-height: 200px;
      object-fit: cover;
    }
    .testimonial {
      background-color: #fff3e0;
      padding: 1rem;
      border-radius: 10px;
      margin-bottom: 1rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      margin-bottom: 1rem;
    }
    header{
      display: flex; 
      align-items: center; 
      justify-content: space-between; 
      background-color: #4b2e2e; 
      color: #fff; 
      padding: 60px 40px;
    }
    h1{
      font-size: 2.8rem; 
      font-weight: bold;

    }
    
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #fff5f2; padding: 20px 40px;">
    <div class="container-fluid">
      <a class="navbar-brand" href="#" style="font-weight: bold; font-size: 1.8rem;">Coffee</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#Home" style="position: relative;">
              Home
              <span style="position:absolute; bottom: -5px; left: 0; width: 100%; height: 2px; background-color: #f25022;"></span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About US</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#menu">Menu</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Testimonials">Testimonials</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Gallery">Gallery</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  

  <header id="Home">
    <div style="flex: 1; padding-right: 40px;">
      <h1>Exceptional Coffee</h1>
      <p style="font-size: 1.4rem; margin: 10px 0;">Where Every Cup Tells a Story</p>
      <p style="font-size: 1rem; color: #ddd; max-width: 400px;">
        Our coffee is brewed to perfection, giving you a tap of love in every cup.
      </p>
      <a href="#order" class="btn btn-light" >Order Now</a>
    </div>
    <div style="flex: 1; text-align: center;">
      <img src="Home.png" alt="Coffee Cup" style="max-width: 100%; height: auto; border-radius: 10px;">
    </div>
  </header>
  

  <section class="container my-5" id="about">
    <div class="row align-items-center">
      <div class="col-md-6">
        <img src="about.png" alt="Coffee Shop Interior" class="img-fluid rounded">
      </div>
      <div class="col-md-6">
        <h2>About Us</h2>
        <p>We believe in the power of a perfect brew. From hand-selected beans to artfully prepared drinks, every cup is a labor of love.</p>
      </div>
    </div>
  </section>

  <section class="container my-5" id="menu">
    <h2 class="text-center mb-4">Our Menu</h2>
    <div class="row">
      <div class="col-md-3 menu-item">
        <img src="Espresso.png" alt="Espresso">
        <h5>Espresso</h5>
        <p>$5.00</p>
        <button class="btn btn-outline-dark">Order Now</button>
      </div>
      <div class="col-md-3 menu-item">
        <img src="Cappuccino.png" alt="Cappuccino">
        <h5>Cappuccino</h5>
        <p>$5.00</p>
        <button class="btn btn-outline-dark">Order Now</button>
      </div>
      <div class="col-md-3 menu-item">
        <img src="Latte.png" alt="Latte">
        <h5>Latte</h5>
        <p>$5.00</p>
        <button class="btn btn-outline-dark">Order Now</button>
      </div>
      <div class="col-md-3 menu-item">
        <img src="Americano.png" alt="Americano">
        <h5>Americano</h5>
        <p>$5.00</p>
        <button class="btn btn-outline-dark">Order Now</button>
      </div>
    </div>
  </section>
  <section class="container my-5" id="Testimonials">
    <h2 class="text-center mb-4">Testimonials</h2>
    <div class="row text-center">
      <div class="col-md-4">
        <div class="testimonial">
          <img src="p1.png" alt="Hayley Phillips" class="rounded-circle mb-2" width="80" height="80">
          <p>"Amazing coffee, cozy vibe, and friendly staff!"</p>
          <strong>Hayley Phillips</strong>
        </div>
      </div>
      <div class="col-md-4">
        <div class="testimonial">
          <img src="p2.png" alt="Walter Walker" class="rounded-circle mb-2" width="80" height="80">
          <p>"My go-to spot for coffee and quiet mornings."</p>
          <strong>Walter Walker</strong>
        </div>
      </div>
      <div class="col-md-4">
        <div class="testimonial">
          <img src="p3.png" alt="Kalflyn Garcia" class="rounded-circle mb-2" width="80" height="80">
          <p>"Incredible selection of drinks. Highly recommended."</p>
          <strong>Kalflyn Garcia</strong>
        </div>
      </div>
    </div>
  </section>
  

  <section class="container my-5 gallery" id="Gallery">
    <h2 class="text-center mb-4">Gallery</h2>
    <div class="row">
      <div class="col-md-4">
        <img src="g1.png" alt="Coffee Image">
      </div>
      <div class="col-md-4">
        <img src="g2.png" alt="Cafe Image">
      </div>
      <div class="col-md-4">
        <img src="g3.png" alt="Barista Image">
      </div>
    </div>
  </section>
  <section class="container my-5" id="order">
    <h2 class="text-center mb-4">Place Your Order</h2>
    <form class="mx-auto" style="max-width: 500px;">
      <div class="mb-3">
        <label for="name" class="form-label">Your Name:</label>
        <input type="text" class="form-control" id="name" name="name" required>
      </div>
  
      <div class="mb-3">
        <label for="drink" class="form-label">Drink:</label>
        <input type="text" class="form-control" id="drink" name="drink" required>
      </div>
  
      <div class="mb-3">
        <label for="size" class="form-label">Size:</label>
        <select class="form-select" id="size" name="size" required>
          <option value="">Select size</option>
          <option value="Small">Small</option>
          <option value="Medium">Medium</option>
          <option value="Large">Large</option>
        </select>
      </div>
  
      <div class="mb-3">
        <label for="notes" class="form-label">Notes (optional):</label>
        <textarea class="form-control" id="notes" name="notes" rows="4"></textarea>
      </div>
  
      <button type="submit" class="btn btn-dark w-100">Submit Order</button>
    </form>
  </section>

  <footer class="text-center py-3 bg-dark text-white">
    <p>&copy; 2025 Coffee Shop. All rights reserved.</p>
  </footer>
  
  
</body>
</html>
