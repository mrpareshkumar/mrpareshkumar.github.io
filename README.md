<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Urban Bites Restaurant</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
}

/* Navbar */
nav {
  display: flex;
  justify-content: space-between;
  padding: 15px 50px;
  background: rgba(0,0,0,0.8);
  color: white;
  position: fixed;
  width: 100%;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

/* Hero */
.hero {
  height: 100vh;
  background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092') center/cover;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
}

.hero h1 {
  font-size: 55px;
}

.btn {
  background: orange;
  padding: 12px 25px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
}

/* Section */
.section {
  padding: 80px 20px;
  text-align: center;
}

/* Menu */
.menu {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: #fff;
  padding: 20px;
  border-radius: 10px;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

/* Gallery */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}

.gallery img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

/* Contact */
.contact {
  background: #111;
  color: white;
  padding: 50px;
}

/* WhatsApp */
.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: green;
  color: white;
  padding: 15px;
  border-radius: 50%;
  text-decoration: none;
  font-size: 20px;
}
</style>
</head>

<body>

<nav>
  <h2>Urban Bites</h2>
  <div>
    <a href="#">Home</a>
    <a href="#menu">Menu</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<div class="hero">
  <h1>Delicious Moments</h1>
  <p>Experience the taste of premium food</p>
  <a href="#menu" class="btn">Explore Menu</a>
</div>

<div class="section" id="menu">
  <h2>Our Menu</h2>
  <div class="menu">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1604908176997-43142c48a3c7">
      <h3>Chicken Burger</h3>
      <p>₹199</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c">
      <h3>Veg Salad</h3>
      <p>₹149</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
      <h3>Pizza</h3>
      <p>₹299</p>
    </div>
  </div>
</div>

<div class="section" id="gallery">
  <h2>Gallery</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1555992336-03a23c7b20ee">
    <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5">
    <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092">
  </div>
</div>

<div class="contact" id="contact">
  <h2>Contact Us</h2>
  <p>📍 Bangalore</p>
  <p>📞 9876543210</p>
  <p>📧 urbanbites@email.com</p>
</div>

<a class="whatsapp" href="https://wa.me/919876543210">💬</a>

</body>
</html>
