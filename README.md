<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Music Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: linear-gradient(135deg, #1e1e2f, #2a2a4a);
      color: white;
      text-align: center;
    }
    header {
      padding: 40px;
      background: rgba(0, 0, 0, 0.6);
    }
    header h1 {
      font-size: 2.5rem;
      margin: 0;
    }
    header p {
      font-size: 1.2rem;
    }
    nav {
      margin: 20px 0;
    }
    nav a {
      color: #ffcc00;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .section {
      padding: 50px 20px;
    }
    .music-player {
      margin-top: 20px;
    }
    audio {
      width: 80%;
      max-width: 400px;
      border-radius: 10px;
      margin-top: 10px;
    }
    footer {
      padding: 20px;
      background: rgba(0,0,0,0.6);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>🎵 My Music Portfolio 🎶</h1>
    <p>Welcome to my digital space of melodies and rhythms</p>
  </header>

  <nav>
    <a href="#about">About Me</a>
    <a href="#projects">My Music</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>Hello! I am passionate about music. I create, remix, and explore different sounds.  
       This portfolio showcases my journey in music.</p>
  </section>

  <section id="projects" class="section">
    <h2>My Music</h2>
    <p>Listen to some of my featured tracks:</p>
    <div class="music-player">
      <p>Track 1: My First Composition</p>
      <audio controls>
        <source src="music1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </div>
    <div class="music-player">
      <p>Track 2: Experimental Beats</p>
      <audio controls>
        <source src="music2.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
    <p>Follow me on social media:  
      <a href="#">Instagram</a> | 
      <a href="#">YouTube</a> | 
      <a href="#">Spotify</a>
    </p>
  </section>

  <footer>
    <p>© 2025 My Music Portfolio | Designed with ❤️ and 🎧</p>
  </footer>

</body>
</html>
