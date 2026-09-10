<!-- ANIMATED HEADER WITH SPINNER & COMPLETION -->
<p align="center">
  <svg width="600" height="140" viewBox="0 0 600 140" xmlns="http://www.w3.org/2000/svg">
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@700;800&display=swap');
      
      .text-type {
        font-family: 'Fira Code', monospace;
        font-size: 22px;
        font-weight: 800;
        fill: #FF2A74;
        white-space: pre;
        overflow: hidden;
        border-right: 3px solid #FF2A74;
        animation: typing 3s steps(30, end) infinite alternate;
      }

      /* TEXT TYPING ANIMATION */
      @keyframes typing {
        0%, 10% { width: 0; }
        50%, 90% { width: 100%; }
      }

      /* SPINNER ROTATION */
      .spinner {
        transform-origin: 300px 85px;
        animation: spin 1.5s linear infinite, fadeSpinner 6s ease-in-out infinite;
      }

      @keyframes spin {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
      }

      /* SPINNER VISIBILITY CYCLE */
      @keyframes fadeSpinner {
        0%, 35% { opacity: 0; }
        40%, 75% { opacity: 1; }
        80%, 100% { opacity: 0; }
      }

      /* SUCCESS GLOW ANIMATION */
      .success-glow {
        font-family: 'Fira Code', monospace;
        font-size: 14px;
        font-weight: 700;
        fill: #00FFCC;
        animation: pulseGlow 6s ease-in-out infinite;
      }

      @keyframes pulseGlow {
        0%, 75% { opacity: 0; transform: scale(0.95); }
        80% { opacity: 1; transform: scale(1.05); }
        85%, 95% { opacity: 1; transform: scale(1); filter: drop-shadow(0 0 8px #00FFCC); }
        100% { opacity: 0; }
      }
    </style>

    <!-- TYPING TEXT -->
    <g transform="translate(0, 30)">
      <text x="50%" y="0" dominant-baseline="middle" text-anchor="middle" class="text-type">
        Welcome to my profile! 👋
      </text>
    </g>

    <!-- LOADING SPINNER -->
    <circle class="spinner" cx="300" cy="85" r="12" stroke="#FF2A74" stroke-width="3" stroke-dasharray="50 20" fill="none" />

    <!-- COMPLETION STATUS -->
    <text x="50%" y="125" dominant-baseline="middle" text-anchor="middle" class="success-glow">
      [ SYSTEM READY / ACCESS GRANTED ]
    </text>
  </svg>
</p>

<!-- TELEMETRY SEPARATOR -->
<p align="center">
  <h2><font color="#FF2A74"><code>// SYSTEM TELEMETRY</code></font></h2>
</p>

<!-- STATS GRID SECTION -->
<table border="0" align="center" cellspacing="0" cellpadding="0">
  <tr>
    <!-- LEFT COLUMN: Recent Activity Card -->
    <td rowspan="2" valign="middle" align="center">
      <img src="https://ghstats.dev/api/card?username=YosetPiedrahita-svg&theme=radical&border_radius=12&custom_title=Recent+Activity&hide=repos%2Ctrend%2Cstars%2Cissues" alt="Recent Activity" width="410" />
    </td>
    <!-- RIGHT COLUMN TOP: Sparkline -->
    <td valign="bottom" align="center">
      <img src="https://ghstats.dev/api/sparkline?username=YosetPiedrahita-svg&theme=radical&days=30&width=330&height=100" alt="Sparkline 30 days" />
    </td>
  </tr>
  <tr>
    <!-- RIGHT COLUMN BOTTOM: Top Languages -->
    <td valign="top" align="center">
      <img src="https://ghstats.dev/api/langs?username=YosetPiedrahita-svg&theme=radical&custom_title=Top+Languages&layout=vertical_list" alt="Top Languages" width="330" />
    </td>
  </tr>
</table>

<br>
