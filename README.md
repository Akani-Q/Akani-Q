<style>
  @keyframes pulse {
    0%, 100% { transform: scale(1); opacity: 0.8; }
    50% { transform: scale(1.05); opacity: 1; }
  }
  @keyframes draw {
    0% { stroke-dashoffset: 300; }
    100% { stroke-dashoffset: 0; }
  }
  @keyframes glow {
    0%, 100% { filter: drop-shadow(0 0 10px rgba(0, 200, 255, 0.3)); }
    50% { filter: drop-shadow(0 0 25px rgba(0, 200, 255, 0.8)); }
  }
  .shield { animation: pulse 2s ease-in-out infinite, glow 2s ease-in-out infinite; }
  .check { stroke-dasharray: 300; stroke-dashoffset: 300; animation: draw 1.5s ease-in-out infinite alternate; }
</style>

<p align="center">
  <svg width="150" height="150" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg">
    <path class="shield" d="M75 10 L140 40 L140 85 C140 125 115 150 75 165 C35 150 10 125 10 85 L10 40 L75 10Z"
          fill="#0a1a3a" stroke="#00ccff" stroke-width="3"/>
    <path d="M75 20 L132 46 L132 85 C132 120 110 143 75 155 C40 143 18 120 18 85 L18 46 L75 20Z"
          fill="none" stroke="#00ccff" stroke-width="1" opacity="0.5"/>
    <path class="check" d="M50 75 L68 93 L105 55" fill="none" stroke="#00ff88" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
  </svg>
</p>

# Akani-Q

## Popular repositories
