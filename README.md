<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Maid.in</title>
  <link rel="stylesheet" href="styles.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap">
</head>
<body>
  <header class="hero">
    <div class="container">
      <h1>Professional Maid Services at Your Doorstep</h1>
      <p>Affordable, Reliable, Verified – Helping Homes, Offices, Hospitals & More</p>
      <a href="https://wa.me/7470945798" class="btn">Book on WhatsApp</a>
    </div>
  </header>

  <section class="about">
    <div class="container">
      <h2>About The Maid.in</h2>
      <p>The Maid.in is a new-age startup from Bhopal, founded by a medical student, making it easier for Indians to hire domestic help with trust, transparency, and technology.</p>
    </div>
  </section>

  <section class="services">
    <div class="container">
      <h2>Our Services</h2>
      <div class="service-grid">
        <div class="service-card"><h3>Home Cleaning</h3><p>Regular or deep cleaning with trusted professionals.</p></div>
        <div class="service-card"><h3>Office Cleaning</h3><p>Daily & weekly services tailored for workplaces.</p></div>
        <div class="service-card"><h3>Hospital Cleaning</h3><p>Hygienic and trained staff for hospital-grade service.</p></div>
        <div class="service-card"><h3>Cook & Kitchen Help</h3><p>Experienced cooks and kitchen assistants available.</p></div>
      </div>
    </div>
  </section>

  <section class="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p>📍 Bhopal, India<br>📞 7470945798<br>✉️ support@themaid.in</p>
      <iframe src="https://maps.google.com/maps?q=Bhopal&t=&z=13&ie=UTF8&iwloc=&output=embed"
        width="100%" height="300" frameborder="0" style="border:0;" allowfullscreen></iframe>
    </div>
  </section>

  <footer>
    <p>© 2025 The Maid.in – All rights reserved</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Inter', sans-serif;
  background: #fff;
  color: #333;
  line-height: 1.6;
}
.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
  padding: 40px 20px;
}
.hero {
  background: url('https://images.unsplash.com/photo-1598514982903-38879aeb9b3c') center/cover no-repeat;
  color: white;
  padding: 100px 20px;
  text-align: center;
}
.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}
.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}
.btn {
  background-color: #00b894;
  color: white;
  padding: 12px 24px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s ease;
}
.btn:hover {
  background-color: #019874;
}
.about, .contact {
  background: #f9f9f9;
}
.services {
  background: #fff;
}
h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #2d3436;
}
.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}
.service-card {
  padding: 20px;
  background: #f1f2f6;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
}
footer {
  text-align: center;
  padding: 20px;
  background: #dfe6e9;
  font-size: 0.9rem;
  color: #636e72;
}
