# Study_Space_Main_Page
All the Study Space page Devs are requested to just fork this repo and start working on it and when work got completed just push the request and the remainaing part will be done by the Github Reviewer team

[![Hacktoberfest 2025](https://img.shields.io/badge/Hacktoberfest-2025-blueviolet)](https://hacktoberfest.com/)

<!-- ============================
     Study Space — Animated README
     Single-file: Neon + Soft Aesthetic
     Paste this whole file into README.md
   ============================ -->

<!-- Neon Animated Header (dark, glowing) -->
<div align="center">
  <svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="neonGrad" x1="0" x2="1" y1="0" y2="1">
        <stop offset="0%" stop-color="#00f0ff"/>
        <stop offset="45%" stop-color="#8a2be2"/>
        <stop offset="100%" stop-color="#ff6ec7"/>
      </linearGradient>

      <filter id="glow">
        <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <filter id="softGlow">
        <feGaussianBlur stdDeviation="2.5" result="soft"/>
        <feMerge>
          <feMergeNode in="soft"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <linearGradient id="barGrad" x1="0" x2="1">
        <stop offset="0%" stop-color="#00F0FF" />
        <stop offset="50%" stop-color="#8A2BE2" />
        <stop offset="100%" stop-color="#FF6EC7" />
      </linearGradient>
    </defs>

    <!-- Background rectangle for dark header -->
    <rect width="1200" height="220" rx="10" ry="10" fill="#05060a"/>
    <!-- Animated diagonal shimmer -->
    <rect x="-1200" y="0" width="2400" height="220" fill="url(#barGrad)" opacity="0.06">
      <animate attributeName="x" from="-1200" to="1200" dur="10s" repeatCount="indefinite" />
    </rect>

    <!-- Neon Title (big) -->
    <text x="50%" y="55" text-anchor="middle" font-family="Inter, Roboto, sans-serif" font-size="36" fill="url(#neonGrad)" filter="url(#glow)" font-weight="700">
      ✨ Study Space — Command Center for Deep Focus
    </text>

    <!-- Neon subtitle with typing effect (SVG text + animated reveal) -->
    <g transform="translate(600,110)">
      <rect x="-540" y="-30" width="1080" height="60" fill="transparent"/>
      <text id="typing" x="-540" y="0" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="18" fill="#bfefff">
        <tspan id="t1"></tspan>
      </text>

      <!-- SMIL-based typing (characters appear one by one by animating textLength via tspan sequence) -->
      <text x="-540" y="0" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="18" fill="#bfefff" opacity="0">
        <tspan>
          <!-- Fallback invisible text so width is reserved -->
          Deep Focus • Timer • Notes • Music • Community
        </tspan>
      </text>
    </g>

    <!-- Animated pulsing "Start" CTA circle -->
    <g transform="translate(1100,170)" style="cursor:pointer;">
      <circle cx="0" cy="0" r="26" fill="url(#neonGrad)" filter="url(#glow)"/>
      <circle cx="0" cy="0" r="26" fill="none" stroke="url(#neonGrad)" stroke-width="2">
        <animate attributeName="r" values="26;34;26" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
      </circle>
      <text x="0" y="6" font-size="12" font-family="Inter, sans-serif" text-anchor="middle" fill="#05060a" font-weight="800">START</text>
    </g>

    <!-- small neon footer line -->
    <rect x="40" y="190" width="1120" height="6" rx="3" ry="3" fill="url(#barGrad)" opacity="0.18"/>
  </svg>
</div>

<!-- Spacer -->
<p></p>

<!-- Combined Dual-Theme Section: Neon left card + Soft right card -->
<table width="100%"><tr>

<td width="50%" valign="top">
<!-- Neon Card (dark) -->
<div style="background:#070713;border-radius:12px;padding:18px;margin-right:10px;box-shadow:0 10px 30px rgba(138,43,226,0.12);">
  <h2 style="color:#bdefff;margin:0 0 6px 0;font-family:Inter, sans-serif;">🧠 Intelligent Focus Timer</h2>
  <p style="color:#9fdcff;margin-top:0;font-family:Inter, sans-serif;">
    Smart Pomodoro sprints, adaptive breaks, and session milestones — built to form habits, not stress you.
  </p>

  <!-- animated progress-like bar -->
  <svg width="100%" height="36" viewBox="0 0 320 36">
    <defs>
      <linearGradient id="nBar" x1="0" x2="1">
        <stop offset="0%" stop-color="#00F0FF"/>
        <stop offset="60%" stop-color="#8A2BE2"/>
        <stop offset="100%" stop-color="#FF6EC7"/>
      </linearGradient>
      <filter id="g2"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    </defs>
    <rect x="0" y="6" rx="8" ry="8" width="320" height="24" fill="#0b0c10"/>
    <rect x="4" y="10" rx="6" ry="6" width="0" height="16" fill="url(#nBar)" filter="url(#g2)">
      <animate attributeName="width" from="0" to="312" dur="8s" repeatCount="indefinite" />
    </rect>
  </svg>

  <p style="color:#88d8ff;margin:6px 0 0 0;font-size:13px;">Session streak: <strong>5 🔥</strong> • Avg focus: <strong>48m</strong></p>
</div>
</td>

<td width="50%" valign="top">
<!-- Soft Aesthetic Card (light) -->
<div style="background:linear-gradient(135deg,#fff7fb,#f3f8ff);border-radius:12px;padding:18px;margin-left:10px;box-shadow:0 8px 20px rgba(99,102,241,0.06);">
  <h2 style="color:#6b4b9b;margin:0 0 6px 0;font-family:Inter, sans-serif;">📝 Quick Notes — Floating & Synced</h2>
  <p style="color:#44475a;margin-top:0;font-family:Inter, sans-serif;">
    Tiny, cozy notepad that floats above your workspace — auto-saves to the cloud and always available.
  </p>

  <!-- soft animated pill icons -->
  <svg width="100%" height="56" viewBox="0 0 360 56" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="soft1" x1="0" x2="1"><stop offset="0" stop-color="#ffd7e8"/><stop offset="1" stop-color="#e6f2ff"/></linearGradient>
      <linearGradient id="soft2" x1="0" x2="1"><stop offset="0" stop-color="#fce6ff"/><stop offset="1" stop-color="#e9fff4"/></linearGradient>
    </defs>
    <rect x="6" y="8" rx="12" ry="12" width="110" height="40" fill="url(#soft1)">
      <animate attributeName="x" values="6;12;6" dur="4s" repeatCount="indefinite"/>
    </rect>
    <rect x="130" y="8" rx="12" ry="12" width="110" height="40" fill="url(#soft2)">
      <animate attributeName="x" values="130;136;130" dur="4.4s" repeatCount="indefinite"/>
    </rect>
    <rect x="254" y="8" rx="12" ry="12" width="100" height="40" fill="url(#soft1)">
      <animate attributeName="x" values="254;248;254" dur="4.2s" repeatCount="indefinite"/>
    </rect>
  </svg>

  <p style="color:#5a5f74;margin:6px 0 0 0;font-size:13px;">All notes auto-sync across devices • Quick markdown support • Search instantly</p>
</div>
</td>

</tr></table>

<!-- Section divider with shimmering SVG -->
<div align="center" style="margin:18px 0;">
  <svg width="90%" height="32" viewBox="0 0 900 32" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="divider" x1="0" x2="1">
        <stop offset="0" stop-color="#fff" stop-opacity="0.05" />
        <stop offset="0.25" stop-color="#00F0FF" stop-opacity="0.14" />
        <stop offset="0.5" stop-color="#8A2BE2" stop-opacity="0.18" />
        <stop offset="0.75" stop-color="#FF6EC7" stop-opacity="0.14" />
        <stop offset="1" stop-color="#fff" stop-opacity="0.05" />
      </linearGradient>
    </defs>
    <rect x="0" y="8" rx="8" ry="8" width="900" height="16" fill="url(#divider)">
      <animate attributeName="x" values="-900;900" dur="12s" repeatCount="indefinite"/>
    </rect>
    <text x="50%" y="12" text-anchor="middle" alignment-baseline="middle" font-family="Inter, sans-serif" font-size="12" fill="#9fbfff" opacity="0.9">— • — • — blended neon + soft aesthetic — • — • —</text>
  </svg>
</div>

<!-- Core Features Grid with small animated GIFs & fallback -->
<div align="center">

| Feature | Live Preview |
|---|---:|
| 🎬 **Embedded Lectures** — Background-layered YouTube player | <img src="https://media.giphy.com/media/3o6Zt6D8D9hQ9Q2f9m/giphy.gif" width="220" alt="video preview" /> |
| 🎧 **Spotify Playlists** — Auto-play focus music | <img src="https://media.giphy.com/media/26BRuo6sLetdllPAQ/giphy.gif" width="220" alt="music preview" /> |
| 🏆 **Community Leaderboards** — Points and streaks | <img src="https://media.giphy.com/media/l0MYyDa8K8A3nQmD6/giphy.gif" width="220" alt="leaderboard preview" /> |

</div>

<!-- Animated "How it works" section with step bubbles -->
<div align="center" style="margin-top:20px;">
  <svg width="90%" height="120" viewBox="0 0 900 120" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="stepG1" x1="0" x2="1"><stop offset="0" stop-color="#ffd7e8"/><stop offset="1" stop-color="#e6f2ff"/></linearGradient>
      <linearGradient id="stepG2" x1="0" x2="1"><stop offset="0" stop-color="#00F0FF"/><stop offset="1" stop-color="#8A2BE2"/></linearGradient>
    </defs>

    <!-- Step 1 -->
    <g transform="translate(100,20)">
      <circle cx="0" cy="20" r="28" fill="url(#stepG2)" filter="url(#glow)">
        <animate attributeName="r" values="28;22;28" dur="4s" repeatCount="indefinite"/>
      </circle>
      <text x="0" y="26" font-family="Inter, sans-serif" font-size="12" text-anchor="middle" fill="#05060a">1</text>
      <text x="60" y="18" font-family="Inter, sans-serif" font-size="14" fill="#bfefff">Start a sprint</text>
    </g>

    <!-- Step 2 -->
    <g transform="translate(360,20)">
      <circle cx="0" cy="20" r="24" fill="url(#stepG1)">
        <animate attributeName="r" values="24;28;24" dur="4.5s" repeatCount="indefinite"/>
      </circle>
      <text x="0" y="26" font-family="Inter, sans-serif" font-size="12" text-anchor="middle" fill="#5a5f74">2</text>
      <text x="60" y="18" font-family="Inter, sans-serif" font-size="14" fill="#6b4b9b">Take smart breaks</text>
    </g>

    <!-- Step 3 -->
    <g transform="translate(620,20)">
      <circle cx="0" cy="20" r="26" fill="url(#stepG2)" filter="url(#glow)">
        <animate attributeName="r" values="26;30;26" dur="5s" repeatCount="indefinite"/>
      </circle>
      <text x="0" y="26" font-family="Inter, sans-serif" font-size="12" text-anchor="middle" fill="#05060a">3</text>
      <text x="60" y="18" font-family="Inter, sans-serif" font-size="14" fill="#bfefff">Review & reward</text>
    </g>

    <!-- connecting lines -->
    <line x1="140" y1="20" x2="320" y2="20" stroke="#7fb3ff" stroke-width="2" stroke-linecap="round">
      <animate attributeName="stroke-opacity" values="0.2;0.9;0.2" dur="6s" repeatCount="indefinite"/>
    </line>
    <line x1="380" y1="20" x2="560" y2="20" stroke="#f2b3e8" stroke-width="2" stroke-linecap="round">
      <animate attributeName="stroke-opacity" values="0.2;0.9;0.2" dur="5s" repeatCount="indefinite"/>
    </line>
  </svg>
</div>

<!-- Tech stack icons (hosted small images) -->
<div align="center" style="margin-top:18px;">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,firebase,spotify,youtube" alt="tech icons" />
</div>

<!-- Call-to-action with soft gradient button and neon small label -->
<div align="center" style="margin-top:22px;">
  <a href="https://github.com/your-username/study-space" target="_blank" rel="noopener">
    <svg width="420" height="72" viewBox="0 0 420 72" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="ctaGrad" x1="0" x2="1"><stop offset="0" stop-color="#ffd7e8"/><stop offset="1" stop-color="#cfe9ff"/></linearGradient>
        <linearGradient id="ctaNeon" x1="0" x2="1"><stop offset="0" stop-color="#00F0FF"/><stop offset="1" stop-color="#FF6EC7"/></linearGradient>
      </defs>
      <rect x="0" y="0" rx="12" ry="12" width="420" height="72" fill="url(#ctaGrad)" />
      <rect x="6" y="6" rx="10" ry="10" width="408" height="60" fill="#fff" opacity="0.06" />
      <text x="50" y="40" font-family="Inter, sans-serif" font-size="18" fill="#3b3b4a">Open Study Space on GitHub</text>
      <rect x="320" y="16" rx="10" ry="10" width="84" height="40" fill="url(#ctaNeon)" filter="url(#glow)">
        <animate attributeName="x" values="320;316;320" dur="2.8s" repeatCount="indefinite"/>
      </rect>
      <text x="362" y="40" font-family="Inter, sans-serif" font-size="14" text-anchor="middle" fill="#05060a" font-weight="700">Explore</text>
    </svg>
  </a>
</div>

---

## 🎨 Why both styles?
I combined both looks to give you the best of both worlds:
- **Neon / Dashboard** for energy, focus, and a high-contrast control center vibe.  
- **Soft / Cozy** for notes, reading, and calm parts of your flow.

This single README shows how the UI could *feel* — neon for the command center, pastel for the calm note-taking space.

---

## 🛠️ Tech Notes (for README maintainers)
- The animations are SVG-only (SMIL & basic SVG `<animate>`). These work on GitHub markdown rendering.  
- If you prefer other animated gifs (app previews), replace the GIF URLs with your exported GIFs in place.  
- Want extra badges or dynamic stat cards? I can embed GitHub stat images (e.g., `github-readme-stats`) below.

---

## 🤝 Contribute
- Fork ➜ Branch ➜ PR  
- Ideas: dark-only mode toggle mockup, more animated widgets (calendar, habit streaks), or animated onboarding flow.

---

<p align="center" style="margin-top:18px;">
  Crafted with ⚡ + ☁️ by <a href="https://github.com/Soumya-codr">Soumya Sagar</a>
</p>
