<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gustavo Bertuzzi - Portfolio</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; background: #f4f4f4; }
    .container { width: 90%; max-width: 1200px; margin: auto; padding: 20px; background: #fff; }
    header { background: #333; color: #fff; padding: 20px 0; text-align: center; }
    nav { margin-top: 10px; }
    nav a { color: #fff; margin: 0 10px; text-decoration: none; display: inline-block; padding: 5px 10px; }
    h1, h2 { color: #333; }
    .section { margin-bottom: 40px; }
    .project { margin-bottom: 20px; }
    footer { text-align: center; padding: 20px; background: #333; color: #fff; }

    @media (max-width: 768px) {
      nav a { display: block; margin: 10px 0; }
      header { padding: 10px 0; }
    }
  </style>
</head>
<body>

<header>
  <h1>Gustavo Bertuzzi</h1>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="container">
  <section id="about" class="section">
    <h2>About Me</h2>
    <p>Hi! I'm Gustavo Bertuzzi, a Software Developer passionate about building scalable applications and solving real-world problems through technology. Currently pursuing an Associate Degree in Systems Analysis and Development at IFPR.</p>
  </section>

  <section id="projects" class="section">
    <h2>Projects</h2>
    <div class="project">
      <h3>Inventory Management API</h3>
      <p>Developed a RESTful API for managing inventory data, improving query performance by 30%.</p>
      <p><strong>Technologies:</strong> Java, Spring Boot, PostgreSQL</p>
      <p><a href="#">GitHub Repository</a></p>
    </div>
    <div class="project">
      <h3>Customer Relationship Management System</h3>
      <p>Designed a CRM system for a mechanic workshop, implementing features for customer and service management.</p>
      <p><strong>Technologies:</strong> Java, PostgreSQL, Spring Boot</p>
      <p><a href="#">GitHub Repository</a></p>
    </div>
  </section>

  <section id="skills" class="section">
    <h2>Skills</h2>
    <ul>
      <li>Java</li>
      <li>JavaScript</li>
      <li>Spring Boot</li>
      <li>Oracle</li>
      <li>PostgreSQL</li>
      <li>Object-Oriented Programming (OOP)</li>
      <li>RESTful APIs</li>
      <li>Git</li>
      <li>SQL</li>
      <li>Problem Solving</li>
    </ul>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: gustavobertuzzi10@gmail.com</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/gustavo-bertuzzi" target="_blank">linkedin.com/in/gustavo-bertuzzi</a></p>
    <p>GitHub: [Add your GitHub link here]</p>
  </section>
</div>

<footer>
  <p>&copy; 2025 Gustavo Bertuzzi. All rights reserved.</p>
</footer>

</body>
</html>
