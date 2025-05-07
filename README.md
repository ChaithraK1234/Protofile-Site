<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
      animation: fadeIn 1s ease-in-out;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00BFFF;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
      animation: slideUp 1s ease-in-out;
    }

    h2 {
      color: #444;
      margin-bottom: 10px;
    }

    .project {
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 20px;
      margin-bottom: 20px;
      background: #fff;
      box-shadow: 0 4px 6px rgba(0,0,0,0.05);
      transition: transform 0.3s;
    }

    .project:hover {
      transform: translateY(-5px);
    }

    .project a {
      color: #007BFF;
      text-decoration: none;
    }

    .project a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #eee;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    /* Responsive */
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }

      .project {
        padding: 15px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a front-end developer passionate about building beautiful and functional websites. With skills in HTML, CSS, JavaScript, and modern frameworks, I enjoy turning ideas into reality on the web.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>A responsive personal portfolio website built with HTML, CSS, and JavaScript to showcase my work and skills.</p>
      <a href="#">View Project</a>
    </div>
    <div class="project">
      <h3>To-Do App</h3>
      <p>A simple and elegant task management app with local storage and dynamic UI built using JavaScript.</p>
      <a href="#">View Project</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: yourname@example.com</p>
    <p>
      <a href="#">LinkedIn</a> |
      <a href="#">GitHub</a> |
      <a href="#">Twitter</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Your Name</p>
  </footer>
</body>
</html>
