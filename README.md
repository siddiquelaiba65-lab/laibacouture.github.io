# laibacouture.github.i
<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Laiba Couture | Trendy Clothing Brand</title>
  <style>
    body {font-family: system-ui, sans-serif; margin: 0; background: #fff; color: #222;}
    header {background: black; color: white; text-align: center; padding: 1rem;}
    nav a {color: white; margin: 0 15px; text-decoration: none; font-weight: bold;}
    section {padding: 2rem; text-align: center;}
    .hero {background: url('https://i.ibb.co/3hmFF3L/fashion-bg.jpg') center/cover no-repeat; color: white; padding: 100px 20px;}
    .hero h1 {font-size: 2.5rem; margin-bottom: .5rem;}
    .hero p {font-size: 1.2rem;}
    .btn {background: white; color: black; padding: 10px 20px; border-radius: 5px; text-decoration: none; font-weight: bold;}
    .collection {display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-top: 2rem;}
    .item {border: 1px solid #eee; border-radius: 10px; width: 250px; padding: 1rem;}
    .item img {width: 100%; border-radius: 10px;}
    footer {background: black; color: white; padding: 1rem; text-align: center;}
  </style>
</head>
<body>
  <header>
    <h1>Laiba Couture</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#collection">Collection</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>New Winter Collection 2025</h1>
    <p>Stylish • Elegant • Affordable</p>
    <a href="#collection" class="btn">Shop Now</a>
  </section>

  <section id="collection">
    <h2>Our Collection</h2>
    <div class="collection">
      <div class="item">
        <img src="https://i.ibb.co/s3sGzYw/dress1.jpg" alt="Dress">
        <p>Silk Kurti — Rs. 3500</p>
      </div>
      <div class="item">
        <img src="https://i.ibb.co/ZHhsWWV/dress2.jpg" alt="Dress">
        <p>Luxury Lawn — Rs. 4500</p>
      </div>
      <div class="item">
        <img src="https://i.ibb.co/F5mDKZT/dress3.jpg" alt="Dress">
        <p>Winter Shawl — Rs. 2800</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Laiba Couture ek modern Pakistani clothing brand hai jo style aur comfort dono ka perfect blend hai.  
    Har piece carefully designed hota hai taake aap har occasion par khubsurat lagen.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: laibacouture@gmail.com</p>
    <p>Instagram: <a href="#" target="_blank">@laibacouture</a></p>
  </section>

  <footer>
    © 2025 Laiba Couture | All Rights Reserved
  </footer>
</body>
</html>
git init
git add .
git commit -m "Initial clothing brand site"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
