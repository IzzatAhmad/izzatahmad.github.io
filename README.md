<!-- Typing Header -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=22&pause=1000&color=0055FF&center=true&vCenter=true&width=500&lines=hey%2C+I'm+Izzat+%F0%9F%91%8B;CS+student+by+day%2C+debugger+by+night;always+building+something." alt="Typing SVG" />
</p>

<br/>

---

I'm a CS student from Malaysia who genuinely enjoys building things — not just to finish assignments, but because shipping something that actually works is a good feeling. Right now I'm deep into my final year project, **RailTrack**, a self-hosted platform for managing FYPs with Docker, role-based workflows, and GitHub integration.

I write mostly Java (JSP/Servlet, the old-school kind), pick up whatever's needed for the job, and have a soft spot for clean back-end logic over flashy front-end tricks — though I'll do both when I have to.

When I'm not coding, I'm probably in a hackathon or figuring out why a container won't start.

---

## what I work with

<p>
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/JSP%20%2F%20Servlet-%23ED8B00.svg?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-%236DB33F.svg?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-%234479A1.svg?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-%233776AB.svg?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-%23777BB4.svg?style=flat-square&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML%20%26%20CSS-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white"/>
</p>

---

## stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=IzzatAhmad&show_icons=true&hide_border=true&title_color=0055FF&icon_color=0055FF&text_color=111111&bg_color=f7f7f4" height="160"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IzzatAhmad&layout=compact&hide_border=true&title_color=0055FF&text_color=111111&bg_color=f7f7f4" height="160"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=IzzatAhmad&theme=default&hide_border=true&ring=0055FF&fire=0055FF&currStreakLabel=0055FF&background=f7f7f4" height="160"/>
</p>

---

## pac-man ate my commits

<p align="center">
  <img src="https://raw.githubusercontent.com/IzzatAhmad/IzzatAhmad/output/pacman.svg" alt="Pac-Man contribution graph" />
</p>

<details>
<summary>⚙️ how this works (setup)</summary>

Create `.github/workflows/pacman.yml` in this repo, paste the workflow below, then go to **Actions → Enable Actions** and run it once manually. After that it auto-updates daily.

```yaml
name: Generate Pac-Man

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - name: Generate Pac-Man SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/pacman.svg?color_snake=0055FF&color_dots=#f7f7f4,#bdd4ff,#7aaaff,#3377ff,#0055ff&game=pacman

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

## find me

<p>
  <a href="https://github.com/IzzatAhmad">
    <img src="https://img.shields.io/badge/GitHub-%23181717.svg?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/izzatahmad00/">
    <img src="https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://stackoverflow.com/users/15065735/izzat-ahmad">
    <img src="https://img.shields.io/badge/Stack%20Overflow-%23F58025.svg?style=flat-square&logo=stackoverflow&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=13&pause=2000&color=0055FF&center=true&vCenter=true&width=400&lines=thanks+for+stopping+by+%F0%9F%94%B5" alt="footer" />
</p>
