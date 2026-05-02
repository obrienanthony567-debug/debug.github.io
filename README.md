# debug.github.io
A moving company website 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Box & Beyond Moving</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  color: #111;
}

/* NAVBAR */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 50px;
  background: white;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  position: sticky;
  top: 0;
}

header h2 {
  color: #0d1b2a;
}

nav a {
  margin-left: 25px;
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

/* HERO */
.hero {
  height: 90vh;
  background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.6)),
  url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c') center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
}

.hero h1 {
  font-size: 60px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 20px;
  margin-bottom: 25px;
}

.btn {
  background: #d4af37;
  padding: 15px 35px;
  color: black;
  text-decoration: none;
  border-radius: 5px;
  font-weight: 600;
}

/* TRUST BAR */
.trust {
  display: flex;
  justify-content: space-around;
  padding: 20px;
  background: #f8f8f8;
  font-weight: 500;
}

/* SERVICES */
.services {
  padding: 80px 50px;
  text-align: center;
}

.services h2 {
  font-size: 36px;
  margin-bottom: 40px;
}

.cards {
  display: flex;
  gap: 30px;
  justify-content: center;
  flex-wrap: wrap;
}

.card {
  width: 280px;
  padding: 30px;
  border-radius: 10px;
  background: white;
  box-shadow: 0 10px 30px rgba(0,0,0,0.08);
}

/* WHY US */
.why {
  background: #0d1b2a;
  color: white;
  padding: 80px 50px;
  text-align: center;
}

/* CTA */
.cta {
  padding: 80px;
  text-align: center;
  background: #d4af37;
}

/* FORM */
form input, form textarea {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
}

/* FOOTER */
footer {
  background: #111;
  color: white;
  text-align: center;
  padding: 30px;
}
</style>
</head>

<body>

<header>
  <h2>Box & Beyond</h2>
  <nav>
    <a href="#">Home</a>
    <a href="#">Services</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section class="hero">
  <div>
    <h1>Move Smarter. Move Better.</h1>
    <p>Luxury-level moving with speed, care, and precision.</p>
    <a href="#" class="btn">Get Free Quote</a>
  </div>
</section>

<div class="trust">
  <div>✔ Licensed & Insured</div>
  <div>✔ 5-Star Service</div>
  <div>✔ Fast & Reliable</div>
</div>

<section class="services">
  <h2>Our Services</h2>
  <div class="cards">
    <div class="card">
      <h3>Local Moves</h3>
      <p>Fast and smooth moves within your city.</p>
    </div>
    <div class="card">
      <h3>Long Distance</h3>
      <p>Secure transport across states with zero stress.</p>
    </div>
    <div class="card">
      <h3>Packing</h3>
      <p>Professional packing that protects everything.</p>
    </div>
  </div>
</section>

<section class="why">
  <h2>Why Box & Beyond?</h2>
  <p>We deliver premium moving experiences with attention to detail, speed, and care.</p>
</section>

<section class="cta">
  <h2>Get Your Free Quote Today</h2>
  <form>
    <input type="text" placeholder="Full Name">
    <input type="email" placeholder="Email">
    <input type="text" placeholder="Moving From / To">
    <textarea placeholder="Details"></textarea>
    <br>
    <a href="#" class="btn">Submit Request</a>
  </form>
</section>

<footer>
  <p>© 2026 Box & Beyond Moving Company</p>
</footer>

</body>
</html>