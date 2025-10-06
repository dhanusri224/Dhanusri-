<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dhanusri | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 2rem 0;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.1rem;
      color: #aaa;
    }

    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00bcd4;
    }

    section {
      padding: 3rem 10%;
    }

    h2 {
      color: #222;
      margin-bottom: 1rem;
      border-left: 5px solid #00bcd4;
      padding-left: 10px;
    }

    .about p {
      line-height: 1.6;
    }

    .skills ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .skills li {
      background-color: #00bcd4;
      color: white;
      padding: 0.7rem 1.2rem;
      border-radius: 25px;
      font-weight: 500;
    }

    .projects .project {
      background-color: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin-bottom: 1.5rem;
    }

    .contact p {
      margin-bottom: 0.5rem;
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      background-color: #222;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Dhanusri</h1>
    <p>Welcome to my portfolio!</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p> I am a passionate cyber security student studing in Mahendra Engineering College </p>
  </section>

  <section id="skills" class="skills">
    <h2>My Skills</h2>
    <ul>
      <li>penetrating tester</li>
      <li>web developer</li>
      <li>python programming</li>
     
    </ul>
  </section>

  <section id="projects" class="projects">
    <h2>My Projects</h2>
    <div class="project">
      <h3>vintage vault</h3>
      <p>the pericious things in india</p>
    </div>
    <div class="project">
      <h3>vintage vault</h3>
      <p>the precious things in india </p>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>6678909843</h2>
    <p>Email: dhanusridhanu46@gmail.com</p>
    <p>LinkedIn: Dhanusri S</p>
    <p>GitHub: dhanusri224</p>
  </section>

  <footer>
    <p>© 2025 Dhanusri. All Rights Reserved.</p>
  </footer>
</body>
</html>
