![banner](https://github.com/user-attachments/assets/df8adbe3-6883-4438-a9a5-84b1c3163011)<div align="center">


  ![Up<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Deep dark background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0e1a"/>
      <stop offset="50%" style="stop-color:#0d1b2e"/>
      <stop offset="100%" style="stop-color:#0a0e1a"/>
    </linearGradient>
[README.md](https://github.com/user-attachments/files/26573547/README.md)

    <!-- Cyan glow gradient -->
    <radialGradient id="glowLeft" cx="20%" cy="50%" r="45%">
      <stop offset="0%" style="stop-color:#00d9ff;stop-opacity:0.18"/>
      <stop offset="100%" style="stop-color:#00d9ff;stop-opacity:0"/>
    </radialGradient>

    <!-- Purple glow gradient -->
    <radialGradient id="glowRight" cx="80%" cy="50%" r="45%">
      <stop offset="0%" style="stop-color:#7c3aed;stop-opacity:0.22"/>
      <stop offset="100%" style="stop-color:#7c3aed;stop-opacity:0"/>
    </radialGradient>

    <!-- Center glow -->
    <radialGradient id="glowCenter" cx="50%" cy="60%" r="35%">
      <stop offset="0%" style="stop-color:#00d9ff;stop-opacity:0.08"/>
      <stop offset="100%" style="stop-color:#00d9ff;stop-opacity:0"/>
    </radialGradient>

    <!-- Text gradient -->
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ffffff"/>
      <stop offset="40%" style="stop-color:#00d9ff"/>
      <stop offset="100%" style="stop-color:#a78bfa"/>
    </linearGradient>

    <!-- Accent line gradient -->
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d9ff;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#00d9ff"/>
      <stop offset="70%" style="stop-color:#7c3aed"/>
      <stop offset="100%" style="stop-color:#7c3aed;stop-opacity:0"/>
    </linearGradient>

    <!-- Particle filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Strong glow filter -->
    <filter id="strongGlow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Clip path -->
    <clipPath id="roundedClip">
      <rect width="900" height="280" rx="16" ry="16"/>
    </clipPath>
  </defs>

  <g clip-path="url(#roundedClip)">

    <!-- Base background -->
    <rect width="900" height="280" fill="url(#bgGrad)"/>
    <!-- Ambient glows -->
    <rect width="900" height="280" fill="url(#glowLeft)"/>
    <rect width="900" height="280" fill="url(#glowRight)"/>
    <rect width="900" height="280" fill="url(#glowCenter)"/>

    <!-- Grid lines - horizontal -->
    <line x1="0" y1="70" x2="900" y2="70" stroke="#00d9ff" stroke-opacity="0.06" stroke-width="1"/>
    <line x1="0" y1="140" x2="900" y2="140" stroke="#00d9ff" stroke-opacity="0.06" stroke-width="1"/>
    <line x1="0" y1="210" x2="900" y2="210" stroke="#00d9ff" stroke-opacity="0.06" stroke-width="1"/>
    <!-- Grid lines - vertical -->
    <line x1="150" y1="0" x2="150" y2="280" stroke="#00d9ff" stroke-opacity="0.04" stroke-width="1"/>
    <line x1="300" y1="0" x2="300" y2="280" stroke="#00d9ff" stroke-opacity="0.04" stroke-width="1"/>
    <line x1="450" y1="0" x2="450" y2="280" stroke="#00d9ff" stroke-opacity="0.04" stroke-width="1"/>
    <line x1="600" y1="0" x2="600" y2="280" stroke="#00d9ff" stroke-opacity="0.04" stroke-width="1"/>
    <line x1="750" y1="0" x2="750" y2="280" stroke="#00d9ff" stroke-opacity="0.04" stroke-width="1"/>

    <!-- Floating particles - animated -->
    <!-- Row 1 particles -->
    <circle cx="60" cy="40" r="1.5" fill="#00d9ff" opacity="0.6" filter="url(#glow)">
      <animate attributeName="opacity" values="0.6;0.1;0.6" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="40;32;40" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="840" cy="55" r="1" fill="#a78bfa" opacity="0.5" filter="url(#glow)">
      <animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.5s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="55;47;55" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="200" cy="25" r="1.2" fill="#00d9ff" opacity="0.4">
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="700" cy="30" r="1.8" fill="#7c3aed" opacity="0.5" filter="url(#glow)">
      <animate attributeName="opacity" values="0.5;0.15;0.5" dur="3.5s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="30;22;30" dur="3.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="500" cy="18" r="1.3" fill="#00d9ff" opacity="0.7">
      <animate attributeName="opacity" values="0.7;0.2;0.7" dur="2.8s" repeatCount="indefinite"/>
    </circle>
    <!-- Row 2 particles -->
    <circle cx="120" cy="220" r="1.4" fill="#a78bfa" opacity="0.5">
      <animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.2s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="220;212;220" dur="3.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="780" cy="240" r="1.6" fill="#00d9ff" opacity="0.6" filter="url(#glow)">
      <animate attributeName="opacity" values="0.6;0.2;0.6" dur="2.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="380" cy="260" r="1.1" fill="#7c3aed" opacity="0.4">
      <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="640" cy="255" r="1.5" fill="#00d9ff" opacity="0.5">
      <animate attributeName="opacity" values="0.5;0.1;0.5" dur="4.2s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="255;247;255" dur="4.2s" repeatCount="indefinite"/>
    </circle>
    <!-- Extra scattered -->
    <circle cx="30" cy="160" r="1" fill="#00d9ff" opacity="0.3">
      <animate attributeName="opacity" values="0.3;0.7;0.3" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="870" cy="150" r="1.2" fill="#a78bfa" opacity="0.4">
      <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="450" cy="265" r="0.8" fill="#00d9ff" opacity="0.5">
      <animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.2s" repeatCount="indefinite"/>
    </circle>

    <!-- Corner decorations -->
    <!-- Top-left bracket -->
    <path d="M 20 20 L 20 50 M 20 20 L 50 20" stroke="#00d9ff" stroke-width="2" fill="none" stroke-opacity="0.7" filter="url(#glow)"/>
    <!-- Top-right bracket -->
    <path d="M 880 20 L 880 50 M 880 20 L 850 20" stroke="#7c3aed" stroke-width="2" fill="none" stroke-opacity="0.7" filter="url(#glow)"/>
    <!-- Bottom-left bracket -->
    <path d="M 20 260 L 20 230 M 20 260 L 50 260" stroke="#7c3aed" stroke-width="2" fill="none" stroke-opacity="0.7" filter="url(#glow)"/>
    <!-- Bottom-right bracket -->
    <path d="M 880 260 L 880 230 M 880 260 L 850 260" stroke="#00d9ff" stroke-width="2" fill="none" stroke-opacity="0.7" filter="url(#glow)"/>

    <!-- Animated scanning line -->
    <rect x="0" y="0" width="900" height="2" fill="url(#lineGrad)" opacity="0.5">
      <animateTransform attributeName="transform" type="translate" values="0,0;0,278;0,0" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.15;0.5" dur="6s" repeatCount="indefinite"/>
    </rect>

    <!-- Left decorative circuit lines -->
    <path d="M 20 100 L 80 100 L 95 115 L 130 115" stroke="#00d9ff" stroke-width="1" fill="none" stroke-opacity="0.4">
      <animate attributeName="stroke-opacity" values="0.4;0.8;0.4" dur="3s" repeatCount="indefinite"/>
    </path>
    <path d="M 20 180 L 60 180 L 75 165 L 110 165" stroke="#7c3aed" stroke-width="1" fill="none" stroke-opacity="0.3">
      <animate attributeName="stroke-opacity" values="0.3;0.7;0.3" dur="4s" repeatCount="indefinite"/>
    </path>
    <circle cx="130" cy="115" r="2.5" fill="none" stroke="#00d9ff" stroke-width="1" stroke-opacity="0.6" filter="url(#glow)">
      <animate attributeName="stroke-opacity" values="0.6;0.1;0.6" dur="3s" repeatCount="indefinite"/>
    </circle>

    <!-- Right decorative circuit lines -->
    <path d="M 880 100 L 820 100 L 805 115 L 770 115" stroke="#a78bfa" stroke-width="1" fill="none" stroke-opacity="0.4">
      <animate attributeName="stroke-opacity" values="0.4;0.8;0.4" dur="3.5s" repeatCount="indefinite"/>
    </path>
    <path d="M 880 180 L 840 180 L 825 165 L 790 165" stroke="#00d9ff" stroke-width="1" fill="none" stroke-opacity="0.3">
      <animate attributeName="stroke-opacity" values="0.3;0.7;0.3" dur="4.5s" repeatCount="indefinite"/>
    </path>
    <circle cx="770" cy="115" r="2.5" fill="none" stroke="#a78bfa" stroke-width="1" stroke-opacity="0.6" filter="url(#glow)">
      <animate attributeName="stroke-opacity" values="0.6;0.1;0.6" dur="3.5s" repeatCount="indefinite"/>
    </circle>

    <!-- Code tag decorations -->
    <text x="22" y="68" font-family="'Courier New', monospace" font-size="11" fill="#00d9ff" opacity="0.35">&lt;dev&gt;</text>
    <text x="840" y="68" font-family="'Courier New', monospace" font-size="11" fill="#7c3aed" opacity="0.35">&lt;/dev&gt;</text>
    <text x="22" y="235" font-family="'Courier New', monospace" font-size="10" fill="#7c3aed" opacity="0.3">{ mern: true }</text>
    <text x="810" y="235" font-family="'Courier New', monospace" font-size="10" fill="#00d9ff" opacity="0.3">{ build: 🚀 }</text>

    <!-- Main greeting line with fade-in feel -->
    <text x="450" y="88"
      font-family="'Courier New', monospace"
      font-size="13"
      fill="#00d9ff"
      text-anchor="middle"
      letter-spacing="6"
      opacity="0.8">
      &lt;!-- WELCOME TO MY PROFILE --&gt;
    </text>

    <!-- Main name - large gradient text -->
    <text x="450" y="155"
      font-family="Georgia, 'Times New Roman', serif"
      font-size="52"
      font-weight="bold"
      fill="url(#nameGrad)"
      text-anchor="middle"
      filter="url(#strongGlow)"
      letter-spacing="1">
      Abdhullah Al Maruf
      <animate attributeName="opacity" values="0;1" dur="1s" fill="freeze"/>
    </text>

    <!-- Accent underline -->
    <line x1="200" y1="168" x2="700" y2="168" stroke="url(#lineGrad)" stroke-width="1.5" opacity="0.8">
      <animate attributeName="x1" values="450;200" dur="1.2s" fill="freeze"/>
      <animate attributeName="x2" values="450;700" dur="1.2s" fill="freeze"/>
    </line>

    <!-- Role subtitle -->
    <text x="450" y="200"
      font-family="'Courier New', monospace"
      font-size="16"
      fill="#94a3b8"
      text-anchor="middle"
      letter-spacing="3">
      MERN STACK DEVELOPER
    </text>

    <!-- Tag pills at bottom -->
    <!-- Pill 1 -->
    <rect x="198" y="220" width="90" height="24" rx="12" fill="#00d9ff" fill-opacity="0.1" stroke="#00d9ff" stroke-width="1" stroke-opacity="0.4"/>
    <text x="243" y="236" font-family="'Courier New', monospace" font-size="10" fill="#00d9ff" text-anchor="middle" letter-spacing="1">React</text>

    <!-- Pill 2 -->
    <rect x="302" y="220" width="90" height="24" rx="12" fill="#a78bfa" fill-opacity="0.1" stroke="#a78bfa" stroke-width="1" stroke-opacity="0.4"/>
    <text x="347" y="236" font-family="'Courier New', monospace" font-size="10" fill="#a78bfa" text-anchor="middle" letter-spacing="1">Node.js</text>

    <!-- Pill 3 -->
    <rect x="406" y="220" width="90" height="24" rx="12" fill="#00d9ff" fill-opacity="0.1" stroke="#00d9ff" stroke-width="1" stroke-opacity="0.4"/>
    <text x="451" y="236" font-family="'Courier New', monospace" font-size="10" fill="#00d9ff" text-anchor="middle" letter-spacing="1">MongoDB</text>

    <!-- Pill 4 -->
    <rect x="510" y="220" width="90" height="24" rx="12" fill="#a78bfa" fill-opacity="0.1" stroke="#a78bfa" stroke-width="1" stroke-opacity="0.4"/>
    <text x="555" y="236" font-family="'Courier New', monospace" font-size="10" fill="#a78bfa" text-anchor="middle" letter-spacing="1">Express</text>

    <!-- Pill 5 -->
    <rect x="614" y="220" width="90" height="24" rx="12" fill="#00d9ff" fill-opacity="0.1" stroke="#00d9ff" stroke-width="1" stroke-opacity="0.4"/>
    <text x="659" y="236" font-family="'Courier New', monospace" font-size="10" fill="#00d9ff" text-anchor="middle" letter-spacing="1">Next.js</text>

    <!-- Border glow -->
    <rect x="1" y="1" width="898" height="278" rx="15" ry="15"
      fill="none"
      stroke="url(#lineGrad)"
      stroke-width="1.5"
      stroke-opacity="0.5"/>

  </g>
</svg>

<div align="center">
<img src="https://raw.githubusercontent.com/Abdhullah-Al-Maruf/Abdhullah-Al-Maruf/main/banner.svg" width="100%" alt="Abdhullah Al Maruf Banner"/>
</div>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Hey+There%2C+I'm+Maruf+%F0%9F%91%8B;MERN+Stack+Developer+%7C+Bangladesh+%F0%9F%87%A7%F0%9F%87%A9;Building+Scalable+Web+Applications+%F0%9F%9A%80;Open+Source+Enthusiast+%7C+Always+Learning)](https://git.io/typing-svg)

</div>

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=Abdhullah-Al-Maruf&label=Profile+Views&color=00d9ff&style=for-the-badge&labelColor=0d1117)](https://github.com/Abdhullah-Al-Maruf)&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/Abdhullah-Al-Maruf?label=Followers&style=for-the-badge&color=7c3aed&labelColor=0d1117)](https://github.com/Abdhullah-Al-Maruf)&nbsp;
[![GitHub stars](https://img.shields.io/github/stars/Abdhullah-Al-Maruf?label=Stars&style=for-the-badge&color=00d9ff&labelColor=0d1117)](https://github.com/Abdhullah-Al-Maruf)

</div>

<br/>

---

## 🧑‍💻 About Me

```ts
const maruf = {
  name        : "Abdhullah Al Maruf",
  role        : "MERN Stack Developer",
  location    : "Bangladesh 🇧🇩",
  focus       : ["Scalable Web Apps", "Clean Architecture", "Great UX"],
  currently   : ["Next.js", "System Design", "AWS", "Docker"],
  collaborate : "Open Source Projects 🤝",
  funFact     : "I turn ☕ coffee into scalable systems",
  ask_me_about: ["React", "Node.js", "MongoDB", "Express", "REST APIs"],
  available   : true,
};
```

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdhullah-al-maruf/)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-%23171515.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Abdhullah-Al-Maruf)&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mdmaruf20053@gmail.com)

</div>

---

## 🛠️ Tech Stack & Tools

<div align="center">

### 🎨 Frontend

![React](https://img.shields.io/badge/React-%2320232A.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)&nbsp;
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)&nbsp;
![Redux](https://img.shields.io/badge/Redux-%23593D88.svg?style=for-the-badge&logo=redux&logoColor=white)&nbsp;
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)&nbsp;
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)&nbsp;
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-%2306B6D4.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)&nbsp;
![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)&nbsp;
![Figma](https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### ⚙️ Backend

![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)&nbsp;
![Express.js](https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)&nbsp;
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)&nbsp;
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### 🗄️ Database & Cloud

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)&nbsp;
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)&nbsp;
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)&nbsp;
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

### 🧰 Tools & DevOps

![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)&nbsp;
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)&nbsp;
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)&nbsp;
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)&nbsp;
![VS Code](https://img.shields.io/badge/VS_Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Abdhullah-Al-Maruf&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=00d9ff&icon_color=7c3aed&text_color=94a3b8" />
<img width="49%" src="https://streak-stats.demolab.com/?user=Abdhullah-Al-Maruf&theme=tokyonight&hide_border=true&background=0d1117&stroke=00d9ff&ring=7c3aed&fire=00d9ff&currStreakLabel=00d9ff&sideLabels=94a3b8" />

</div>

<div align="center">

<img width="45%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abdhullah-Al-Maruf&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&text_color=94a3b8&langs_count=8" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Abdhullah-Al-Maruf&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" />

</div>

---

## 🔥 Contribution Graph

<div align="center">

[![Maruf's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Abdhullah-Al-Maruf&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00d9ff&line=7c3aed&point=00d9ff&area=true&area_color=00d9ff)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🏅 Highlights

<div align="center">

| 🏆 Achievement | 📌 Details |
|:---|:---|
| ⚡ Full-Stack Apps | Built production-ready MERN applications end-to-end |
| 🔐 Auth Systems | JWT, OAuth & Firebase Authentication flows |
| 📱 Responsive UI | Mobile-first designs with Tailwind CSS & DaisyUI |
| 🔗 REST APIs | Designed and documented RESTful backend services |
| 🐳 DevOps Ready | Docker, Git workflows & cloud infrastructure |

</div>

---

## 🚀 Currently Building

```bash
🔨  Full Stack MERN Applications with role-based access control
📐  RESTful & scalable APIs with Node.js + Express
🎨  Pixel-perfect UIs with React, Tailwind CSS & DaisyUI
☁️  Containerized apps with Docker + exploring AWS cloud
```

---

<div align="center">

### 💬 Dev Philosophy

*"First, solve the problem. Then, write the code."*

<br/>

![snake animation](https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg)

<br/>

⭐ **If you find my work valuable, consider giving a star!** ⭐

</div>
loading banner.svg…]()

</div>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Hey+There%2C+I'm+Maruf+%F0%9F%91%8B;MERN+Stack+Developer+%7C+Bangladesh+%F0%9F%87%A7%F0%9F%87%A9;Building+Scalable+Web+Applications+%F0%9F%9A%80;Open+Source+Enthusiast+%7C+Always+Learning)](https://git.io/typing-svg)

</div>

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=Abdhullah-Al-Maruf&label=Profile+Views&color=00d9ff&style=for-the-badge&labelColor=0d1117)](https://github.com/Abdhullah-Al-Maruf)&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/Abdhullah-Al-Maruf?label=Followers&style=for-the-badge&color=7c3aed&labelColor=0d1117)](https://github.com/Abdhullah-Al-Maruf)&nbsp;
[![GitHub stars](https://img.shields.io/github/stars/Abdhullah-Al-Maruf?label=Stars&style=for-the-badge&color=00d9ff&labelColor=0d1117)](https://github.com/Abdhullah-Al-Maruf)

</div>

<br/>

---

## 🧑‍💻 About Me

```ts
const maruf = {
  name        : "Abdhullah Al Maruf",
  role        : "MERN Stack Developer",
  location    : "Bangladesh 🇧🇩",
  focus       : ["Scalable Web Apps", "Clean Architecture", "Great UX"],
  currently   : ["Next.js", "System Design", "AWS", "Docker"],
  collaborate : "Open Source Projects 🤝",
  funFact     : "I turn ☕ coffee into scalable systems",
  ask_me_about: ["React", "Node.js", "MongoDB", "Express", "REST APIs"],
  available   : true,
};
```

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdhullah-al-maruf/)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-%23171515.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Abdhullah-Al-Maruf)&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mdmaruf20053@gmail.com)

</div>

---

## 🛠️ Tech Stack & Tools

<div align="center">

### 🎨 Frontend

![React](https://img.shields.io/badge/React-%2320232A.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)&nbsp;
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)&nbsp;
![Redux](https://img.shields.io/badge/Redux-%23593D88.svg?style=for-the-badge&logo=redux&logoColor=white)&nbsp;
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)&nbsp;
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)&nbsp;
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-%2306B6D4.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)&nbsp;
![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)&nbsp;
![Figma](https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### ⚙️ Backend

![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)&nbsp;
![Express.js](https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)&nbsp;
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)&nbsp;
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### 🗄️ Database & Cloud

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)&nbsp;
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)&nbsp;
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)&nbsp;
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

### 🧰 Tools & DevOps

![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)&nbsp;
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)&nbsp;
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)&nbsp;
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)&nbsp;
![VS Code](https://img.shields.io/badge/VS_Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Abdhullah-Al-Maruf&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=00d9ff&icon_color=7c3aed&text_color=94a3b8" />
<img width="49%" src="https://streak-stats.demolab.com/?user=Abdhullah-Al-Maruf&theme=tokyonight&hide_border=true&background=0d1117&stroke=00d9ff&ring=7c3aed&fire=00d9ff&currStreakLabel=00d9ff&sideLabels=94a3b8" />

</div>

<div align="center">

<img width="45%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abdhullah-Al-Maruf&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&text_color=94a3b8&langs_count=8" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Abdhullah-Al-Maruf&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" />

</div>

---

## 🔥 Contribution Graph

<div align="center">

[![Maruf's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Abdhullah-Al-Maruf&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00d9ff&line=7c3aed&point=00d9ff&area=true&area_color=00d9ff)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🏅 Highlights

<div align="center">

| 🏆 Achievement | 📌 Details |
|:---|:---|
| ⚡ Full-Stack Apps | Built production-ready MERN applications end-to-end |
| 🔐 Auth Systems | JWT, OAuth & Firebase Authentication flows |
| 📱 Responsive UI | Mobile-first designs with Tailwind CSS & DaisyUI |
| 🔗 REST APIs | Designed and documented RESTful backend services |
| 🐳 DevOps Ready | Docker, Git workflows & cloud infrastructure |

</div>

---

## 🚀 Currently Building

```bash
🔨  Full Stack MERN Applications with role-based access control
📐  RESTful & scalable APIs with Node.js + Express
🎨  Pixel-perfect UIs with React, Tailwind CSS & DaisyUI
☁️  Containerized apps with Docker + exploring AWS cloud
```

---

<div align="center">

### 💬 Dev Philosophy

*"First, solve the problem. Then, write the code."*

<br/>

![snake animation](https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg)

<br/>

⭐ **If you find my work valuable, consider giving a star!** ⭐

</div>
