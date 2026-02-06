# Mala-Holdings

<heade>
  <nav class="navbar">
      <div class='logo">Mala Holding</div>
      <ul class="nav-Links" id="navLinks"> 
          <li><a href="#Home">Home</></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
          <li><a href="#testestimonials">Testimonials</a></li>
          <a><a href="#contact">Contact</a></li>
        </ul>
        </div class="humbarger"> online="tagglemenu()">
             ☰
    </div>
    </nav>
https://res.cloudinary.com/<cloud_name>/image/upload/<transformations>/<folder>/<filename>
https://res.cloudinary.com/your_cloud_name/image/upload/f_auto,q_auto/mala-holding/logo.png
VITE_CLOUDINARY_CLOUD_NAME=your_cloud_name
VITE_CLOUDINARY_API_KEY=your_api_key
VITE_CLOUDINARY_API_SECRET=your_api_secret

npm install cloudinary

import { v2 as cloudinary } from 'cloudinary';

cloudinary.config({
  cloud_name: import.meta.env.VITE_CLOUDINARY_CLOUD_NAME,
  api_key: import.meta.env.VITE_CLOUDINARY_API_KEY,
  api_secret: import.meta.env.VITE_CLOUDINARY_API_SECRET
});

cloudinary.uploader.upload("src/assets/logo.png", {
  folder: "mala-holding"
}).then(result => console.log(result.secure_url));

function Hero() {
  return (
    <img 
      src="https://res.cloudinary.com/your_cloud_name/image/upload/v123456789/mala-holding/logo.png" 
      alt="Mala Holding Logo" 
    />
  );
}
</header>

.../image/upload/w_400,h_300,f_auto,q_auto/mala-holding/portfolio1.jpg
.../image/upload/w_300,h_300,c_fill,f_auto,q_auto/mala-holding/banner.jpg
<img 
  src="https://res.cloudinary.com/your_cloud_name/image/upload/w_600,f_auto,q_auto/mala-holding/portfolio1.jpg"
  srcSet="
    https://res.cloudinary.com/your_cloud_name/image/upload/w_300,f_auto,q_auto/mala-holding/portfolio1.jpg 300w,
    https://res.cloudinary.com/your_cloud_name/image/upload/w_600,f_auto,q_auto/mala-holding/portfolio1.jpg 600w,
    https://res.cloudinary.com/your_cloud_name/image/upload/w_1200,f_auto,q_auto/mala-holding/portfolio1.jpg 1200w
  "
  sizes="(max-width: 600px) 300px, (max-width: 1200px) 600px, 1200px"
  alt="Portfolio Screenshot"
/>


HTML STRUCTURE form


HTML Structure Form 
Code to footer 

'''html
<DOCKTYPE HTML>
<html lang="en">

<head>
  <meta charset="UIF-8">
  <mETA NAME="viewport"Contant="width=device-width, initial-scale=1.0">
  <title>Mala Holding</title>
  <rel="stylesheet" href=" style.css">
  
</head>

<body>

  <1-- Navigatinn-- >
  <nav>
    <a href="Home">Home</a>
    <a href="#Services"> Services</a>
    <a href="portfolio"> Portfolio</a>
    <a href="testimonial"> testimonial</a>
    <a href="Contact"> contact</a> 
  </nav>
  <1-- Hero Section -->
    <secction id ="Home>
      <h1> Welcome to Mala Holding </h1>
      <p>Profetional IT Services to your Businesses thrive in the digital world </p>
      <botton>Get started </botton>
      <section>

      <!--services section-->
      <section id="services">
      <h2="our services</h2>
      <p> We provide a range of IT Solution tailarate toyour needs</p>
      <ul>
      <li> Web Development</li>
      <LI>IT Consalting</li>
      <li>Cloud solution</li>
      <li>Cyber security</li>
      </ul>
      </Section>
       <!--Portfolio Section-->
       <Section id="Portfolio">
       <h2>portfolio</h2>
       <p> here are sokme our recent project<p/>
       <div>
       <img src="project1.JPG" ALT="project1"loading="lazy">
       <img src="project2.JPG"ALT="project2="loading="lazy>
       <img src="project3.JPG"ALT="PROJECT3="loading="lazy>
       </div>
       </Section>   
       <!--testimonials Section-->
       <Section id=" testimonials"> 
       <h2> What our lients say</h2>
         <Blockqoute>
         "Mala Holding transformed our online service. Highly Professional and realable" 
         </Blockqoute>
         <Blockqoute>
         "Excelent service snd support. We trust them with our IT needs"
         </Blockqoute>
         </section>
         <--Contact Section-->
         <section id="contact">
         <h2>Contact Us</h2>
         <Form Name="contact" method="Post" data-Netlify="true">
                <input type="text nameplaceholder="Your Name" requare>
                <input type="email nameplaceholder="Your Nme" require>
                <input type="massege nameplaceholder="Your Name" require>
                <input type="msubmit"> Sand massege <button/>
                </form>
                </Sections>
             <!-- footer -->   
                <footer>
                <p>&copy; 2026 Mala Holding. All right reseved.</p>
 
        </FOOTER>
        
     </body>   

</html>
---

---




         
      </body>
7434b429f4f9d9e2c2d91c95cfd73eba7d08c61d
git add assets/images/logo.png
git commit -m "Add Mala Holding logo"
git push origin main
<header>
  <img src="assets/images/logo.png" alt="Mala Holding Logo" width="200">
  
</header> 
.logo {
  background-image: url("assets/images/logo.png");
  background-size: contain;
  background-repeat: no-repeat;
  width: 200px;
  height: 80px;
}
  font-weight: bold;
  font-weight: bold;
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mala Holding - IT Services</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Mala Holding</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="hero">
    <h2>Professional IT Services for a Connected World</h2>
    <p>Building trust through technology and design.</p>
    <button>Get Started</button>
  </section>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mala Holding - IT Services</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">Mala Holding</div>
    <nav>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="hero">
    <h1>Professional IT Services for All Businesses</h1>
    <p>Building trust through technology and design.</p>
    <button>Get Started</button>
  </section>

  <!-- Services -->
  <section id="services">
    <h2>Our Services</h2>
    <div class="service-grid">
      <div class="service-card">Web Development</div>
      <div class="service-card">Cloud Solutions</div>
      <div class="service-card">Cybersecurity</div>
      <div class="service-card">IT Consulting</div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 Mala Holding. All rights reserved.</p>
    <p>Contact: info@malaholding.com</p>
  </footer>
</body>
</html>

body {
  font-family: 'Open Sans', sans-serif;
  margin: 0;
  padding: 0;
  background: #fff;
  color: #333;
}

header {
  background: #0d47a1; /* deep blue */
  color: white;
  padding: 1rem;
  display: flex;
  justify-content: space-between;
}

nav a {
  color: white;
  margin: 0 1rem;
  text-decoration: none;
}

#hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(to right, #e53935, #0d47a1); /* red to blue */
  color: white;
}

button {
  background: white;
  color: #0d47a1;
  border: none;
  padding: 1rem 2rem;
  cursor: pointer;
  font-weight: bold;
}
<section id="hero">
  <div class="hero-content">
    <h1>Professional IT Services for All Businesses</h1>
    <p>Building trust through technology and design.</p>
    <button class="cta">Get Started</button>
  </div>
</section>

<section id="services">
  <h2>Our Services</h2>
  <div class="service-grid">
    <div class="service-card">
      <span class="icon">💻</span>
      <h3>Web Development</h3>
      <p>Responsive, modern websites tailored to your business.</p>
    </div>
    <div class="service-card">
      <span class="icon">☁️</span>
      <h3>Cloud Solutions</h3>
      <p>Secure, scalable cloud infrastructure for growth.</p>
    </div>
    <div class="service-card">
      <span class="icon">🔒</span>
      <h3>Cybersecurity</h3>
      <p>Protecting your business with advanced security tools.</p>
    </div>
    <div class="service-card">
      <span class="icon">🛠️</span>
      <h3>IT Consulting</h3>
      <p>Expert advice to optimize your IT strategy.</p>
    </div>
  </div>
</section>

body {
  font-family: 'Open Sans', sans-serif;
  margin: 0;
  background: #fff;
  color: #333;
}

header {
  background: #0d47a1;
  color: white;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: white;
  margin: 0 1rem;
  text-decoration: none;
  font-weight: 600;
}

#hero {
  background: linear-gradient(135deg, #e53935, #0d47a1);
  color: white;
  text-align: center;
  padding: 6rem 2rem;
}

#hero h1 {
  font-family: 'Montserrat', sans-serif;
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.cta {
  background: white;
  color: #0d47a1;
  border: none;
  padding: 1rem 2rem;
  font-size: 1rem;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

.cta:hover {
  background: #e53935;
  color: white;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 2rem;
  padding: 3rem 2rem;
}

.service-card {
  background: #f9f9f9;
  padding: 2rem;
  border-radius: 10px;
  text-align: center;
  transition: 0.3s;
}

.service-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transform: translateY(-5px);
}

.icon {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #0d47a1;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mala Holding - IT Services</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">Mala Holding</div>
    <nav>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="hero">
    <div class="hero-content">
      <h1>Professional IT Services for All Businesses</h1>
      <p>Building trust through technology and design.</p>
      <button class="cta">Get Started</button>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Our Services</h2>
    <div class="service-grid">
      <div class="service-card">
        <span class="icon">💻</span>
        <h3>Web Development</h3>
        <p>Responsive, modern websites tailored to your business.</p>
      </div>
      <div class="service-card">
        <span class="icon">☁️</span>
        <h3>Cloud Solutions</h3>
        <p>Secure, scalable cloud infrastructure for growth.</p>
      </div>
      <div class="service-card">
        <span class="icon">🔒</span>
        <h3>Cybersecurity</h3>
        <p>Protecting your business with advanced security tools.</p>
      </div>
      <div class="service-card">
        <span class="icon">🛠️</span>
        <h3>IT Consulting</h3>
        <p>Expert advice to optimize your IT strategy.</p>
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <h2>Our Work</h2>
    <div class="portfolio-grid">
      <div class="portfolio-item">
        <img src="project1.jpg" alt="Project 1">
        <h3>E-commerce Platform</h3>
        <p>Built a scalable online store with secure payment integration.</p>
      </div>
      <div class="portfolio-item">
        <img src="project2.jpg" alt="Project 2">
        <h3>Business Website</h3>
        <p>Designed a professional site for a growing consultancy firm.</p>
      </div>
      <div class="portfolio-item">
        <img src="project3.jpg" alt="Project 3">
        <h3>Cloud Migration</h3>
        <p>Helped a client move their infrastructure to the cloud.</p>
      </div>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials">
    <h2>What Our Clients Say</h2>
    <div class="testimonial-grid">
      <div class="testimonial">
        <p>"Mala Holding transformed our online presence. Highly recommended!"</p>
        <span>- Client A</span>
      </div>
      <div class="testimonial">
        <p>"Reliable IT support that keeps our business running smoothly."</p>
        <span>- Client B</span>
      </div>
      <div class="testimonial">
        <p>"Professional, innovative, and trustworthy. A great partner."</p>
        <span>- Client C</span>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 Mala Holding. All rights reserved.</p>
    <p>Contact: info@malaholding.com | +27 123 456 789</p>
    <p>Follow us: LinkedIn | Twitter | GitHub</p>
  </footer>
</body>
</html>
/* General */
body {
  font-family: 'Open Sans', sans-serif;
  margin: 0;
  background: #fff;
  color: #333;
}

/* Header */
header {
  background: #0d47a1;
  color: white;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: white;
  margin: 0 1rem;
  text-decoration: none;
  font-weight: 600;
}

/* Hero */
#hero {
  background: linear-gradient(135deg, #e53935, #0d47a1);
  color: white;
  text-align: center;
  padding: 6rem 2rem;
}

#hero h1 {
  font-family: 'Montserrat', sans-serif;
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.cta {
  background: white;
  color: #0d47a1;
  border: none;
  padding: 1rem 2rem;
  font-size: 1rem;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

.cta:hover {
  background: #e53935;
  color: white;
}

/* Services */
.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 2rem;
  padding: 3rem 2rem;
}

.service-card {
  background: #f9f9f9;
  padding: 2rem;
  border-radius: 10px;
  text-align: center;
  transition: 0.3s;
}

.service-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transform: translateY(-5px);
}

.icon {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #0d47a1;
}

/* Portfolio */
.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  padding: 3rem 2rem;
}

.portfolio-item img {
  width: 100%;
  border-radius: 8px;
}

/* Testimonials */
.testimonial-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  padding: 3rem 2rem;
}

.testimonial {
  background: #f1f1f1;
  padding: 2rem;
  border-radius: 10px;
  font-style: italic;
}

/* Footer */
footer {
  background: #0d47a1;
  color: white;
  text-align: center;
  padding: 2rem;
}

<section id="services-hero">
  <h1>Our IT Services</h1>
  <p>Tailored solutions to help businesses thrive in the digital age.</p>
</section>

<section id="services-list">
  <div class="service-card">
    <span class="icon">💻</span>
    <h2>Web Development</h2>
    <p>Responsive websites, e-commerce platforms, and custom applications.</p>
    <a href="#webdev" class="learn-more">Learn More</a>
  </div>

  <div class="service-card">
    <span class="icon">☁️</span>
    <h2>Cloud Solutions</h2>
    <p>Migration, hosting, and scalable infrastructure for growth.</p>
    <a href="#cloud" class="learn-more">Learn More</a>
  </div>

  <div class="service-card">
    <span class="icon">🔒</span>
    <h2>Cybersecurity</h2>
    <p>Threat detection, compliance, and advanced data protection.</p>
    <a href="#security" class="learn-more">Learn More</a>
  </div>

  <div class="service-card">
    <span class="icon">🛠️</span>
    <h2>IT Consulting</h2>
    <p>Expert advice to optimize your IT strategy and operations.</p>
    <a href="#consulting" class="learn-more">Learn More</a>
  </div>
</section>

<section id="cta-banner">
  <h2>Ready to transform your business with IT solutions?</h2>
  <button class="cta">Contact Us Today</button>
</section>

 #services-hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #0d47a1, #e53935);
  color: white;
}

#services-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  padding: 3rem 2rem;
}

.service-card {
  background: #f9f9f9;
  padding: 2rem;
  border-radius: 10px;
  text-align: center;
  transition: 0.3s;
}

.service-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transform: translateY(-5px);
}

.learn-more {
  display: inline-block;
  margin-top: 1rem;
  color: #0d47a1;
  font-weight: bold;
  text-decoration: none;
}

.learn-more:hover {
  color: #e53935;
}

#cta-banner {
  text-align: center;
  padding: 3rem 2rem;
  background: #0d47a1;
  color: white;
}

#cta-banner .cta {
  background: #e53935;
  color: white;
  border: none;
  padding: 1rem 2rem;
  font-size: 1rem;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#cta-banner .cta:hover {
  background: white;
  color: #0d47a1;
}
<section id="services-hero">
  <h1>Our IT Services</h1>
  <p>Tailored solutions to help businesses thrive in the digital age.</p>
</section>

<section id="services-list">
  <div class="service-card">
    <span class="icon">💻</span>
    <h2>Web Development</h2>
    <p>Responsive websites and custom applications.</p>
  </div>

  <div class="service-card">
    <span class="icon">☁️</span>
    <h2>Cloud Solutions</h2>
    <p>Scalable hosting and infrastructure.</p>
  </div>

  <div class="service-card">
    <span class="icon">🔒</span>
    <h2>Cybersecurity</h2>
    <p>Advanced protection and compliance.</p>
  </div>

  <div class="service-card">
    <span class="icon">🛠️</span>
    <h2>IT Consulting</h2>
    <p>Expert advice to optimize your IT strategy.</p>
  </div>
</section>

<section id="cta-banner">
  <h2>Ready to transform your business with IT solutions?</h2>
  <button class="cta">Contact Us Today</button>
</section>

#services-hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #0d47a1, #e53935);
  color: white;
}

#services-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 2rem;
  padding: 3rem 2rem;
}

.service-card {
  background: #f9f9f9;
  padding: 2rem;
  border-radius: 10px;
  text-align: center;
  transition: 0.3s;
}

.service-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transform: translateY(-5px);
}

.icon {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #0d47a1;
}

#cta-banner {
  text-align: center;
  padding: 3rem 2rem;
  background: #0d47a1;
  color: white;
}

#cta-banner .cta {
  background: #e53935;
  color: white;
  border: none;
  padding: 1rem 2rem;
  font-size: 1rem;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#cta-banner .cta:hover {
  background: white;
  color: #0d47a1;
}

git add .
git commit -m "Added Call to Action section"
git push origin main
<form name="contact" method="POST" data-netlify="true">
  <input type="hidden" name="form-name" value="contact" />
  
  <label>Your Name:</label>
  <input type="text" name="name" required />

  <label>Your Email:</label>
  <input type="email" name="email" required />

  <label>Message:</label>
  <textarea name="message" required></textarea>

  <button type="submit">Send</button>
</form>
<form name="contact" method="POST" data-netlify="true" action="/thank-you">
  <input type="hidden" name="form-name" value="contact" />
  <!-- fields here -->
</form>

feature/*  --->  dev (staging)  --->  main (production)
     |             |                   |
 Deploy Preview   Staging Site        Live Site





    
