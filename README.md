- 👋 Hi, I’m @IlyasBaratov
- 🎓 Software Engineering student (Junior) at Washington State University
- 📫 How to reach me: ilyas.baratoff@gmail.com 
- 🌐 Website:
https://connect.ilyasbaratov.com/
<!---
IlyasBaratov/IlyasBaratov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!-- <p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IlyasBaratov&layout=compact&theme=github_dark&langs_count=8" />
</p> -->

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


