<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cheliz Portfolio Website</title>
  <link rel="stylesheet" href="gazoo.css" />
  <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet" />
</head>
<body>

  <header class="header">
    <a href="#home" class="logo">Cheliz <span>Posadas</span></a>
    <nav class="navbar">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#pet-adoption">Pet Adoption</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="home" id="home">
    <div class="home-content">
      <h1>Hi, it's <span>CJ</span></h1>
      <h3>I'm a <span>Junior Developer</span></h3>
      <p>
        I have over five years of experience working at Global Pet Foods,
        where I developed a strong passion for animals and truly enjoy caring
        for our furry visitors—especially giving them treats and affection.
        Outside of work, I love reading mystery and sci-fi novels that spark
        my imagination, as well as painting abstract art to ease anxiety and
        express creativity. I'm also deeply interested in coding and web
        development, and I often read inspirational books to fuel my goal of
        building my own website from the ground up.
      </p>

      <div class="social-icons">
        <a href="#"><i class="bx bxl-facebook"></i></a>
        <a href="#"><i class="bx bxl-twitter"></i></a>
        <a href="#"><i class="bx bxl-instagram"></i></a>
      </div>

      <div class="btn-group">
        <a href="#" class="btn">Hire</a>
        <a href="#contact" class="btn">Contact</a>
      </div>
    </div>

    <div class="home-img">
      <img src="Gazoo.jpg" alt="Gazoo Picture" />
    </div>
  </section>

  <section class="about" id="about">
    <div class="about-container">
      <div class="about-img">
        <img src="toby.jpg" alt="Toby Picture" />
      </div>
      <div class="about-content">
        <h2>About <span>CJ</span></h2>
        <p>
          I've always dreamed of starting my own business—not just to feed
          animals, but to make a difference in their lives. Helping homeless
          animals and giving them hope is a mission close to my heart.
          Everyday, I'm inspired by my furry best friends, Gazoo and Toby.
          Whether we're out for a walk or just spending quiet time together,
          they remind me why I'm so passionate about caring for animals and
          building a future where every pet feels loved and nourished.
        </p>
      </div>
    </div>
  </section>

  <section class="pet-adoption" id="pet-adoption">
    <h2 class="heading">Pet Adoption</h2>
    <div class="pet-adoption-container">
      <div class="pet-adoption-box">
        <div class="pet-adoption-info">
          <h4>Pet Adoption</h4>
          <p>
            We provide shelter, care, training, veterinary support, and a
            second chance to animals in need. Setting them up for a joyous and
            happy new life. But, we do so much more than that as well.
          </p>
          <p>
            Providing a full range of services to support guardians and their
            pets at all stages; training and behavioural support, temporary
            sheltering, accessible veterinary care and pet food support.
          </p>
          <p>
            Education, advocacy, and industry advancements through research
            underpin everything we do.
          </p>
        </div>
      </div>

      <div class="pet-adoption-box">
        <div class="pet-adoption-info">
          <i class="bx bx-heart"></i>
          <p>We offer affordable medical services for rescued and adopted pets...</p>
        </div>
      </div>

      <div class="pet-adoption-box">
        <div class="pet-adoption-info">
          <i class="bx bx-donate-heart"></i>
          <h4>Pet Food Program</h4>
          <p>
            We support families with nutritious food to keep their pets healthy
            at home...
          </p>
        </div>
      </div>
    </div>
  </section>

  
  <section class="contact" id="contact">
    <h2 class="heading">Contact <span>CJ</span></h2>
    
    <form action="">
     <div class="input-group">
     <div class="input-box">
    <input type="text" placeholder="Full Name">
    <input type="email" placeholder="Email"></div>
    <div class="input-box">
    <input type="phone number" placeholder="Phone Number">
    <input type="text" placeholder="Subject">
</div>
  
<div class="input-group 2">
    <textarea name="" id=""cols="30" rows="10"
    placeholder="Your Message"></textarea>
    <input type="submit" value="send message"
    class="btn">
</div>
  
  
</form>
 
      
  <footer class="footer">
    <div class="social-icons">
      <a href="#"><i class="bx bxl-facebook"></i></a>
      <a href="#"><i class="bx bxl-twitter"></i></a>
      <a href="#"><i class="bx bxl-instagram"></i></a>
    </div>

   
    <p class="copyright">
      @Cheliz S. Posadas | 2025 All Rights Reserved
    </p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
