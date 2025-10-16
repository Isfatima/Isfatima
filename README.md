<head>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    .header {
      font-size: 2rem;
      font-weight: bold;
      margin-bottom: 1rem;
      animation: wave 2s infinite;
    }
    @keyframes wave {
      0% { transform: rotate(0deg); }
      25% { transform: rotate(15deg); }
      50% { transform: rotate(-10deg); }
      75% { transform: rotate(10deg); }
      100% { transform: rotate(0deg); }
    }
    .content h1 {
      color: #6f42c1;
    }
    .section {
      margin-top: 1rem;
      padding: 0.5rem;
      border-left: 4px solid #6f42c1;
    }
    .emoji {
      font-size: 1.2rem;
    }
  </style>
</head>

<body>
  <div class="header">
    Hello there! 👋
  </div>

  <div class="content">
    <h1>Welcome to my GitHub corner!</h1>

    <div class="section">
      <p class="emoji">✨</p>
      <p>If you know me from <strong>academics</strong>: I am a 5th-year Electrical & Embedded Systems student, passionate about robotics, electronics, and AI-enabled systems.</p>
    </div>

    <div class="section">
      <p class="emoji">🧰</p>
      <p>If we’ve collaborated on <strong>projects</strong>: I have designed interactive robotic devices using C++, ROS2, ESP32, and tactile sensors for human-robot interaction.</p>
    </div>

    <div class="section">
      <p class="emoji">🚀</p>
      <p>If you’re exploring my GitHub casually: I love experimenting, coding challenges, and continuously expanding my skills with real-world robotics and embedded systems projects.</p>
    </div>

    <div class="section">
      <p class="emoji">📫</p>
      <p>Feel free to reach out or explore my repositories — each project has a story and a lesson!</p>
    </div>
  </div>
</body>
