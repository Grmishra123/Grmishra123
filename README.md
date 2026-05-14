<div align="center">

<!-- Mountain & Buddha SVG Banner -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 220" width="900" height="220">
  <!-- Sky gradient background -->
  <defs>
    <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0f1b2e"/>
      <stop offset="60%" stop-color="#1a3a5c"/>
      <stop offset="100%" stop-color="#2d5a8e"/>
    </linearGradient>
    <linearGradient id="snowGrad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="100%" stop-color="#c8dff0"/>
    </linearGradient>
    <linearGradient id="mountainGrad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#2a4a6b"/>
      <stop offset="100%" stop-color="#0d2137"/>
    </linearGradient>
    <linearGradient id="mountain2Grad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#1e3d5e"/>
      <stop offset="100%" stop-color="#0a1c2e"/>
    </linearGradient>
    <linearGradient id="glowGrad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#f9d86e" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#f0a030" stop-opacity="0.6"/>
    </linearGradient>
  </defs>

  <!-- Sky -->
  <rect width="900" height="220" fill="url(#sky)"/>

  <!-- Stars -->
  <circle cx="50" cy="20" r="1.2" fill="white" opacity="0.8"/>
  <circle cx="120" cy="10" r="0.9" fill="white" opacity="0.7"/>
  <circle cx="200" cy="25" r="1.1" fill="white" opacity="0.6"/>
  <circle cx="310" cy="15" r="0.8" fill="white" opacity="0.8"/>
  <circle cx="410" cy="8" r="1.3" fill="white" opacity="0.5"/>
  <circle cx="580" cy="18" r="0.9" fill="white" opacity="0.7"/>
  <circle cx="680" cy="12" r="1.1" fill="white" opacity="0.9"/>
  <circle cx="780" cy="22" r="0.8" fill="white" opacity="0.6"/>
  <circle cx="840" cy="9" r="1.2" fill="white" opacity="0.7"/>
  <circle cx="860" cy="35" r="0.7" fill="white" opacity="0.5"/>
  <circle cx="760" cy="40" r="0.9" fill="white" opacity="0.6"/>
  <circle cx="30" cy="55" r="0.7" fill="white" opacity="0.5"/>
  <circle cx="150" cy="45" r="1.0" fill="white" opacity="0.6"/>
  <circle cx="650" cy="30" r="0.8" fill="white" opacity="0.7"/>

  <!-- Far background mountains (left) -->
  <polygon points="0,160 80,70 160,130 220,85 300,140 0,140" fill="#12283f" opacity="0.7"/>
  <!-- Far background mountains (right) -->
  <polygon points="600,145 700,80 760,110 850,65 900,100 900,145" fill="#12283f" opacity="0.7"/>

  <!-- Main left mountain -->
  <polygon points="20,210 180,55 260,100 320,210" fill="url(#mountainGrad)"/>
  <!-- Snow cap left -->
  <polygon points="160,70 180,55 200,68 185,80" fill="url(#snowGrad)" opacity="0.95"/>

  <!-- Main right mountain -->
  <polygon points="580,210 720,50 800,95 900,210" fill="url(#mountain2Grad)"/>
  <!-- Snow cap right -->
  <polygon points="700,65 720,50 742,63 726,78" fill="url(#snowGrad)" opacity="0.95"/>

  <!-- Mid mountain left -->
  <polygon points="200,210 330,90 420,140 500,210" fill="#0e2236" opacity="0.85"/>
  <!-- Snow cap mid left -->
  <polygon points="312,105 330,90 350,103 335,118" fill="url(#snowGrad)" opacity="0.9"/>

  <!-- Mid mountain right -->
  <polygon points="400,210 530,95 620,140 700,210" fill="#0b1e30" opacity="0.9"/>
  <!-- Snow cap mid right -->
  <polygon points="512,110 530,95 550,108 535,122" fill="url(#snowGrad)" opacity="0.9"/>

  <!-- Ground mist / fog layer -->
  <rect x="0" y="185" width="900" height="35" fill="#1a3a5c" opacity="0.5"/>
  <ellipse cx="450" cy="195" rx="450" ry="25" fill="#1a3a5c" opacity="0.4"/>

  <!-- Aura / glow behind Buddha -->
  <ellipse cx="450" cy="130" rx="62" ry="72" fill="url(#glowGrad)" opacity="0.25"/>
  <ellipse cx="450" cy="130" rx="48" ry="58" fill="#f9d86e" opacity="0.13"/>

  <!-- Lotus base -->
  <ellipse cx="450" cy="196" rx="38" ry="10" fill="#c8860a" opacity="0.7"/>
  <!-- Lotus petals -->
  <ellipse cx="422" cy="192" rx="14" ry="6" fill="#e8a020" opacity="0.85" transform="rotate(-20,422,192)"/>
  <ellipse cx="478" cy="192" rx="14" ry="6" fill="#e8a020" opacity="0.85" transform="rotate(20,478,192)"/>
  <ellipse cx="450" cy="188" rx="14" ry="6" fill="#f0b830" opacity="0.9"/>
  <ellipse cx="435" cy="190" rx="12" ry="5" fill="#f5c840" opacity="0.8" transform="rotate(-10,435,190)"/>
  <ellipse cx="465" cy="190" rx="12" ry="5" fill="#f5c840" opacity="0.8" transform="rotate(10,465,190)"/>

  <!-- Buddha body (robe) -->
  <ellipse cx="450" cy="168" rx="28" ry="22" fill="#c8860a"/>
  <!-- Robe folds -->
  <path d="M428,162 Q435,175 430,185" stroke="#a06a06" stroke-width="1" fill="none" opacity="0.6"/>
  <path d="M472,162 Q465,175 470,185" stroke="#a06a06" stroke-width="1" fill="none" opacity="0.6"/>

  <!-- Buddha hands (dhyana mudra) -->
  <ellipse cx="440" cy="178" rx="10" ry="5" fill="#c8860a"/>
  <ellipse cx="460" cy="178" rx="10" ry="5" fill="#c8860a"/>
  <ellipse cx="450" cy="181" rx="12" ry="5" fill="#b87a08"/>

  <!-- Buddha neck -->
  <rect x="444" y="148" width="12" height="9" rx="3" fill="#d4920e"/>

  <!-- Buddha head -->
  <ellipse cx="450" cy="138" rx="20" ry="22" fill="#d4920e"/>

  <!-- Ushnisha (topknot) -->
  <ellipse cx="450" cy="117" rx="10" ry="8" fill="#c8860a"/>
  <ellipse cx="450" cy="111" rx="6" ry="5" fill="#b87a08"/>
  <circle cx="450" cy="107" r="3" fill="#f9d86e"/>

  <!-- Buddha face -->
  <!-- Eyes (closed, meditating) -->
  <path d="M440,137 Q445,134 450,137" stroke="#7a4a00" stroke-width="1.5" fill="none" stroke-linecap="round"/>
  <path d="M450,137 Q455,134 460,137" stroke="#7a4a00" stroke-width="1.5" fill="none" stroke-linecap="round"/>
  <!-- Eyebrows -->
  <path d="M438,132 Q445,129 452,132" stroke="#8a5800" stroke-width="1.2" fill="none" stroke-linecap="round"/>
  <path d="M448,132 Q455,129 462,132" stroke="#8a5800" stroke-width="1.2" fill="none" stroke-linecap="round"/>
  <!-- Nose -->
  <path d="M448,140 Q450,144 452,140" stroke="#a07000" stroke-width="1" fill="none" stroke-linecap="round"/>
  <!-- Mouth (serene smile) -->
  <path d="M444,148 Q450,152 456,148" stroke="#8a5800" stroke-width="1.2" fill="none" stroke-linecap="round"/>
  <!-- Ear -->
  <ellipse cx="430" cy="140" rx="4" ry="6" fill="#c8860a"/>
  <ellipse cx="470" cy="140" rx="4" ry="6" fill="#c8860a"/>
  <!-- Long earlobes -->
  <ellipse cx="430" cy="146" rx="3" ry="4" fill="#b87a08"/>
  <ellipse cx="470" cy="146" rx="3" ry="4" fill="#b87a08"/>

  <!-- Name text -->
  <text x="450" y="34" text-anchor="middle" font-family="Georgia, serif" font-size="26" font-weight="bold" fill="white" opacity="0.95" letter-spacing="3">GRISHAB MISHRA</text>
  <text x="450" y="56" text-anchor="middle" font-family="Georgia, serif" font-size="13" fill="#90b8d8" letter-spacing="2">Cybersecurity Engineer  ·  Backend Developer</text>

  <!-- Decorative line under title -->
  <line x1="320" y1="64" x2="580" y2="64" stroke="#f9d86e" stroke-width="0.8" opacity="0.5"/>

  <!-- Small dharma wheel left -->
  <g transform="translate(360,110)" opacity="0.35">
    <circle r="10" fill="none" stroke="#f9d86e" stroke-width="1"/>
    <circle r="3" fill="none" stroke="#f9d86e" stroke-width="1"/>
    <line x1="-10" y1="0" x2="10" y2="0" stroke="#f9d86e" stroke-width="0.8"/>
    <line x1="0" y1="-10" x2="0" y2="10" stroke="#f9d86e" stroke-width="0.8"/>
    <line x1="-7" y1="-7" x2="7" y2="7" stroke="#f9d86e" stroke-width="0.8"/>
    <line x1="7" y1="-7" x2="-7" y2="7" stroke="#f9d86e" stroke-width="0.8"/>
  </g>
  <!-- Small dharma wheel right -->
  <g transform="translate(540,110)" opacity="0.35">
    <circle r="10" fill="none" stroke="#f9d86e" stroke-width="1"/>
    <circle r="3" fill="none" stroke="#f9d86e" stroke-width="1"/>
    <line x1="-10" y1="0" x2="10" y2="0" stroke="#f9d86e" stroke-width="0.8"/>
    <line x1="0" y1="-10" x2="0" y2="10" stroke="#f9d86e" stroke-width="0.8"/>
    <line x1="-7" y1="-7" x2="7" y2="7" stroke="#f9d86e" stroke-width="0.8"/>
    <line x1="7" y1="-7" x2="-7" y2="7" stroke="#f9d86e" stroke-width="0.8"/>
  </g>
</svg>

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-1e3a8a?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/grishab-mishra-741786349/)
[![Email](https://img.shields.io/badge/Email-334155?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mishra.secure999@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-0f172a?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Grmishra123)

</div>

---

# About Me

I'm a cybersecurity student at the University of North Texas focused on secure backend systems, authentication infrastructure, API security, and DevOps.

Most of my projects are built around:
- secure authentication
- network auditing
- backend engineering
- infrastructure automation
- security-focused software development

Currently looking for full-time opportunities in cybersecurity engineering, backend development, and cloud/security operations.

---

# Featured Projects

## 🔐 [JWT Authentication Server](https://github.com/Grmishra123/jwks-server-project-part3)

FastAPI-based JWT authentication server with encrypted RSA key storage, automatic key rotation, JWKS support, and authentication logging.

### Tech
`Python` `FastAPI` `SQLite` `RSA` `AES-GCM` `Argon2`

### Highlights
- JWT signing with RSA keys
- AES-GCM encrypted private key storage
- JWKS endpoint support
- Per-IP rate limiting
- Authentication logging
- Automated key rotation

---

## 🌐 [CodeQueryZone](https://github.com/Grmishra123/codequeryzone)

Containerized developer forum platform with CI/CD pipelines, SSL/TLS configuration, Docker orchestration, and production deployment workflows.

### Tech
`Docker` `Nginx` `PostgreSQL` `Redis` `GitHub Actions`

### Highlights
- Multi-container Docker setup
- CI/CD workflows
- Reverse proxy configuration
- SSL/TLS integration
- Cloudflare protection
- Deployment automation

---

## 🛡️ [NetAudit](https://github.com/Grmishra123/netaudit)

Python-based network auditing tool for port scanning, service detection, banner grabbing, subdomain enumeration, and reporting.

### Tech
`Python` `Networking` `Security Auditing` `DNS`

### Highlights
- Multi-threaded TCP scanning
- Service detection
- Banner grabbing
- HTML and JSON reports
- Risk assessment
- Custom scan profiles

---

# Skills

```text
Security        RSA · AES-GCM · JWT · OAuth2 · Authentication · OWASP
Languages       Python · SQL · Bash · JavaScript
Backend         FastAPI · REST APIs · PostgreSQL · SQLite
DevOps          Docker · GitHub Actions · Linux · Nginx
Networking      DNS · SSL/TLS · Reverse Proxy · Cloudflare
Tools           Git · Redis · Pytest · VS Code
```

---

# GitHub Stats

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=Grmishra123&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=60a5fa&icon_color=60a5fa&text_color=e2e8f0&count_private=true" />

<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Grmishra123&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=60a5fa&text_color=e2e8f0" />

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=Grmishra123&theme=tokyonight&hide_border=true&background=0f172a&stroke=60a5fa&ring=60a5fa&fire=60a5fa&currStreakLabel=e2e8f0&sideLabels=e2e8f0&dates=94a3b8)

</div>

---

# Contact

- LinkedIn: https://www.linkedin.com/in/grishab-mishra-741786349/
- GitHub: https://github.com/Grmishra123
- Email: mishra.secure999@gmail.com

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=120&section=footer)

</div>
