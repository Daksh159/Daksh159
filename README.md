# Hi 👋 I'm Daksh

Welcome to my GitHub profile!

<p align="center">
  <img src="./profile-3d-contrib/profile-night-view.svg" />
</p>



<svg viewBox="0 0 900 260" width="100%" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <style>
      /* Stars scrolling */
      .star {
        animation: stars 6s linear infinite;
        opacity: 0.8;
      }
      @keyframes stars {
        from { transform: translateY(0); }
        to { transform: translateY(260px); }
      }

      /* Enemy blocks falling */
      .enemy {
        animation: fall 4s linear infinite;
      }
      .enemy:nth-child(2) { animation-delay: 1s; }
      .enemy:nth-child(3) { animation-delay: 2s; }
      .enemy:nth-child(4) { animation-delay: 3s; }

      @keyframes fall {
        from { transform: translateY(-40px); }
        to { transform: translateY(300px); }
      }

      /* Bullet shooting */
      .bullet {
        animation: shoot 0.9s linear infinite;
      }
      @keyframes shoot {
        from { transform: translateY(0); opacity: 1; }
        to { transform: translateY(-200px); opacity: 0; }
      }

      /* Subtle glow */
      .glow {
        filter: drop-shadow(0 0 6px #58a6ff);
      }
    </style>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="#0d1117"/>

  <!-- Stars -->
  <g fill="#ffffff">
    <circle cx="120" cy="20" r="1.2" class="star"/>
    <circle cx="300" cy="90" r="1" class="star"/>
    <circle cx="520" cy="40" r="1.3" class="star"/>
    <circle cx="700" cy="130" r="1.1" class="star"/>
    <circle cx="840" cy="60" r="1" class="star"/>
  </g>

  <!-- Enemies (contribution blocks vibe) -->
  <g fill="#2ea043">
    <rect x="200" y="0" width="14" height="14" class="enemy"/>
    <rect x="360" y="0" width="14" height="14" class="enemy"/>
    <rect x="520" y="0" width="14" height="14" class="enemy"/>
    <rect x="680" y="0" width="14" height="14" class="enemy"/>
  </g>

  <!-- Player aircraft -->
  <polygon
    points="450,210 440,235 450,225 460,235"
    fill="#58a6ff"
    class="glow"
  />

  <!-- Bullet -->
  <rect x="447" y="195" width="6" height="16" fill="#ffd33d" class="bullet"/>

  <!-- HUD Text -->
  <text x="50%" y="245" text-anchor="middle"
        fill="#8b949e" font-size="12" font-family="monospace">
    GITHUB ACTIVITY · AIRCRAFT MODE
  </text>

</svg>

