# fulida
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Fulida | Leading Electric Bicycle Manufacturer in China</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="Fulida is a trusted OEM/ODM electric bicycle & scooter manufacturer in China, exporting to Europe, North America, Israel with CE/TÜV/ROHS certified e-bikes.">
<style>
:root{
  --primary:#ff6600;
  --dark:#222;
  --light:#fff;
  --gray:#f5f5f5;
  --max:1100px;
  --radius:6px;
}
*{margin:0;padding:0;box-sizing:border-box;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif;}
body{line-height:1.6;color:#333;}
a{text-decoration:none;color:inherit;}
img{max-width:100%;display:block;}
header{
  background:var(--light);
  box-shadow:0 2px 6px rgba(0,0,0,.05);
  position:sticky;top:0;z-index:999;
}
nav{
  max-width:var(--max);
  margin:auto;
  display:flex;align-items:center;justify-content:space-between;padding:15px 20px;
}
nav .logo{
  font-size:24px;font-weight:700;color:var(--primary);
}
nav ul{
  list-style:none;display:flex;gap:25px;
}
nav ul li a:hover{color:var(--primary);}
.hero{
  background:linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),url('https://images.unsplash.com/photo-1558618666-fcd25c85cd64?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
  color:var(--light);text-align:center;padding:120px 20px;
}
.hero h1{font-size:42px;margin-bottom:15px;}
.hero p{font-size:18px;max-width:700px;margin:auto auto 30px;}
.btn{
  background:var(--primary);color:var(--light);padding:12px 30px;border-radius:var(--radius);display:inline-block;font-weight:600;transition:.3s;
}
.btn:hover{background:#e55b00;}
.section{padding:70px 20px;}
.container{max-width:var(--max);margin:auto;}
.grid{
  display:grid;gap:30px;
}
.grid-2{grid-template-columns:repeat(auto-fit,minmax(280px,1fr));}
.grid-3{grid-template-columns:repeat(auto-fit,minmax(250px,1fr));}
.center{text-align:center;}
.card{
  background:var(--gray);border-radius:var(--radius);overflow:hidden;box-shadow:0 2px 8px rgba(0,0,0,.05);
}
.card img{height:200px;object-fit:cover;}
.card-body{padding:20px;}
footer{
  background:var(--dark);color:#ccc;text-align:center;padding:40px 20px;font-size:14px;
}
footer a{color:var(--primary);}
@media(max-width:768px){
  nav ul{flex-direction:column;gap:10px;}
  .hero h1{font-size:32px;}
}
</style>
</head>
<body>

<header>
  <nav>
    <div class="logo>Fulida</div>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#products">Products</a></li>
      <li><a href="#cert">Certifications</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<section id="home" class="hero">
  <h1>Leading Electric Bicycle Manufacturer in China</h1>
  <p>Fulida specializes in premium OEM/ODM electric bicycles & scooters, trusted by 200+ overseas clients across Europe, North America and Israel.</p>
  <a href="#contact" class="btn">Request a Quote</a>
</section>

<section id="about" class="section">
  <div class="container">
    <h2 class="center">About Fulida</h2>
    <div class="grid grid-2" style="margin-top:40px;align-items:center;">
      <div>
        <p>Founded in 2017, Fulida has grown into a reliable partner for global e-mobility brands. Our 150+ skilled employees operate within a 18,000 m² factory equipped with automatic frame welding, phosphating & powder-coating lines, delivering 300,000+ vehicles annually.</p>
        <ul style="margin-top:20px;padding-left:20px;">
          <li>7 years focused on e-bikes & e-scooters</li>
          <li>Export to 35+ countries</li>
          <li>ISO 9001 & ISO 14001 certified management</li>
          <li>In-house RD, 15 engineers, 72-hour prototype</li>
        </ul>
      </div>
      <div><img src="https://images.unsplash.com/photo-1583795128727-6ec3642408f8?auto=format&fit=crop&w=800&q=80" alt="Factory"></div>
    </div>
  </div>
</section>

<section id="products" class="section" style="background:var(--gray);">
  <div class="container">
    <h2 class="center">Our Products</h2>
    <div class="grid grid-3" style="margin-top:40px;">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?auto=format&fit=crop&w=800&q=80" alt="E-Bike">
        <div class="card-body">
          <h3>Electric Bicycles</h3>
          <p>City, trekking, fat-tire, folding and cargo models with 250-750W motor options, EN 15194 approved.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1607793722733-9c9d2ce5a1b2?auto=format&fit=crop&w=800&q=80" alt="E-Scooter">
        <div class="card-body">
          <h3>Electric Scooters</h3>
          <p>10-14 inch tire, 36-60V, removable battery design, perfect for sharing or retail fleets.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1580927752452-89d86da3fa0a?auto=format&fit=crop&w=800&q=80" alt="ODM">
        <div class="card-body">
          <h3>ODM / OEM</h3>
          <p>From sketch to mass production in 45 days, custom frame painting, app connectivity, retail packaging.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="cert" class="section">
  <div class="container">
    <h2 class="center">Certifications</h2>
    <p class="center" style="max-width:700px;margin:15px auto 40px;">All Fulida e-bikes for the EU market are tested by accredited laboratories. We hold valid CE, RoHS, TÜV Nord & TÜV Rheinland reports.</p>
    <div class="grid grid-3">
      <div class="card center"><div class="card-body"><h4>CE</h4><p>2006/42/EC &amp; 2014/30/EU</p></div></div>
      <div class="card center"><div class="card-body"><h4>RoHS</h4><p>2011/65/EU &amp; 2015/863</p></div></div>
      <div class="card center"><div class="card-body"><h4>TÜV</h4><p>EN 15194:2017 &amp; ISO 4210</p></div></div>
    </div>
  </div>
</section>

<section id="contact" class="section" style="background:var(--gray);">
  <div class="container center">
    <h2>Contact Us</h2>
    <p style="margin:15px auto 30px;max-width:500px;">Looking for a reliable e-bike partner? Send your inquiry and receive a quotation with 24-hour technical datasheet.</p>
    <p><strong>Email:</strong> <a href="mailto:info@fulida-ebike.com">info@fulida-ebike.com</a><br>
       <strong>Phone:</strong> <a href="tel:+8657187654321">+86 571 8765 4321</a><br>
       <strong>Address:</strong> No. 88 Fulida Road, Hangzhou, Zhejiang, China 310000</p>
    <a href="mailto:info@fulida-ebike.com" class="btn">Send Inquiry</a>
  </div>
</section>

<footer>
  © 2025 Fulida Tech Co., Ltd. All rights reserved. | <a href="mailto:info@fulida-ebike.com">info@fulida-ebike.com</a>
</footer>

<script>
// 平滑滚动
document.querySelectorAll('a[href^="#"]').forEach(anchor=>{
  anchor.addEventListener('click',function(e){
    e.preventDefault();
    document.querySelector(this.getAttribute('href')).scrollIntoView({behavior:'smooth'});
  });
});
</script>
</body>
</html>
```
