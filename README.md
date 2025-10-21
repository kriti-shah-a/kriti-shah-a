<p align="center">
  <img src="https://raw.githubusercontent.com/kriti-shah-a/kriti-shah-a/output/snake.svg" alt="snake" />
</p>

<!-- Profile README for @kriti-shah-a -->

<h1 align="center">Hi, I'm Kriti Shah 👋</h1>
<p align="center">
  Developer–Designer @ UF • CS + Marketing • AI Fundamentals & Applications
</p>

<p align="center">
  <a href="mailto:kritishah989@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-kritishah989%40gmail.com-blue"></a>
  <a href="https://linkedin.com/in/kritiashah"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-kritiashah-0a66c2?logo=linkedin&logoColor=white"></a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=kriti-shah-a&style=flat&color=blueviolet">
</p>

---

### ⚙️ Tech I Use
<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232a?logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/React%20Native-20232a?logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-003B57?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Leaflet.js-199900?logo=leaflet&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/DaVinci%20Resolve-1f2b3e?logo=davinciresolve&logoColor=white" />
  <img src="https://img.shields.io/badge/Canva-00C4CC?logo=canva&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
</p>

---

### 🧠 About
I build products where **engineering meets storytelling**: full-stack web/mobile apps, clean UI systems, and content that moves people.  
- **CS + Marketing @ University of Florida (’27)** — Dean’s List (x2)  
- **Core skills:** Frontend (React/TS), Mobile (React Native), Data viz (Leaflet), SQL, UI/UX, Video

---

### 🔭 Highlight Projects
- **DoneTogether** — Collaborative goal-tracking (TypeScript, React, Clerk, MongoDB)  
  Reusable component system, real-time incentives & leaderboards.
- **StudyUp!** — Multiplayer study game (React Native)  
  Gyroscope gestures for hands-free gameplay; improved vocab retention by ~40%.
- **Am I Safe?** — Crime heatmaps for 61k+ students (JavaScript + Leaflet.js)  
  Top-10 prize out of 160+ entries; optimized queries with hash tables & heaps.

> 💡 Looking for teammates on creative CS x Design projects — reach out!

---

### 📊 GitHub Cards (Live)
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=kriti-shah-a&show_icons=true&theme=tokyonight&rank_icon=github" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kriti-shah-a&layout=compact&theme=tokyonight&langs_count=8" />
</p>

<p align="center">
  <img height="190" src="https://streak-stats.demolab.com?user=kriti-shah-a&theme=tokyonight&hide_border=false" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=kriti-shah-a&theme=algolia&no-frame=true&no-bg=true&column=6" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kriti-shah-a&theme=tokyo-night" alt="activity-graph" />
</p>

---

### 🧩 Experience (Quick Hits)
- **Web Developer Intern — Rimage Solutions**  
  25% faster load times; mobile-first rebuild; React enhancements.
- **Chief Marketing Officer — Expressive Marketing Agency**  
  33+ videos, 18 posts, 1 influencer → $1k+ revenue for clients.
- **Head of Marketing — Gathr (UF)**  
  Connected **1k+ orgs → 61k students**; 51k+ views across 8 campaign videos.

---

### 📬 Contact
**Email:** [kritishah989@gmail.com](mailto:kritishah989@gmail.com)  
**LinkedIn:** [linkedin.com/in/kritiashah](https://linkedin.com/in/kritiashah)

---

<details>
<summary>🐍 Optional: Contribution “Snake” (enable via Actions)</summary>

1) Create: `.github/workflows/snake.yml`  
2) Paste:
  
```yml
name: Generate snake
on:
  schedule: [{cron: "0 0 * * *"}]
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: kriti-shah-a
          outputs: dist/snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
