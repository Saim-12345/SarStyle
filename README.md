
<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8" />

  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <title>SAR STYLE | Luxury Watches</title>

 

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

 

  <style>

    *{

      margin:0;

      padding:0;

      box-sizing:border-box;

      font-family:'Poppins',sans-serif;

    }

 

    body{

      background:#f9f6ef;

      color:#222;

    }

 

    header{

      display:flex;

      justify-content:space-between;

      align-items:center;

      padding:25px 8%;

      background:white;

      position:sticky;

      top:0;

      z-index:1000;

      box-shadow:0 2px 15px rgba(0,0,0,0.05);

    }

 

    .logo{

      font-size:32px;

      font-weight:700;

      color:#c8a95b;

      letter-spacing:2px;

    }

 

    nav a{

      margin-left:25px;

      text-decoration:none;

      color:#333;

      font-weight:500;

      transition:0.3s;

    }

 

    nav a:hover{

      color:#c8a95b;

    }

 

    .hero{

      min-height:90vh;

      display:flex;

      align-items:center;

      justify-content:center;

      text-align:center;

      padding:40px;

      background:linear-gradient(rgba(255,255,255,0.75),rgba(255,255,255,0.75)),

      url('https://images.unsplash.com/photo-1523170335258-f5ed11844a49?q=80&w=1400&auto=format&fit=crop') center/cover;

    }

 

    .hero-content{

      max-width:800px;

    }

 

    .hero h1{

      font-size:70px;

      color:#b8923f;

      margin-bottom:20px;

      line-height:1.1;

    }

 

    .hero p{

      font-size:20px;

      color:#444;

      margin-bottom:35px;

    }

 

    .btn{

      display:inline-block;

      padding:16px 40px;

      background:#c8a95b;

      color:white;

      text-decoration:none;

      border-radius:50px;

      font-weight:600;

      transition:0.3s;

    }

 

    .btn:hover{

      transform:translateY(-3px);

      background:#b8923f;

    }

 

    .section-title{

      text-align:center;

      font-size:42px;

      margin:80px 0 50px;

      color:#b8923f;

    }

 

    .products{

      display:grid;

      grid-template-columns:repeat(auto-fit,minmax(280px,1fr));

      gap:30px;

      padding:0 8% 80px;

    }

 

    .card{

      background:white;

      border-radius:25px;

      overflow:hidden;

      box-shadow:0 10px 30px rgba(0,0,0,0.08);

      transition:0.4s;

    }

 

    .card:hover{

      transform:translateY(-10px);

    }

 

    .card img{

      width:100%;

      height:320px;

      object-fit:cover;

    }

 

    .card-content{

      padding:25px;

      text-align:center;

    }

 

    .card-content h3{

      font-size:28px;

      margin-bottom:10px;

    }

 

    .price{

      color:#c8a95b;

      font-size:22px;

      font-weight:600;

      margin-bottom:20px;

    }

 

    .whatsapp-btn{

      display:inline-block;

      background:#25D366;

      color:white;

      padding:12px 30px;

      border-radius:40px;

      text-decoration:none;

      font-weight:600;

      transition:0.3s;

    }

 

    .whatsapp-btn:hover{

      opacity:0.9;

    }

 

    .about{

      padding:80px 10%;

      text-align:center;

      background:white;

    }

 

    .about p{

      max-width:850px;

      margin:auto;

      line-height:1.9;

      font-size:18px;

      color:#555;

    }

 

    footer{

      background:#111;

      color:#ccc;

      text-align:center;

      padding:30px;

    }

 

    footer h3{

      color:#c8a95b;

      margin-bottom:10px;

    }

 

    @media(max-width:768px){

 

      .hero h1{

        font-size:45px;

      }

 

      nav{

        display:none;

      }

 

      .section-title{

        font-size:34px;

      }

    }

  </style>

</head>

<body>

 

  <header>

    <div class="logo">SAR STYLE</div>

 

    <nav>

      <a href="#">Home</a>

      <a href="#">Collection</a>

      <a href="#">About</a>

      <a href="#">Contact</a>

    </nav>

  </header>

 

  <section class="hero">

 

    <div class="hero-content">

      <h1>Luxury Watches For Modern Style</h1>

 

      <p>

        Discover premium watches crafted with elegance,

        luxury, and timeless design.

      </p>

 

      <a href="#products" class="btn">Explore Collection</a>

    </div>

 

  </section>

 

  <h2 class="section-title" id="products">Featured Collection</h2>

 

  <section class="products">

 

    <div class="card">

      <img src="https://images.unsplash.com/photo-1547996160-81dfa63595aa?q=80&w=1200&auto=format&fit=crop">

 

      <div class="card-content">

        <h3>Royal Gold</h3>

        <div class="price">Rs. 7,999</div>

 

        <a class="whatsapp-btn"

        href="https://wa.me/923001234567">

        Order Now

        </a>

      </div>

    </div>

 

    <div class="card">

      <img src="https://images.unsplash.com/photo-1523170335258-f5ed11844a49?q=80&w=1200&auto=format&fit=crop">

 

      <div class="card-content">

        <h3>Classic Silver</h3>

        <div class="price">Rs. 5,499</div>

 

        <a class="whatsapp-btn"

        href="https://wa.me/923001234567">

        Order Now

        </a>

      </div>

    </div>

 

    <div class="card">

      <img src="https://images.unsplash.com/photo-1434056886845-dac89ffe9b56?q=80&w=1200&auto=format&fit=crop">

 

      <div class="card-content">

        <h3>Black Diamond</h3>

        <div class="price">Rs. 8,999</div>

 

        <a class="whatsapp-btn"

        href="https://wa.me/923001234567">

        Order Now

        </a>

      </div>

    </div>

 

  </section>

 

  <section class="about">

 

    <h2 class="section-title">Why SAR STYLE?</h2>

 

    <p>

      SAR STYLE brings luxury and elegance together with

      premium quality watches designed for modern fashion lovers.

      Our collection combines timeless craftsmanship with stylish

      trends to give you the perfect look for every occasion.

    </p>

 

  </section>

 

  <footer>

 

    <h3>SAR STYLE</h3>

 

    <p>Premium Luxury Watches</p>

 

    <p style="margin-top:10px;">

      WhatsApp: +92 300 1234567

    </p>

 

  </footer>

 

</body>

</html>
