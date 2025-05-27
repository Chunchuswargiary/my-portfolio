# my-portfolio
My portfolio which i made myself using Html, Css and javascript
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chunchu Swargiary | Developer & AI Explorer</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="syles.css" />
</head>
<body>
  <div class="overlay"></div>
  <div class="container">
    <div class="intro">
      <h1>👋 Hi, I'm Chunchu</h1>
      <h2>Developer | Musician | AI Explorer</h2>
      <p>Welcome to my digital portfolio. Here, you’ll discover who I am, what I do, and what I dream of building next 🚀</p>
    </div>

    <div class="nav-buttons">
      <button onclick="showSection('greeting')">Greetings</button>
      <button onclick="showSection('about')">About Me</button>
      <button onclick="showSection('skills')">Technical Skills</button>
      <button onclick="showSection('projects')">Projects</button>
      <button onclick="showSection('softskills')">Soft Skills</button>
      <button onclick="showSection('contact')">Contact</button>
    </div>

    <div class="content-section" id="greeting">
      <h2>Warm Greetings 🙌</h2>
      <p>Welcome to my creative space! 🌟 This is where code meets creativity, and where ideas are transformed into real-life applications. I’m thrilled you’re here. Whether you're a recruiter, a friend, or a fellow coder — let’s explore the techie-musician hybrid world I live in!</p>
      <div class="quote-box">
        "Don’t just learn to code. Learn to create, to explore, to inspire." — Chunchu
      </div>
    </div>

    <div class="content-section" id="about">
      <h2>About Me</h2>
      <p>I'm Chunchu Swargiary — a 2nd-year Computer Science Engineering student from Assam Downtown University, specializing in Cloud Technology & Information Security. I believe that tech isn’t just about machines — it’s about what we can do with them to make lives better.</p>
      <p>When I’m not coding or designing UIs, I’m often composing tunes, diving into AI research papers, or thinking up wild ideas to build next.</p>
    </div>

    <div class="content-section" id="skills">
      <h2>Technical Skills</h2>
      <ul>
        <li><strong>Languages:</strong> C, Python, Java</li>
        <li><strong>Web Stack:</strong> HTML, CSS, JavaScript</li>
        <li><strong>Tools:</strong> Git, GitHub, MySQL, MongoDB</li>
        <li><strong>Concepts:</strong> Cybersecurity, AI/ML Basics</li>
      </ul>
    </div>

    <div class="content-section" id="projects">
      <h2>Projects</h2>
      <div class="projects">
        <div class="card">
          <h3>🌐 Personal Portfolio</h3>
          <p>This very website! Designed from scratch to reflect my passion, creativity, and growth as a developer.</p>
        </div>
        <div class="card">
          <h3>🎵 AI Lyrics Generator</h3>
          <p>A Python-based app that generates unique song lyrics using ML techniques. Music + AI = ❤️</p>
        </div>
        <div class="card">
          <h3>🔐 Password Validator CLI</h3>
          <p>A terminal-based C program that evaluates password strength and gives secure suggestions.</p>
        </div>
      </div>
    </div>

    <div class="content-section" id="softskills">
      <h2>Soft Skills</h2>
      <ul>
        <li>🎸 Musician & Creative Thinker</li>
        <li>💬 Strong Communicator & Listener</li>
        <li>🧠 Curious Learner & Problem Solver</li>
        <li>🌈 Team Player with a Positive Attitude</li>
      </ul>
    </div>

    <div class="content-section" id="contact">
      <h2>Let's Connect 🤝</h2>
      <p>💌 Email: <a href="mailto:your.email@example.com">chanchupfu@gmail.com</a></p>
      <p>🔗 LinkedIn: <a href="https://www.linkedin.com/in/chunchuswargiary3104/" target="_blank">/chunchuswargiary3104</a></p>
      <p>🐙 GitHub: <a href="https://github.com/Chunchuswargiary" target="_blank">/Chunchuswargiary</a></p>
    </div>

    <div class="social-links">
      <a href="https://www.linkedin.com/in/chunchuswargiary3104/" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/Chunchuswargiary" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://twitter.com/yourprofile" target="_blank"><i class="fab fa-twitter"></i></a>
      <a href="https://reddit.com/user/yourprofile" target="_blank"><i class="fab fa-reddit"></i></a>
    </div>

    <footer>
      &copy; 2025 Chunchu Swargiary | Made with ☕, 🎸 & 💻 from the heart of Assam ❤️
    </footer>
  </div>

  <script>
    function showSection(id) {
      document.querySelectorAll('.content-section').forEach(sec => sec.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>
</body>
</html>
