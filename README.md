<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C9A7&height=220&section=header&text=Anwar%20Mohammed%20Koji&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20Python%20Enthusiast%20%7C%20ALX%20Fellow&descAlignY=58&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=00C9A7&center=true&vCenter=true&width=650&lines=Building+clean%2C+scalable+software;Python+%7C+Django+%7C+FastAPI+%7C+React;ALX+Software+Engineering+Fellow;Turning+curiosity+into+code+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<a href="https://github.com/Mahiamk"><img src="https://img.shields.io/github/followers/Mahiamk?label=Followers&style=for-the-badge&color=00C9A7&logo=github&logoColor=white"/></a>
<a href="mailto:mahikomohammed@gmail.com"><img src="https://img.shields.io/badge/Email-Me-2C5364?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/anwarkoji4u/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0F2027?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=Mahiamk&label=Profile%20Views&style=for-the-badge&color=00C9A7"/>

</div>

<br/>

## 👨‍💻 About Me

```python
class AnwarKoji:
    def __init__(self):
        self.name = "Anwar Mohammed Koji"
        self.role = "Full-Stack Developer @ ALX Software Engineering"
        self.stack = ["Python", "Django", "FastAPI", "React", "PostgreSQL"]
        self.mission = "Solving real-world problems through clean, scalable code"
        self.currently_learning = ["Docker", "DevOps fundamentals", "AI-powered APIs"]

    def spark(self):
        return "How does software power the world?"

    def say_hi(self):
        print("Let's build something impactful together 🚀")
```

I'm a driven **Full-Stack Developer** and **Computer Science student**, currently sharpening my craft as an **ALX Software Engineering Fellow**. My journey started with one question — *"How does software power the world?"* — and today I turn that curiosity into digital solutions that help businesses and communities thrive.

---

## 📊 Snapshot

<div align="center">

| 🚀 Projects Shipped | ⏳ Coding Hours | 🏆 Program | 🌍 Focus |
|:---:|:---:|:---:|:---:|
| **15+** | **1,200+ hrs** | ALX SE Fellow | Backend • Full-Stack |

</div>

> Numbers above are placeholders — plug in a [Wakatime](https://wakatime.com) badge for live coding-hour tracking, and update the project count as your portfolio grows (see the *Setup Notes* at the bottom for exact steps).

---

## 🔧 Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,js,c,java,html,css,bash&theme=dark" />

**Frameworks & Libraries**

<img src="https://skillicons.dev/icons?i=django,fastapi,react,bootstrap&theme=dark" />

**Databases, Tools & Platforms**

<img src="https://skillicons.dev/icons?i=postgres,sqlite,git,github,linux,vscode&theme=dark" />

</div>

---

## 🏗️ Featured Projects

<div align="center">

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🔍 Anomaly Detection ML Model</h3>
      <p align="center">A scalable machine learning pipeline for detecting anomalies in real-world data streams.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🌐 Full-Stack Web Platform</h3>
      <p align="center">A Django/FastAPI-powered backend paired with a React front end for real-world use cases.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
        <img src="https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB"/>
      </p>
    </td>
  </tr>
</table>

> 📌 Replace these with links to your actual pinned repositories — see *Setup Notes* below for a quick guide.

</div>

---

## 📈 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Mahiamk&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00C9A7&icon_color=00C9A7&text_color=c9d1d9" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Mahiamk&theme=radical&hide_border=true&background=0D1117&ring=00C9A7&fire=00C9A7&currStreakLabel=00C9A7" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mahiamk&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00C9A7&text_color=c9d1d9" height="165"/>

<img src="https://github-profile-trophy.vercel.app/?username=Mahiamk&theme=radical&no-frame=true&row=1&column=6" />

</div>

---

## 🐍 Contribution Graph

<div align="center">
  <img src="https://raw.githubusercontent.com/Mahiamk/Mahiamk/output/github-contribution-grid-snake.svg" alt="snake animation"/>
</div>
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *" # Runs every day
  workflow_dispatch:

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v4

      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: Mahiamk
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist

        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

> This animated snake needs a one-time GitHub Actions setup — instructions are in *Setup Notes* below.

---

## 🔥 What I Bring to the Table

- ✅ Clean, maintainable, and testable code
- ✅ Strong full-stack experience across frontend and backend
- ✅ Agile collaboration and reliable time management
- ✅ Fast learner, quick to adapt to new stacks and environments
- ✅ Clear communication and thorough documentation

---

## 📫 Let's Connect

<div align="center">

<a href="mailto:mahikomohammed@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/anwarkoji4u/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/Mahiamk"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

<i>"Open to collaboration, internships, and freelance opportunities — let's build something great."</i>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,50:2C5364,100:0F2027&height=100&section=footer" width="100%"/>

---

<details>
<summary>⚙️ Setup Notes (click to expand)</summary>

1. **Wakatime coding hours** — Sign up at [wakatime.com](https://wakatime.com), install the plugin for your editor, then replace the "Coding Hours" cell above with:
   `![Wakatime](https://wakatime.com/badge/user/YOUR_WAKATIME_USER_ID.svg)`
2. **Project count** — Update the "Projects Shipped" number as you complete and pin repositories.
3. **Featured projects table** — Swap in your real project names, descriptions, and links (wrap each title in `[Name](https://github.com/Mahiamk/repo)`).
4. **Snake contribution animation** — Follow the [platane/snk](https://github.com/Platane/snk) GitHub Action guide to auto-generate `github-contribution-grid-snake.svg` for your profile.
5. All stats/badges above pull live from GitHub, Vercel-hosted stat APIs, and skillicons.dev — no extra setup needed for those.

</details>
