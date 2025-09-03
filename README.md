<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>InfiLink | Smart Livestock Management</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">
      <img src="C:\animal protection\assert\lo.jpg" alt="InfiLink Logo">
      <h1>InfiLink</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#solutions">Solutions</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#team">Team</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero -->
  <section class="hero">
    <div class="hero-text">
      <h2>Boundless Connectivity & Endless Possibilities 🐄</h2>
      <p>Revolutionizing livestock management with IoT-driven solutions for real-time health, location, and behavior monitoring.</p>
      <a href="#solutions" class="btn">Explore Solutions</a>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="about">
    <h2>About Us</h2>
    <p>At <b>InfiLink</b>, we focus on building smart livestock management systems using IoT and AI technologies. 
       Our vision is to help farm owners monitor animal health, location, and behavior to ensure better productivity and animal welfare.</p>
  </section>

  <!-- Solutions -->
  <section id="solutions" class="solutions">
    <h2>Our Smart Solutions</h2>
    <div class="grid">
      <div class="card">Real-time Health Monitoring</div>
      <div class="card">GPS-based Animal Tracking</div>
      <div class="card">Behavior & Activity Analysis</div>
      <div class="card">Early Disease Detection</div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="projects">
    <h2>Key Projects</h2>
    <div class="grid">
      <div class="project-card">
        <h3>IoT Health Tags</h3>
        <p>Wearable sensors for cattle to detect vital signs and early disease symptoms.</p>
        <img src="C:\animal protection\assert\p1.png"width="200px"height="100px"alt="IoT Health Tags">
      </div>
      <div class="project-card">
        <h3>Smart Dairy Tracker</h3>
        <p>Monitoring milk production, feeding patterns, and cow health in real-time.</p>
        <img src="C:\animal protection\assert\p2.jpg"width="175px"height="100px"alt="Smart Dairy Tracker">
      </div>
      <div class="project-card">
        <h3>Ranch GPS Monitoring</h3>
        <p>GPS-enabled systems to locate and track livestock across large farms.</p>
        <img src="C:\animal protection\assert\p3.webp"width="175px"height="100px"alt="Ranch GPS Monitoring">
      </div>
    </div>
  </section>

  <!-- Team -->
  <section id="team" class="team">
    <h2>Meet Our Team</h2>
    <div class="grid">
      <div class="team-member"><b>Shaik Ayesha</b><br>(Team Leader)
    </div>
      <div class="team-member"><b>G. Triveni</b><br>(Handles Q&A)</div>
      <div class="team-member"><b>G. Anitha</b><br>(Handles Presentation)</div>
      <div class="team-member"><b>D. Gayathri</b><br>(Handles Emails)</div>
      <div class="team-member"><b>Shaik Sabiha</b><br>(Handles Documents)</div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2>Get In Touch</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Email Address" required>
      <textarea placeholder="Your Message" rows="4"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 InfiLink | Boundless Connectivity and Endless Possibilities</p>
  </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
  }
  
  body {
    background: #f9fbfd;
    color: #333;
  }
  
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 10%;
    background: #002b5c;
    color: #fff;
  }
  
  header .logo {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  
  header .logo img {
    height: 50px;
  }
  
  header ul {
    display: flex;
    gap: 20px;
    list-style: none;
  }
  
  header ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: 500;
  }
  
  .hero {
    background: #e6f0ff;
    padding: 60px 10%;
    text-align: center;
  }
  
  .hero-text h2 {
    font-size: 32px;
    color: #002b5c;
    margin-bottom: 15px;
  }
  
  .hero-text p {
    font-size: 18px;
    margin-bottom: 20px;
  }
  
  .btn {
    padding: 12px 20px;
    background: #0073e6;
    color: #fff;
    text-decoration: none;
    border-radius: 6px;
  }
  
  section {
    padding: 60px 10%;
    text-align: center;
  }
  
  .grid {
    display: flex;
    gap: 20px;
    margin-top: 30px;
    flex-wrap: wrap;
    justify-content: center;
  }
  
  .card, .project-card, .team-member {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    width: 220px;
    transition: transform 0.3s;
  }
  
  .card:hover, .project-card:hover, .team-member:hover {
    transform: translateY(-5px);
  }
  
  .contact form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 400px;
    margin: auto;
  }
  
  .contact input, .contact textarea {
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 6px;
  }
  
  .contact button {
    background: #0073e6;
    color: #fff;
    padding: 12px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
  
  footer {
    text-align: center;
    padding: 20px;
    background: #002b5c;
    color: #fff;
  }
