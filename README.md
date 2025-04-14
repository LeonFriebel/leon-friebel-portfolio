<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Leon Friebel | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #1e1e1e;
      line-height: 1.6;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #1b263b;
      padding: 1rem;
      display: flex;
      justify-content: center;
      z-index: 999;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
      font-size: 1rem;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 5rem 2rem;
      max-width: 900px;
      margin: auto;
    }
    .hero {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      height: 100vh;
      background-color: #0d1b2a;
      color: white;
      text-align: center;
      padding: 0 2rem;
    }
    .hero h1 {
      font-size: 3.5rem;
      margin: 0;
    }
    .hero p {
      font-size: 1.2rem;
      margin-top: 1rem;
      max-width: 700px;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    a {
      color: #0077cc;
    }
    footer {
      background-color: #1b263b;
      color: white;
      text-align: center;
      padding: 1rem 2rem;
    }
  </style>
</head>
<body>

<nav>
  <a href="#about">About</a>
  <a href="#research">Research</a>
  <a href="#apps">Apps</a>
  <a href="#resume">Resume</a>
  <a href="#contact">Contact</a>
</nav>

<section class="hero">
  <h1>Leon Friebel</h1>
  <p>Quantitative Economics & International Business student | R programmer | Shiny app developer | NFL momentum researcher</p>
</section>

<section id="about">
  <h2>About Me</h2>
  <p>
    I’m Leon Friebel, a senior at Dickinson College pursuing degrees in Quantitative Economics and International Business & Management. 
    My work focuses on applying statistical and economic models to real-world problems, from financial analysis to sports analytics.
  </p>
</section>

<section id="research">
  <h2>Research</h2>
  <p>
    My research includes an algorithm to quantify momentum in American Football, revealing strategic insights that can improve win probability by over 70%. 
    I'm also working on integrating financial models like CAPM and Fama-French into user-friendly dashboards.
  </p>
  <ul>
    <li><strong>NFL Momentum Analysis (1999–present):</strong> R-based project using live play data</li>
    <li><strong>Stock Return Models:</strong> Visualizing CAPM and Fama-French results using Shiny</li>
    <li><strong>Feminist Economics Paper:</strong> Investigating gender disparities in India’s labor market</li>
  </ul>
</section>

<section id="apps">
  <h2>Shiny Apps</h2>
  <ul>
    <li><strong>NFL Momentum Tracker:</strong> <a href="https://yourname.shinyapps.io/nfl-momentum/" target="_blank">View App</a></li>
    <li><strong>Stock Analysis Dashboard:</strong> <a href="https://yourname.shinyapps.io/stock-analyzer/" target="_blank">View App</a></li>
  </ul>
</section>

<section id="resume">
  <h2>Resume</h2>
  <p>You can <a href="Leon_Friebel_Resume.pdf" target="_blank">download my resume here</a>.</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:friebell@dickinson.edu">friebell@dickinson.edu</a></p>
  <p>LinkedIn: <a href="https://linkedin.com/in/leon-friebel" target="_blank">leon-friebel</a></p>
  <p>GitHub: <a href="https://github.com/leonfriebel" target="_blank">github.com/leonfriebel</a></p>
</section>

<footer>
  <p>&copy; 2025 Leon Friebel. All rights reserved.</p>
</footer>

</body>
</html>
