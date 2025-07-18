
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SparkClean Services</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f8fb;
      color: #333;
    }
    header {
      background-image:url(https://th.bing.com/th/id/OIP.BB7KU1SecRCfTnkNGBzmrgHaE7?w=268&h=180&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3);background-size: cover;height: 300px;>

      background-position:no-repeat center center/cover;
      color: white;
      padding: 4rem 2rem;
      text-align: center;
      position: relative;
    }
    header::after {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 0, 0.4);
    }
    header h1, header p, header img {
      position: relative;
      z-index: 2;
    }
    header h1 {
      margin: 0;
      font-size: 2.8rem;
    }
    header p {
      font-size: 1.3rem;
      margin-top: 0.5rem;
    }
    header img.logo {
      width: 120px;
      margin-bottom: 1rem;
    }
    section {
      padding: 3rem 1.5rem;
      max-width: 1000px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .service-box {
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s ease;
    }
    .service-box:hover {
      transform: translateY(-5px);
    }
    .service-box h3 {
      color: #00aaff;
      margin-bottom: 0.5rem;
    }
    .service-box img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 1rem;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 500px;
      margin: auto;
    }
    form input, form textarea {
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }
    form button {
      padding: 0.75rem;
      background-color: #00aaff;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    form button:hover {
      background-color: #008fcc;
    }
    footer {
      background-color: #003c5a;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
    nav {
      background: #fff;
      padding: 1rem;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    nav a {
      margin: 0 1rem;
      color: #00aaff;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 100%;
      padding: 15px;
      font-size: 24px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      text-decoration: none;
      z-index: 999;
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-Fo3rlrZj/kTcQeXtfLOcOZL+yXNLx+54Kjbpsm/1VvIb0U7XYM8i4K3Nq4d2ezBfN+P3dZW2Xl+XQJ5Kk5PjOw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <header>
        <h1>The-CastleMan</h1>
    <h1>SparkClean Services</h1>
    <p>Where Cleanliness Sparks Confidence</p>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>At SparkClean, we are committed to delivering high-quality cleaning services that brighten your home and workspace. Whether it's residential, commercial, or deep cleaning — our trained team ensures a spotless experience with eco-friendly methods.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service-box">
        <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c" alt="Home Cleaning">
        <h3>Home Cleaning</h3>
        <p>Comprehensive cleaning solutions to keep your home fresh and sparkling.</p>
      </div>
      <div class="service-box">
        <img src="https://tse1.mm.bing.net/th/id/OIP.ixzGdo3sg0ARyYS3qK1alwHaE8?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Office Cleaning">
        <h3>Office Cleaning</h3>
        <p>Clean, hygienic office spaces that boost productivity and morale.</p>
      </div>
      <div class="service-box">
        <img src="https://www.denverhousecleaningpros.com/wp-content/uploads/2019/03/before-after5-o.jpg" alt="Deep Cleaning">
        <h3>Deep Cleaning</h3>
        <p>Intensive cleaning for kitchens, bathrooms, and hard-to-reach areas.</p>
      </div>
      <div class="service-box">
        <img src="https://bleuskycleaning.com/wp-content/uploads/2025/01/Bathroom-deep-cleaning.jpg" alt="Sanitization">
        <h3>Sanitization Services</h3>
        <p>Advanced disinfection solutions for homes and commercial units.</p>
      </div>
      <div class="service-box">
        <img src="C:\Users\harshal\Downloads\ChatGPT Image Jul 18, 2025, 11_40_22 PM.png" alt="Carpet Shampooing">
        <h3>Car Cleaning</h3>
        <p>Professional carpet cleaning to remove deep-seated dirt.</p>
      </div>
      <div class="service-box">
        <img src="https://i.pinimg.com/736x/dd/ca/e7/ddcae77e8f532398daf158f6d0b23670.jpg" alt="Glass Cleaning">
        <h3>Glass Cleaning</h3>
        <p>Crystal-clear cleaning of glass windows, panels, and partitions.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <input type="tel" name="phone" placeholder="Phone Number" required />
      <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p style="text-align:center; margin-top:1rem;">📞 +91-8668682778 | ✉ contact@the-castleman.com</p>
    <p style="text-align:center;">📍 Nagpur, Maharashtra</p>
  </section>

  <a href="https://wa.me/918668682778" class="whatsapp-button" target="_blank">
    <i class="fab fa-whatsapp"></i>
  </a>

  <footer>
    &copy; 2025 the-castleman operation pvt ltd. All rights reserved.
  </footer>
</body>
</html>
