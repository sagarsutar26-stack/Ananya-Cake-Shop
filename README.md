# Ananya-Cake-Shop
Delicious, Chocklet, Strawberry, pineapple, butter scotch -  for birthday-Wedding ceremoy
AnanyaCakeShop/
│── index.html
│── cake.jpg   (your uploaded cake image)
AnanyaCakeShop/
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ananya Cake Shop</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#fff8f0;
    color:#333;
}

/* Header */
header{
    background:#7B241C;
    color:white;
    text-align:center;
    padding:20px;
}

header h1{
    font-size:42px;
}

header p{
    margin-top:8px;
}

/* Navigation */
nav{
    background:#C0392B;
    text-align:center;
    padding:15px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 18px;
    font-size:18px;
    font-weight:bold;
}

nav a:hover{
    color:#FFD700;
}

/* Hero Section */
.hero{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    align-items:center;
    padding:50px;
    background:#FFF3E0;
}

.hero-text{
    flex:1;
    min-width:300px;
    padding:20px;
}

.hero-text h2{
    font-size:42px;
    color:#7B241C;
}

.hero-text p{
    margin-top:20px;
    font-size:18px;
    line-height:30px;
}

.hero-text a{
    display:inline-block;
    margin-top:25px;
    padding:14px 28px;
    background:#C0392B;
    color:white;
    text-decoration:none;
    border-radius:30px;
    transition:.3s;
}

.hero-text a:hover{
    background:#7B241C;
}

.hero-image{
    flex:1;
    text-align:center;
}

.hero-image img{
    width:90%;
    max-width:450px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,.3);
}

/* Cakes */
.section{
    padding:60px 20px;
    text-align:center;
}

.section h2{
    color:#7B241C;
    margin-bottom:40px;
}

.cards{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:25px;
}

.card{
    width:300px;
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,.2);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card h3{
    color:#7B241C;
    margin:15px;
}

.card p{
    padding:0 15px 20px;
}

/* Contact */
.contact{
    background:#7B241C;
    color:white;
    text-align:center;
    padding:50px 20px;
}

.contact h2{
    margin-bottom:20px;
}

.contact p{
    margin:10px;
    font-size:18px;
}

/* Footer */
footer{
    background:#4A1510;
    color:white;
    text-align:center;
    padding:15px;
}

@media(max-width:768px){

.hero{
    flex-direction:column;
}

.hero-text h2{
    font-size:32px;
}

nav a{
    display:block;
    margin:10px 0;
}

}
</style>
</head>

<body>

<header>
<h1>🎂 Ananya Cake Shop</h1>
<p>Fresh • Delicious • Made With Love</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Our Cakes</a>
<a href="#">Gallery</a>
<a href="#">Contact</a>
</nav>

<section class="hero">

<div class="hero-text">
<h2>Celebrate Every Moment With Sweetness</h2>

<p>
From birthdays and anniversaries to weddings and special occasions,
Ananya Cake Shop prepares freshly baked cakes with premium ingredients
and beautiful custom designs.
</p>

<a href="#">Order Your Cake</a>

</div>

<div class="hero-image">
<img src="cake.jpg" alt="White Chocolate Cake">
</div>

</section>

<section class="section">

<h2>Our Special Cakes</h2>

<div class="cards">

<div class="card">
<img src="cake.jpg">
<h3>White Chocolate Cake</h3>
<p>Soft sponge layered with creamy white chocolate and elegant decoration.</p>
</div>

<div class="card">
<img src="cake.jpg">
<h3>Fruit Celebration Cake</h3>
<p>Fresh seasonal fruits blended with delicious whipped cream.</p>
</div>

<div class="card">
<img src="cake.jpg">
<h3>Custom Party Cake</h3>
<p>Perfect for birthdays, weddings and memorable celebrations.</p>
</div>

</div>

</section>

<section class="contact">

<h2>Contact Us</h2>

<p><strong>Ananya Cake Shop</strong></p>

<p>📍 Sai Mandir, Main Road, Unchgaon</p>

<p>📞 +91 9284485735</p>

<p>📧 ananyacakeshop@gmail.com</p>

<p>🕘 Open Daily: 9:00 AM – 9:00 PM</p>

</section>

<footer>

<p>© 2026 Ananya Cake Shop | Designed with ❤️</p>

</footer>

</body>
</html>
