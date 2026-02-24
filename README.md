<div align="center">

<!-- Top Banner - capsule-render venom with depth -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0d1117,50:161b22,100:0d1117&height=200&text=Harikrishna%20Battula&fontSize=48&fontColor=ffffff&fontAlignY=50&desc=Full%20Stack%20Java%20Developer&descAlignY=68&descColor=8b949e&animation=fadeIn" width="100%"/>

<!-- Animated SVG Banner -->
<svg width="100%" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#161b22;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#0d1117;stop-opacity:1"/>
    </linearGradient>
    <!-- Shimmer sweep gradient -->
    <linearGradient id="shimmer" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#ffffff;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#ffffff;stop-opacity:0"/>
    </linearGradient>
    <!-- Glow filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Soft glow for particles -->
    <filter id="softglow">
      <feGaussianBlur stdDeviation="1.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Shimmer animation -->
    <clipPath id="textClip">
      <text x="400" y="68" text-anchor="middle" font-family="JetBrains Mono, monospace" font-size="22" font-weight="600">&lt; Full Stack Java Developer /&gt;</text>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="800" height="120" fill="url(#bgGrad)"/>

  <!-- Decorative left line -->
  <line x1="40" y1="30" x2="40" y2="90" stroke="#21262d" stroke-width="1.5" opacity="0.8">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3s" repeatCount="indefinite"/>
  </line>
  <line x1="50" y1="40" x2="50" y2="80" stroke="#30363d" stroke-width="1" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="2.5s" repeatCount="indefinite"/>
  </line>

  <!-- Decorative right line -->
  <line x1="760" y1="30" x2="760" y2="90" stroke="#21262d" stroke-width="1.5" opacity="0.8">
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="3s" repeatCount="indefinite"/>
  </line>
  <line x1="750" y1="40" x2="750" y2="80" stroke="#30363d" stroke-width="1" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="2.5s" repeatCount="indefinite"/>
  </line>

  <!-- Floating particles -->
  <circle cx="100" cy="30" r="1.5" fill="#30363d" filter="url(#softglow)">
    <animate attributeName="cy" values="30;20;30" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="90" r="1" fill="#21262d" filter="url(#softglow)">
    <animate attributeName="cy" values="90;80;90" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="25" r="1.5" fill="#30363d" filter="url(#softglow)">
    <animate attributeName="cy" values="25;35;25" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="680" cy="85" r="1" fill="#21262d" filter="url(#softglow)">
    <animate attributeName="cy" values="85;75;85" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.4;1" dur="4.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="350" cy="15" r="1.2" fill="#30363d" filter="url(#softglow)">
    <animate attributeName="cy" values="15;25;15" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="460" cy="100" r="1" fill="#21262d" filter="url(#softglow)">
    <animate attributeName="cy" values="100;90;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- Main text with glow -->
  <text x="400" y="68" text-anchor="middle"
    font-family="JetBrains Mono, monospace"
    font-size="22" font-weight="600"
    fill="#ffffff" filter="url(#glow)" opacity="0.95">
    &lt; Full Stack Java Developer /&gt;
    <animate attributeName="opacity" values="0.7;1;0.7" dur="4s" repeatCount="indefinite"/>
  </text>

  <!-- Shimmer sweep over text -->
  <rect x="-800" y="45" width="800" height="35" fill="url(#shimmer)" clip-path="url(#textClip)">
    <animateTransform attributeName="transform" type="translate" from="-800 0" to="1600 0" dur="3.5s" repeatCount="indefinite"/>
  </rect>

  <!-- Bottom thin line -->
  <line x1="60" y1="108" x2="740" y2="108" stroke="#21262d" stroke-width="0.5" opacity="0.5"/>
</svg>

<!-- Typing SVG -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=ffffff&center=true&vCenter=true&width=600&lines=Full+Stack+Java+Developer;Java+%7C+Spring+Boot+%7C+WebSockets" alt="Typing SVG"/>

<br/>

<img src="https://komarev.com/ghpvc/?username=harikrishnaaa321&label=Profile+Views&color=21262d&style=for-the-badge&labelColor=161b22" alt="Profile Views"/>

</div>

---

<img align="right" alt="coding" width="360" src="https://user-images.githubusercontent.com/55389276/140866485-8fb1c876-9a8f-4d6a-98dc-08c4981eaf70.gif"/>

### 👨‍💻 About Me
```java
