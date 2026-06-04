## Hi there 👋

<svg width="1500" height="500" viewBox="0 0 1500 500" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Dark background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0f1e;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#0d1b2a;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0a1628;stop-opacity:1" />
    </linearGradient>

    <!-- Accent gradient for lines -->
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00c6ff;stop-opacity:0" />
      <stop offset="30%" style="stop-color:#00c6ff;stop-opacity:1" />
      <stop offset="70%" style="stop-color:#7b2ff7;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#7b2ff7;stop-opacity:0" />
    </linearGradient>

    <!-- Glow filter -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Soft glow for circles -->
    <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="20" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Grid pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#ffffff" stroke-width="0.3" opacity="0.08"/>
    </pattern>

    <!-- Dot pattern -->
    <pattern id="dots" width="30" height="30" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1" fill="#00c6ff" opacity="0.15"/>
    </pattern>
  </defs>

  <!-- Background -->
  <rect width="1500" height="500" fill="url(#bgGrad)"/>

  <!-- Grid overlay -->
  <rect width="1500" height="500" fill="url(#grid)"/>

  <!-- Dot pattern right side -->
  <rect x="900" y="0" width="600" height="500" fill="url(#dots)" opacity="0.6"/>

  <!-- Decorative orbs -->
  <circle cx="180" cy="120" r="120" fill="#00c6ff" opacity="0.04" filter="url(#softGlow)"/>
  <circle cx="1350" cy="380" r="150" fill="#7b2ff7" opacity="0.06" filter="url(#softGlow)"/>
  <circle cx="750" cy="500" r="100" fill="#00c6ff" opacity="0.03" filter="url(#softGlow)"/>

  <!-- Top accent line -->
  <rect x="0" y="0" width="1500" height="2" fill="url(#accentGrad)" opacity="0.8"/>

  <!-- Bottom accent line -->
  <rect x="0" y="498" width="1500" height="2" fill="url(#accentGrad)" opacity="0.8"/>

  <!-- Vertical accent line left -->
  <rect x="80" y="60" width="1" height="380" fill="#00c6ff" opacity="0.2"/>

  <!-- Small decorative squares -->
  <rect x="77" y="57" width="7" height="7" fill="#00c6ff" opacity="0.6"/>
  <rect x="77" y="436" width="7" height="7" fill="#7b2ff7" opacity="0.6"/>

  <!-- Circuit-like decorative lines -->
  <line x1="1100" y1="80" x2="1200" y2="80" stroke="#00c6ff" stroke-width="0.8" opacity="0.3"/>
  <line x1="1200" y1="80" x2="1200" y2="140" stroke="#00c6ff" stroke-width="0.8" opacity="0.3"/>
  <line x1="1200" y1="140" x2="1350" y2="140" stroke="#00c6ff" stroke-width="0.8" opacity="0.3"/>
  <circle cx="1100" cy="80" r="3" fill="#00c6ff" opacity="0.5"/>
  <circle cx="1350" cy="140" r="3" fill="#00c6ff" opacity="0.5"/>

  <line x1="1050" y1="380" x2="1050" y2="420" stroke="#7b2ff7" stroke-width="0.8" opacity="0.3"/>
  <line x1="1050" y1="420" x2="1400" y2="420" stroke="#7b2ff7" stroke-width="0.8" opacity="0.3"/>
  <circle cx="1050" cy="380" r="3" fill="#7b2ff7" opacity="0.5"/>
  <circle cx="1400" cy="420" r="3" fill="#7b2ff7" opacity="0.5"/>

  <!-- Tag label -->
  <rect x="108" y="100" width="160" height="28" rx="4" fill="#00c6ff" opacity="0.1" stroke="#00c6ff" stroke-width="0.8" stroke-opacity="0.4"/>
  <text x="188" y="119" font-family="'Courier New', monospace" font-size="12" fill="#00c6ff" opacity="0.9" text-anchor="middle" letter-spacing="2">INDEPENDENT RESEARCHER</text>

  <!-- Main name -->
  <text x="108" y="210" font-family="Georgia, 'Times New Roman', serif" font-size="88" font-weight="700" fill="#ffffff" opacity="0.97" letter-spacing="-2" filter="url(#glow)">Harshit</text>

  <!-- Accent line under name -->
  <rect x="108" y="225" width="320" height="2" fill="url(#accentGrad)" opacity="0.9"/>

  <!-- Subtitle line 1 -->
  <text x="108" y="280" font-family="'Courier New', monospace" font-size="18" fill="#00c6ff" opacity="0.85" letter-spacing="1">AI &amp; Future of Work</text>

  <!-- Subtitle line 2 -->
  <text x="108" y="315" font-family="Georgia, serif" font-size="16" fill="#a0b4c8" opacity="0.75" letter-spacing="0.5">Studying how automation reshapes careers and businesses in India</text>

  <!-- Divider -->
  <rect x="108" y="345" width="600" height="1" fill="#ffffff" opacity="0.08"/>

  <!-- Stats row -->
  <!-- Stat 1 -->
  <text x="108" y="380" font-family="Georgia, serif" font-size="26" font-weight="700" fill="#ffffff" opacity="0.95">9</text>
  <text x="108" y="400" font-family="'Courier New', monospace" font-size="11" fill="#7b8fa0" opacity="0.8" letter-spacing="1">CAREERS ANALYZED</text>

  <!-- Divider dot -->
  <circle cx="235" cy="385" r="2" fill="#00c6ff" opacity="0.4"/>

  <!-- Stat 2 -->
  <text x="255" y="380" font-family="Georgia, serif" font-size="26" font-weight="700" fill="#ffffff" opacity="0.95">2</text>
  <text x="255" y="400" font-family="'Courier New', monospace" font-size="11" fill="#7b8fa0" opacity="0.8" letter-spacing="1">FIELD CASE STUDIES</text>

  <!-- Divider dot -->
  <circle cx="400" cy="385" r="2" fill="#7b2ff7" opacity="0.4"/>

  <!-- Stat 3 -->
  <text x="420" y="380" font-family="Georgia, serif" font-size="26" font-weight="700" fill="#ffffff" opacity="0.95">2030</text>
  <text x="420" y="400" font-family="'Courier New', monospace" font-size="11" fill="#7b8fa0" opacity="0.8" letter-spacing="1">RESEARCH HORIZON</text>

  <!-- DOI badge -->
  <rect x="108" y="428" width="90" height="24" rx="4" fill="#7b2ff7" opacity="0.25" stroke="#7b2ff7" stroke-width="0.8" stroke-opacity="0.6"/>
  <text x="153" y="444" font-family="'Courier New', monospace" font-size="11" fill="#b39dff" text-anchor="middle" letter-spacing="1">ZENODO DOI</text>

  <rect x="210" y="428" width="110" height="24" rx="4" fill="#00c6ff" opacity="0.1" stroke="#00c6ff" stroke-width="0.8" stroke-opacity="0.4"/>
  <text x="265" y="444" font-family="'Courier New', monospace" font-size="11" fill="#00c6ff" text-anchor="middle" letter-spacing="1">YOUTH KI AWAAZ</text>

  <rect x="332" y="428" width="80" height="24" rx="4" fill="#00c6ff" opacity="0.1" stroke="#00c6ff" stroke-width="0.8" stroke-opacity="0.4"/>
  <text x="372" y="444" font-family="'Courier New', monospace" font-size="11" fill="#00c6ff" text-anchor="middle" letter-spacing="1">PROTOTYPE</text>

  <!-- Right side — decorative data visualization -->
  <!-- Vertical bars -->
  <g opacity="0.6">
    <rect x="950" y="320" width="18" height="100" rx="3" fill="#00c6ff" opacity="0.15"/>
    <rect x="950" y="197" width="18" height="123" rx="3" fill="#00c6ff" opacity="0.7" filter="url(#glow)"/>
    <text x="959" y="190" font-family="'Courier New', monospace" font-size="10" fill="#00c6ff" text-anchor="middle" opacity="0.8">23</text>

    <rect x="984" y="320" width="18" height="100" rx="3" fill="#00c6ff" opacity="0.15"/>
    <rect x="984" y="205" width="18" height="115" rx="3" fill="#00c6ff" opacity="0.65"/>
    <text x="993" y="198" font-family="'Courier New', monospace" font-size="10" fill="#00c6ff" text-anchor="middle" opacity="0.8">22</text>

    <rect x="1018" y="320" width="18" height="100" rx="3" fill="#00c6ff" opacity="0.15"/>
    <rect x="1018" y="205" width="18" height="115" rx="3" fill="#00c6ff" opacity="0.65"/>

    <rect x="1052" y="320" width="18" height="100" rx="3" fill="#00c6ff" opacity="0.15"/>
    <rect x="1052" y="225" width="18" height="95" rx="3" fill="#4a9fd4" opacity="0.6"/>

    <rect x="1086" y="320" width="18" height="100" rx="3" fill="#00c6ff" opacity="0.15"/>
    <rect x="1086" y="235" width="18" height="85" rx="3" fill="#4a9fd4" opacity="0.55"/>

    <rect x="1120" y="320" width="18" height="100" rx="3" fill="#7b2ff7" opacity="0.15"/>
    <rect x="1120" y="235" width="18" height="85" rx="3" fill="#9b6fd4" opacity="0.5"/>

    <rect x="1154" y="320" width="18" height="100" rx="3" fill="#7b2ff7" opacity="0.15"/>
    <rect x="1154" y="255" width="18" height="65" rx="3" fill="#9b6fd4" opacity="0.45"/>

    <rect x="1188" y="320" width="18" height="100" rx="3" fill="#7b2ff7" opacity="0.15"/>
    <rect x="1188" y="265" width="18" height="55" rx="3" fill="#9b6fd4" opacity="0.4"/>

    <rect x="1222" y="320" width="18" height="100" rx="3" fill="#e74c3c" opacity="0.15"/>
    <rect x="1222" y="305" width="18" height="15" rx="3" fill="#e74c3c" opacity="0.5"/>
    <text x="1231" y="298" font-family="'Courier New', monospace" font-size="10" fill="#e74c3c" text-anchor="middle" opacity="0.8">10</text>
  </g>

  <!-- Chart label -->
  <rect x="950" y="325" width="290" height="1" fill="#ffffff" opacity="0.1"/>
  <text x="1095" y="345" font-family="'Courier New', monospace" font-size="10" fill="#7b8fa0" text-anchor="middle" letter-spacing="1" opacity="0.7">AI CAREER RESILIENCE INDEX</text>

  <!-- Chart title -->
  <text x="1095" y="165" font-family="'Courier New', monospace" font-size="11" fill="#00c6ff" text-anchor="middle" letter-spacing="2" opacity="0.6">RESEARCH FINDINGS</text>

  <!-- Floating data points -->
  <circle cx="1300" cy="200" r="4" fill="#00c6ff" opacity="0.4"/>
  <circle cx="1350" cy="240" r="2" fill="#7b2ff7" opacity="0.5"/>
  <circle cx="1400" cy="180" r="3" fill="#00c6ff" opacity="0.3"/>
  <circle cx="1420" cy="300" r="5" fill="#7b2ff7" opacity="0.2"/>
  <circle cx="1370" cy="350" r="2" fill="#00c6ff" opacity="0.4"/>

  <!-- Connecting lines between data points -->
  <polyline points="1300,200 1350,240 1400,180 1420,300 1370,350" fill="none" stroke="#00c6ff" stroke-width="0.8" opacity="0.2"/>

  <!-- India text watermark -->
  <text x="1095" y="480" font-family="Georgia, serif" font-size="11" fill="#ffffff" text-anchor="middle" opacity="0.15" letter-spacing="4">INDIA · 2026</text>

</svg>
<!--
**harshitrajput2227-a11y/harshitrajput2227-a11y** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
