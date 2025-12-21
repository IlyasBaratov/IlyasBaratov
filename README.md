<!---- 👋 Hi, I’m @IlyasBaratov
- 🎓 Software Engineering student (Junior) at Washington State University
- 📫 How to reach me: ilyas.baratoff@gmail.com 
- 🌐 Website:
https://connect.ilyasbaratov.com/

IlyasBaratov/IlyasBaratov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.


<!-- <p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IlyasBaratov&layout=compact&theme=github_dark&langs_count=8" />
</p>

<p aling="center">
  <img src="https://github.com/IlyasBaratov/IlyasBaratov/blob/output/github-contribution-grid-snake.svg" />
</p>
 -->

 <!-- PROFILE README for: IlyasBaratov -->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1200&color=58A6FF&center=true&vCenter=true&width=820&lines=Hi%2C+I%27m+Ilyas+Baratov+%F0%9F%91%8B;Software+Engineering+Student;Java+%7C+Python+%7C+Spring+Boot;Building+Analytics+%26+Weather+Apps;Always+learning%2C+always+building" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/IlyasBaratov">
    <img src="https://komarev.com/ghpvc/?username=IlyasBaratov&style=flat-square&color=58A6FF" alt="Profile views" />
  </a>
  <a href="https://github.com/IlyasBaratov?tab=followers">
    <img src="https://img.shields.io/github/followers/IlyasBaratov?label=Followers&style=flat-square&color=58A6FF" alt="Followers" />
  </a>
  <a href="https://github.com/IlyasBaratov?tab=stars">
    <img src="https://img.shields.io/github/stars/IlyasBaratov?label=Stars&style=flat-square&color=58A6FF" alt="Stars" />
  </a>
</p>

---

### 👨‍💻 About me
- 🎓 Software Engineering student  
- ⚙️ Interested in backend, DevOps, and data-driven apps  
- 🧠 Strongest languages: **Java** and **Python** (Spring Boot, APIs, databases)

---

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=IlyasBaratov&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" alt="GitHub Stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=IlyasBaratov&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=IlyasBaratov&theme=github-dark&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=IlyasBaratov&theme=github-dark&hide_border=true&area=true" alt="Activity Graph" />
</p>

---

## 🐍 Animated contribution snake (optional, looks awesome)
This one needs a GitHub Action to generate the SVG automatically.

### 1) Create this file:
**`.github/workflows/snake.yml`** in your `IlyasBaratov` profile repo

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: IlyasBaratov
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}



