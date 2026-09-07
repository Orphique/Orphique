<div align="center">

<svg width="850" height="720" viewBox="0 0 850 720" xmlns="http://www.w3.org/2000/svg"
<style>
    @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&amp;family=Orbitron:wght@700&amp;display=swap');

    .bg { fill: #070913; }
    .window-bg { fill: #0b1120; stroke: #00f0ff; stroke-width: 1.5; filter: drop-shadow(0px 0px 8px rgba(0,240,255,0.3)); }
    .header-bg { fill: #00f0ff; }
    
    .text-title { font-family: 'Orbitron', sans-serif; font-weight: 700; fill: #070913; font-size: 13px; letter-spacing: 2px; }
    .text-label { font-family: 'Share Tech Mono', monospace; fill: #64748b; font-size: 14px; }
    .text-value { font-family: 'Share Tech Mono', monospace; fill: #e2e8f0; font-size: 14px; font-weight: bold; }
    .text-cyan { font-family: 'Share Tech Mono', monospace; fill: #00f0ff; font-size: 14px; font-weight: bold; }
    .text-green { font-family: 'Share Tech Mono', monospace; fill: #10b981; font-size: 13px; }
    .text-yellow { font-family: 'Share Tech Mono', monospace; fill: #f59e0b; font-size: 13px; }
    .text-dim { font-family: 'Share Tech Mono', monospace; fill: #94a3b8; font-size: 13px; }
    
    .bar-bg { fill: #1e293b; rx: 3px; }
    .hp-bar { fill: #ef4444; rx: 3px; filter: drop-shadow(0px 0px 4px rgba(239,68,68,0.6)); }
    .mp-bar { fill: #3b82f6; rx: 3px; filter: drop-shadow(0px 0px 4px rgba(59,130,246,0.6)); }
    .stat-bar { fill: #00f0ff; rx: 2px; filter: drop-shadow(0px 0px 3px rgba(0,240,255,0.5)); }

    .corner { stroke: #00f0ff; stroke-width: 2; fill: none; }
  </style>

  <rect width="850" height="720" class="bg" rx="10"/>

  <g transform="translate(25, 25)">
    <rect width="255" height="430" class="window-bg" rx="4"/>
    <rect x="0" y="0" width="255" height="30" class="header-bg"/>
    <text x="127" y="20" text-anchor="middle" class="text-title">SYSTEM STATUS</text>
    
    <g transform="translate(15, 50)">
      <text x="0" y="0" class="text-label">Name:</text>
      <text x="110" y="0" class="text-cyan">Sung Jin-Code</text>

      <text x="0" y="25" class="text-label">Level:</text>
      <text x="110" y="25" class="text-value">99</text>

      <text x="0" y="50" class="text-label">Job:</text>
      <text x="110" y="50" class="text-value">Shadow Arch</text>

      <text x="0" y="75" class="text-label">HP:</text>
      <rect x="45" y="63" width="175" height="12" class="bar-bg"/>
      <rect x="45" y="63" width="175" height="12" class="hp-bar"/>
      <text x="132" y="73" text-anchor="middle" font-family="'Share Tech Mono', monospace" font-size="9" fill="#ffffff">2500/2500</text>

      <text x="0" y="100" class="text-label">MP:</text>
      <rect x="45" y="88" width="175" height="12" class="bar-bg"/>
      <rect x="45" y="88" width="175" height="12" class="mp-bar"/>
      <text x="132" y="98" text-anchor="middle" font-family="'Share Tech Mono', monospace" font-size="9" fill="#ffffff">1200/1200</text>
    </g>

    <line x1="15" y1="175" x2="240" y2="175" stroke="#1e293b" stroke-width="1.5"/>

    <g transform="translate(15, 195)">
      <text x="0" y="0" class="text-label">Strength</text>
      <rect x="90" y="-10" width="90" height="8" class="bar-bg"/>
      <rect x="90" y="-10" width="75" height="8" class="stat-bar"/>
      <text x="210" y="0" class="text-value">210</text>

      <text x="0" y="30" class="text-label">Agility</text>
      <rect x="90" y="20" width="90" height="8" class="bar-bg"/>
      <rect x="90" y="20" width="85" height="8" class="stat-bar"/>
      <text x="210" y="30" class="text-value">245</text>

      <text x="0" y="60" class="text-label">Sense</text>
      <rect x="90" y="50" width="90" height="8" class="bar-bg"/>
      <rect x="90" y="50" width="80" height="8" class="stat-bar"/>
      <text x="210" y="60" class="text-value">230</text>

      <text x="0" y="90" class="text-label">Vitality</text>
      <rect x="90" y="80" width="90" height="8" class="bar-bg"/>
      <rect x="90" y="80" width="70" height="8" class="stat-bar"/>
      <text x="210" y="90" class="text-value">190</text>

      <text x="0" y="120" class="text-label">Intelligence</text>
      <rect x="90" y="110" width="90" height="8" class="bar-bg"/>
      <rect x="90" y="110" width="88" height="8" class="stat-bar"/>
      <text x="210" y="120" class="text-value">255</text>
    </g>

    <path d="M 0 8 L 0 0 L 8 0" class="corner"/>
    <path d="M 247 0 L 255 0 L 255 8" class="corner"/>
    <path d="M 0 422 L 0 430 L 8 430" class="corner"/>
    <path d="M 247 430 L 255 430 L 255 422" class="corner"/>
  </g>

  <g transform="translate(295, 25)">
    <rect width="530" height="255" class="window-bg" rx="4"/>
    <rect x="0" y="0" width="530" height="30" class="header-bg"/>
    <text x="265" y="20" text-anchor="middle" class="text-title">QUEST LOG</text>

    <g transform="translate(20, 50)">
      <text x="0" y="0" class="text-green">[FINISHED] Daily Quest: Consistency Protocol</text>
      <text x="15" y="20" class="text-dim">Goal: Push at least 1 commit &amp; clear daily pipelines.</text>
      <text x="15" y="38" class="text-dim">Reward: +10 EXP, Clean Git History.</text>

      <g transform="translate(0, 65)">
        <text x="0" y="0" class="text-yellow">[ONGOING] Class Upgrade: Distributed System Architecture</text>
        <text x="15" y="20" class="text-dim">Goal: Build scalable microservices with gRPC &amp; Kafka.</text>
        <rect x="15" y="32" width="470" height="6" class="bar-bg"/>
        <rect x="15" y="32" width="300" height="6" fill="#f59e0b" rx="2"/>
        <text x="440" y="20" class="text-value" font-size="12">65%</text>
      </g>

      <g transform="translate(0, 135)">
        <text x="0" y="0" class="text-cyan">[PROJECT] Awakening: Solo-Leveling CLI Tool</text>
        <text x="15" y="20" class="text-dim">Goal: Create an interactive terminal dashboard for developers.</text>
        <text x="15" y="38" class="text-dim">Tech: Rust, Tokio, Crossterm</text>
      </g>
    </g>

    <path d="M 0 8 L 0 0 L 8 0" class="corner"/>
    <path d="M 522 0 L 530 0 L 530 8" class="corner"/>
    <path d="M 0 247 L 0 255 L 8 255" class="corner"/>
    <path d="M 522 255 L 530 255 L 530 247" class="corner"/>
  </g>

  <g transform="translate(295, 295)">
    <rect width="530" height="400" class="window-bg" rx="4"/>
    <rect x="0" y="0" width="530" height="30" class="header-bg"/>
    <text x="265" y="20" text-anchor="middle" class="text-title">SKILLS &amp; TECH STACK</text>

    <g transform="translate(20, 50)">
      <text x="0" y="0" class="text-cyan">» LANGUAGES</text>
      <text x="15" y="25" class="text-label">TypeScript / JavaScript</text>
      <text x="280" y="25" class="text-value">[★★★★★★★★★★] 95%</text>
      
      <text x="15" y="50" class="text-label">Python / Go</text>
      <text x="280" y="50" class="text-value">[★★★★★★★★☆☆] 85%</text>

      <text x="15" y="75" class="text-label">Rust / C++</text>
      <text x="280" y="75" class="text-value">[★★★★★★★☆☆☆] 70%</text>

      <g transform="translate(0, 110)">
        <text x="0" y="0" class="text-cyan">» FRAMEWORKS &amp; BACKEND</text>
        <text x="15" y="25" class="text-label">Node.js / Express / NestJS</text>
        <text x="280" y="25" class="text-value">[★★★★★★★★★★] 90%</text>

        <text x="15" y="50" class="text-label">React / Next.js / Tailwind</text>
        <text x="280" y="50" class="text-value">[★★★★★★★★★★] 95%</text>
      </g>

      <g transform="translate(0, 200)">
        <text x="0" y="0" class="text-cyan">» INFRASTRUCTURE &amp; DATABASES</text>
        <text x="15" y="25" class="text-label">PostgreSQL / Redis / MongoDB</text>
        <text x="280" y="25" class="text-value">[★★★★★★★★☆☆] 85%</text>

        <text x="15" y="50" class="text-label">Docker / Kubernetes / AWS</text>
        <text x="280" y="50" class="text-value">[★★★★★★★☆☆☆] 75%</text>
      </g>
    </g>

    <path d="M 0 8 L 0 0 L 8 0" class="corner"/>
    <path d="M 522 0 L 530 0 L 530 8" class="corner"/>
    <path d="M 0 392 L 0 400 L 8 400" class="corner"/>
    <path d="M 522 400 L 530 400 L 530 392" class="corner"/>
  </g>

</svg>

</div>

<div align="center">
  <h3><i>"Arise."</i></h3>
</div>
