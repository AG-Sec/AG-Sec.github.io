<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Ascend Trading</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      scroll-behavior: smooth;
    }
    /* Navigation */
    header {
      position: fixed;
      width: 100%;
      background: rgba(0, 0, 0, 0.7);
      padding: 10px 20px;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: #fff;
    }
    header nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    /* Hero Section */
    .hero {
      height: 100vh;
      background: url('https://via.placeholder.com/1500x1000') no-repeat center center/cover;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: #fff;
      text-align: center;
      padding: 0 20px;
    }
    .hero h1 {
      font-size: 4em;
      margin: 0;
    }
    .hero p {
      font-size: 1.5em;
      margin: 20px 0;
    }
    .hero .cta-button {
      padding: 15px 30px;
      background-color: #ff4f00;
      border: none;
      color: #fff;
      font-size: 1em;
      cursor: pointer;
      border-radius: 5px;
    }
    /* Current Project Section */
    .current-project {
      padding: 80px 20px;
      background-color: #f9f9f9;
      text-align: center;
    }
    .current-project h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }
    .current-project p {
      font-size: 1.2em;
      margin-bottom: 30px;
    }
    .current-project .project-btn {
      padding: 10px 25px;
      background-color: #007BFF;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1em;
    }
    /* Past Projects Section */
    .past-projects {
      padding: 80px 20px;
      background-color: #fff;
    }
    .past-projects h2 {
      text-align: center;
      font-size: 2.5em;
      margin-bottom: 40px;
    }
    .project-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .project-card {
      background-color: #f1f1f1;
      border-radius: 8px;
      width: 300px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .project-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .project-card .card-content {
      padding: 20px;
      text-align: left;
    }
    .project-card h3 {
      margin-top: 0;
    }
    .project-card a {
      display: inline-block;
      margin-top: 10px;
      color: #007BFF;
      text-decoration: none;
      font-weight: bold;
    }
    /* Footer */
    footer {
      background-color: #222;
      color: #aaa;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <header>
    <div class="logo">Ascend Trading</div>
    <nav>
      <a href="#hero">Home</a>
      <a href="#current">Current Project</a>
      <a href="#past">Past Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="hero">
    <h1>Ascend Trading</h1>
    <p>Building and launching crypto projects every 2 weeks</p>
    <button class="cta-button">Join the Community</button>
  </section>

  <!-- Current Project Section -->
  <section class="current-project" id="current">
    <h2>Current Project: [Project Name]</h2>
    <p>Discover our latest crypto project, where innovation meets community. Learn about our vision, roadmap, and how you can be a part of the next breakthrough.</p>
    <button class="project-btn">Learn More</button>
  </section>

  <!-- Past Projects Section -->
  <section class="past-projects" id="past">
    <h2>Past Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <img src="https://via.placeholder.com/300x200" alt="Project 1">
        <div class="card-content">
          <h3>Project Alpha</h3>
          <p>A brief description of Project Alpha.</p>
          <a href="#">View Details</a>
        </div>
      </div>
      <div class="project-card">
        <img src="https://via.placeholder.com/300x200" alt="Project 2">
        <div class="card-content">
          <h3>Project Beta</h3>
          <p>A brief description of Project Beta.</p>
          <a href="#">View Details</a>
        </div>
      </div>
      <!-- Add more project cards as needed -->
    </div>
  </section>

  <!-- Footer -->
  <footer id="contact">
    <p>&copy; 2025 Ascend Trading. All rights reserved.</p>
    <p>Follow us on 
      <a href="#" style="color: #ff4f00; text-decoration: none;">Twitter</a> | 
      <a href="#" style="color: #ff4f00; text-decoration: none;">Discord</a>
    </p>
  </footer>
  
  <script>
    // Optionally, add JavaScript for interactive features like a carousel for past projects.
  </script>
</body>
</html>
