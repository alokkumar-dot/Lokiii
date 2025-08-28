<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alok's Website</title>
  <style>
    body {
      background-color: orange;
      font-family: Arial, sans-serif;
      text-align: center;
      color: white;
      margin: 0;
      padding: 0;
    }
    h1 {
      margin-top: 100px;
      font-size: 2.5em;
      white-space: nowrap;
      overflow: hidden;
      border-right: 4px solid white;
      width: 0;
      animation: typing 3s steps(30, end) forwards,
                 blink 0.75s step-end infinite;
    }
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }
    @keyframes blink {
      from, to { border-color: transparent; }
      50% { border-color: white; }
    }
    p {
      font-size: 1.2em;
      margin-top: 20px;
    }
    .btn {
      display: inline-block;
      margin-top: 30px;
      padding: 12px 25px;
      background: white;
      color: orange;
      font-weight: bold;
      text-decoration: none;
      border-radius: 8px;
      transition: 0.3s;
    }
    .btn:hover {
      background: #ffd580;
      color: black;
    }
    .chatbox {
      margin-top: 40px;
      width: 350px;
      height: 400px;
      border: none;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>
  <h1>Hello, I’m Alok 👋</h1>
  <p>Welcome to my first GitHub Pages website 🚀</p>
  <a href="https://github.com/alokkumar-dot" class="btn">Visit My GitHub</a>

  <h2 style="margin-top:50px;">💬 Chat with my Bot</h2>
  <!-- Replace src link with your HuggingFace/Tidio chatbot later -->
  <iframe class="chatbox" src="https://example.com" title="Chatbot"></iframe>
</body>
</html>
