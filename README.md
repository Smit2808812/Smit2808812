<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Smit Prajapati | Full Stack Developer</title>
  <style>
    :root {
      --bg-color: #f0fff0;
      --card-bg: #ffffff;
      --text-color: #333333;
      --accent: #ff4c4c;
      --accent-dark: #e04343;
      --font: 'Lexend Deca', sans-serif;
    }

    body {
      font-family: var(--font);
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      font-size: 2.5rem;
      color: var(--accent);
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      color: #555;
    }

    .section {
      width: 90%;
      max-width: 900px;
      background-color: var(--card-bg);
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 30px;
      margin: 20px 0;
    }

    .section h2 {
      color: var(--accent);
      margin-bottom: 10px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin: 8px 0;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      color: var(--accent-dark);
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: var(--bg-color);
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    footer {
      text-align: center;
      padding: 30px 0;
      font-size: 0.9rem;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>👋 Hey, I'm Smit Prajapati</h1>
    <p>🚀 Full Stack Developer | Software Engineer | Tech Enthusiast | Innovator</p>
  </header>

  <section class="section">
    <h2>💡 About Me</h2>
    <ul>
      <li>🎓 Passionate Full Stack Developer with expertise in the MERN Stack (MongoDB, Express, React, Node.js)</li>
      <li>🧠 Focused on writing clean, maintainable, and scalable code</li>
      <li>💻 Builder of innovative web solutions and interactive interfaces</li>
      <li>🏗️ Experienced in creating real-world projects with authentication, APIs, and dashboards</li>
      <li>📈 Always learning, exploring, and adapting to new technologies</li>
    </ul>
  </section>

  <section class="section">
    <h2>🛠️ Tech Stack</h2>
    <ul>
      <li><strong>Frontend:</strong> React.js, HTML, CSS, JavaScript, TailwindCSS</li>
      <li><strong>Backend:</strong> Node.js, Express.js, REST APIs</li>
      <li><strong>Database:</strong> MongoDB, Mongoose</li>
      <li><strong>Tools:</strong> Git, GitHub, Postman, VS Code</li>
    </ul>
  </section>

  <section class="section">
    <h2>🌟 Featured Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Project 1</h3>
        <p>A modern web application with a clean interface and real-time data integration.</p>
        <p><strong>Tech:</strong> MERN Stack</p>
      </div>
      <div class="project-card">
        <h3>Project 2</h3>
        <p>A full-featured platform designed for efficient task management and collaboration.</p>
        <p><strong>Tech:</strong> React, Node.js, MongoDB</p>
      </div>
    </div>
  </section>

  <section class="section">
    <h2>🌍 Connect with Me</h2>
    <ul>
      <li>💼 <a href="#">LinkedIn</a></li>
      <li>🐦 <a href="#">Twitter</a></li>
      <li>📧 <a href="mailto:smitprajapati@example.com">smitprajapati@example.com</a></li>
    </ul>
  </section>

  <footer>
    ⭐ "Code, Learn, Build, Repeat."  
    <br>© 2025 Smit Prajapati
  </footer>
</body>
</html>
