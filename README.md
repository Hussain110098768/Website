<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>MySite</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="Bootstrap.html">MySite</a>

   <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#nav">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="nav">

      <ul class="navbar-nav me-auto">
        <li class="nav-item"><a class="nav-link active" href="Bootstrap.html">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="features.html">Features</a></li>
        <li class="nav-item"><a class="nav-link" href="price.html">Price</a></li>
        <li class="nav-item"><a class="nav-link" href="faqs.html">Contact</a></li>
      </ul>

      <form class="d-flex me-3">
        <input class="form-control me-2" type="search" placeholder="Search">
        <button class="btn btn-outline-light" type="submit">Search</button>
      </form>

      <button class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#loginModal">
        Login
      </button>

    </div>
  </div>
</nav>

<!-- CAROUSEL -->
<div id="carouselExample" class="carousel slide">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://images.unsplash.com/photo-1775401152739-662f585e4360?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwzMHx8fGVufDB8fHx8fA%3D%3D" class="d-block w-100" height="400">
    </div>
    <div class="carousel-item">
      <img src="https://images.unsplash.com/photo-1770041797744-59e295885e8b?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwyNnx8fGVufDB8fHx8fA%3D%3D" class="d-block w-100" height="400">
    </div>
    <div class="carousel-item">
      <img src="https://images.unsplash.com/photo-1770917279526-48e205f8ec9a?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwxNnx8fGVufDB8fHx8fA%3D%3D" class="d-block w-100" height="400">
    </div>

  </div>

  <button class="carousel-control-prev" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>

  <button class="carousel-control-next" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>

<!-- FEATURES -->
<div class="container my-5 text-center">
  <h2 class="mb-4">Our Features</h2>
  <div class="row g-4">
    <div class="col-md-4">
      <div class="p-4 border rounded shadow-sm">
        <h5>Fast</h5>
        <p>Quick loading website.</p>
      </div>
    </div>
    <div class="col-md-4">
      <div class="p-4 border rounded shadow-sm">
        <h5>Responsive</h5>
        <p>Works on all devices.</p>
      </div>
    </div>
    <div class="col-md-4">
      <div class="p-4 border rounded shadow-sm">
        <h5>Modern</h5>
        <p>Clean design.</p>
      </div>
    </div>

  </div>

  <a href="features.html" class="btn btn-outline-primary mt-4">View All Features</a>
</div>

<!-- CARDS -->
<div class="container my-5">
  <div class="row g-4">
    <div class="col-md-4">
      <div class="card shadow-sm">
        <img src="https://images.pexels.com/photos/37025262/pexels-photo-37025262.jpeg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Project One</h5>
          <p class="card-text">Simple project description.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shadow-sm">
        <img src="https://images.pexels.com/photos/36397105/pexels-photo-36397105.jpeg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Project Two</h5>
          <p class="card-text">Another project.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shadow-sm">
        <img src="https://images.pexels.com/photos/36397105/pexels-photo-36397105.jpeg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Project Three</h5>
          <p class="card-text">More details.</p>
        </div>
      </div>
    </div>

  </div>
</div>

 <!-- CONTACT -->
<div class="container text-center my-5">
  <h2>Contact Us</h2>
  <p>Have questions? Reach out to us.</p>
  <a href="faqs.html" class="btn btn-primary">Contact</a>
  <a href="price.html" class="btn btn-outline-primary ms-2">Price</a>
</div>

<!-- LOGIN -->
<div class="modal fade" id="loginModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Login</h5>
        <button class="btn-close" data-bs-dismiss="modal"></button>
      </div>
      <div class="modal-body">
        <input type="email" class="form-control mb-3" placeholder="Email">
        <input type="password" class="form-control mb-3" placeholder="Password">
        <button class="btn btn-primary w-100">Login</button>
      </div>
    </div>
  </div>
</div>

<!-- FOOTER -->
<footer class="bg-dark text-white text-center py-3">
  © 2026 All Rights Reserved
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
