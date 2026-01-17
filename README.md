<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fachriditya | Interactive Profile</title>
  <style>
    :root {
      --bg: #0d1117;
      --card: #161b22;
      --text: #c9d1d9;
      --accent: #58a6ff;
    }

    * {
      box-sizing: border-box;
      font-family: "Segoe UI", system-ui, sans-serif;
    }

    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
    }

    header {
      height: 220px;
      background: linear-gradient(120deg, #1f6feb, #8250df);
      display: flex;
      align-items: center;
      justify-content: center;
      animation: gradient 6s ease infinite;
    }

    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header h1 {
      font-size: 2.4rem;
      color: white;
      letter-spacing: 1px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 24px;
    }

    .card {
      background: var(--card);
      border-radius: 14px;
      padding: 24px;
      margin-bottom: 24px;
      box-shadow: 0 8px 24px rgba(0,0,0,.35);
    }

    .about {
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 20px;
      align-items: center;
    }

    .about img {
      width: 100%;
      border-radius: 12px;
    }

    h2 {
      color: var(--accent);
      margin-top: 0;
    }

    details summary {
      cursor: pointer;
      font-weight: bold;
      margin-bottom: 10px;
    }

    ul {
      padding-left: 20px;
    }

    .hobby {
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 20px;
      align-items: center;
    }

    .hobby img {
      width: 100%;
      border-radius: 12px;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      opacity: .6;
    }
  </style>
</head>
<body>

  <header>
    <h1>👋 Hi, I'm Fachriditya</h1>
  </header>

  <main class="container">

    <section class="card about">
      <div>
        <h2>👨‍💻 About Me</h2>
        <p>I'm an <strong>Informatics Engineering</strong> student at <strong>Airlangga University</strong>, class of 2024.</p>
        <p>I’m deeply interested in web development, game development, databases, cybersecurity, and both hardware & software systems.</p>
        <p>Currently learning by building projects independently and exploring new technologies.</p>
      </div>
      <img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" alt="Bye cat" />
    </section>

    <section class="card">
      <h2>🛠️ Languages & Tools</h2>
      <details open>
        <summary>💻 Languages</summary>
        <ul>
          <li>Python</li>
          <li>Java</li>
          <li>JavaScript</li>
        </ul>
      </details>
      <details>
        <summary>🌐 Web</summary>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>Laravel</li>
        </ul>
      </details>
      <details>
        <summary>🗄️ Tools</summary>
        <ul>
          <li>Git</li>
          <li>Linux</li>
          <li>MySQL</li>
        </ul>
      </details>
    </section>

    <section class="card">
      <h2>📂 Projects</h2>
      <details open>
        <summary>🎓 Student Tasks</summary>
        <ul>
          <li>PBD Project – MySQL & Laravel</li>
          <li>PWBF Project – Laravel</li>
        </ul>
      </details>
      <details>
        <summary>💼 Development</summary>
        <ul>
          <li>Personal Portfolio Website</li>
        </ul>
      </details>
    </section>

    <section class="card hobby">
      <div>
        <h2>🎯 Hobbies</h2>
        <ul>
          <li>🎮 Games (ML, Valorant, Clash Royale)</li>
          <li>🎬 Anime & K-Drama</li>
          <li>📖 Manga & Novel</li>
          <li>🎸 Guitar & Singing</li>
          <li>🏃 Running, Basketball, Volleyball, Cycling</li>
        </ul>
      </div>
      <img src="https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif" alt="Coding chill" />
    </section>

  </main>

  <footer>
    © 2026 Fachriditya • Built with ❤️ and curiosity
  </footer>

</body>
</html>
