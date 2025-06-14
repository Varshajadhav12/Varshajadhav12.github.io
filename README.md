File 1:index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Varsha Jadhav | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Varsha Jadhav</h1>
    <p>BCS Student | Aspiring Software Developer</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#certifications">Certifications</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Hi! I'm Varsha Jadhav, a second-year BCS student at Deogiri Institute of Technology and Management Studies, Chhatrapati Sambhaji Nagar. I'm passionate about software development, databases, and data visualization. I enjoy learning new technologies and building real-world projects. Currently, I’m looking for internships or entry-level roles in IT to gain industry experience and grow my skills.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Python (Certified)</li>
      <li>Java (Learning)</li>
      <li>SQL & RDBMS</li>
      <li>Data Visualization (Forage Certificate)</li>
      <li>Public Speaking & Communication</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>
        <strong>Library Management System (Java)</strong> – A console-based application to manage book records, lending, and users.
      </li>
      <li>
        <strong>Student Database Project (SQL)</strong> – Created a relational database with queries, joins, and views to manage academic records.
      </li>
      <li>
        <strong>Python Mini Tools</strong> – Created tools like calculator, number guessing game, and password generator using Python basics.
      </li>
    </ul>
  </section>

  <section id="certifications">
    <h2>Certifications</h2>
    <ul>
      <li><a href="https://www.theforage.com" target="_blank">Data Visualization Certificate – Forage</a></li>
      <li>Introduction to Python – (Analytics vidhya)</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:jadhavruuhh@email.com">jadhavruuhh@email.com</a></p>
    <p>GitHub: <a href="https://github.com/varshajadhav12" target="_blank">github.com/varshajadhav12</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/varsha-jadhav-135a30319" target="_blank">www.linkedin.com/in/varsha-jadhav-135a30319</a></p>
  </section>

  <footer>
    <p>© 2025 Varsha Jadhav</p>
  </footer>
</body>
</html>

File 2: style.css
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 1rem 2rem;
  text-align: center;
}

nav {
  display: flex;
  justify-content: center;
  background: #444;
  padding: 0.5rem;
}

nav a {
  color: #fff;
  margin: 0 1rem;
  text-decoration: none;
}

nav a:hover {
  text-decoration: underline;
}

section {
  padding: 2rem;
  max-width: 800px;
  margin: auto;
}

ul {
  list-style: square;
  padding-left: 20px;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #333;
  color: #fff;
}
