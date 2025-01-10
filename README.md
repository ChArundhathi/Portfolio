# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Header Section */
    header {
      background: linear-gradient(45deg, #6a11cb, #2575fc);
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* Section Styles */
    section {
      padding: 40px 20px;
      text-align: center;
    }

    #about img {
      width: 150px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    #skills ul {
      list-style-type: none;
      padding: 0;
    }

    #skills ul li {
      background: #f4f4f4;
      margin: 10px auto;
      padding: 10px;
      max-width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    #projects .project {
      background: #fff;
      margin: 20px auto;
      padding: 20px;
      max-width: 500px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    /* Footer Section */
    footer {
      background: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }

    footer a {
      color: #ffc107;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>Sushma Arundhathi</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <img src="https://via.placeholder.com/150" alt="Your Photo">
    <p>Hello! I'm Sushma Arundhathi, a passionate developer specializing in web development and software solutions.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML, CSS, JavaScript</li>
      <li>React.js and Node.js</li>
      <li>Python and Machine Learning</li>
      <li>Version Control (Git, GitHub)</li>
      <li>Problem Solving and Team Collaboration</li>
    </ul>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project 1: Stock Market Prediction</h3>
      <p>Developed a machine learning model to predict stock trends using LSTM and ARIMA.</p>
      <a href="#">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Project 2: Dynamic Portfolio Website</h3>
      <p>Designed and developed a responsive personal website using React.js.</p>
      <a href="#">View Live Demo</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:arundhathi.ch06@gmail.com">arundhathi.ch06@gmail.com</a></p>
    <p>Phone: +91-7416369646</p>
    <p>GitHub: <a href="https://github.com/ChArundhathi">https://github.com/ChArundhathi</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/sushma-arundhathi-048bb826a"> https://www.linkedin.com/in/sushma-arundhathi-048bb826a </a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Sushma Arundhathi | <a href="#about">Back to Top</a></p>
  </footer>

</body>
</html>
