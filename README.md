# Youtube
For my youtube
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kemtan | YouTube Channel</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-color: #0f0f0f;
      --primary-color: #00ffff;
      --text-color: #ffffff;
      --accent-color: #ff0080;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: var(--bg-color);
      color: var(--text-color);
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #111, #222);
      padding: 3em 1em;
      text-align: center;
      border-bottom: 2px solid var(--primary-color);
    }

    header h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      color: var(--primary-color);
    }

    header p {
      font-size: 1.2rem;
      color: #aaa;
      margin-top: 0.5em;
    }

    section {
      padding: 2em 1em;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      font-size: 2rem;
      color: var(--accent-color);
      margin-bottom: 1em;
      border-bottom: 1px solid #444;
      padding-bottom: 0.3em;
    }

    p {
      margin-bottom: 1.5em;
    }

    iframe {
      width: 100%;
      max-width: 100%;
      height: 400px;
      border: none;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.2);
      transition: transform 0.3s ease;
    }

    iframe:hover {
      transform: scale(1.02);
    }

    .social a {
      display: inline-block;
      background: var(--primary-color);
      color: #000;
      padding: 0.8em 1.5em;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 1em;
      transition: background 0.3s;
    }

    .social a:hover {
      background: var(--accent-color);
      color: white;
    }

    footer {
      text-align: center;
      padding: 1.5em;
      background: #111;
      color: #888;
      font-size: 0.9rem;
      border-top: 1px solid #222;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2rem;
      }

      iframe {
        height: 220px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Kemtan</h1>
    <p>Challenge videos and daily vlogs — all in English!</p>
  </header>

  <section>
    <h2>🎥 About the Channel</h2>
    <p>
      On this channel, I post various challenge videos and casual daily content, mainly in English.
      The upload frequency depends on when editing is finished — stay tuned!
    </p>
  </section>

  <section>
    <h2>📺 Latest Video</h2>
    <iframe src="https://www.youtube.com/embed?list=UUYgntkvVQYOYQLg6Pybx3vQ" allowfullscreen></iframe>
  </section>

  <section class="social" style="text-align: center;">
    <h2>🔗 Follow Me</h2>
    <a href="https://www.youtube.com/@Kemtan_1730" target="_blank">Subscribe on YouTube</a>
  </section>

  <footer>
    &copy; 2025 Kemtan. All rights reserved.
  </footer>
</body>
</html>
