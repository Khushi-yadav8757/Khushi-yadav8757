<!-- ================= HERO SECTION ================= -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=34&pause=1000&color=00F7FF&center=true&vCenter=true&width=950&lines=Hey+%F0%9F%91%8B+I'm+Khushi+Yadav;3rd+Year+B.Tech+CSE+Student;Python+%7C+SQL+%7C+Data+Analytics+Enthusiast;DSA+Explorer+%7C+Future+ML+Engineer;Open+Source+Contributor+in+Progress" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Khushi-yadav8757&label=Profile%20Views&color=0e75b6&style=flat" />
</p>

---

# 🚀 About Me


+ 🎓 3rd Year B.Tech CSE student at KCC Institute of Technology and Management
+ 💡 Exploring Machine Learning, Data Analytics & Open Source
+ 🧠 Strong interest in DSA & Problem Solving
+ 🚀 Building real-world projects step-by-step
+ 🎯 Goal: Become a Machine Learning Engineer

🛠️ Tech Stack
🚀 Programming Languages
<p align="center"> <img src="https://skillicons.dev/icons?i=python,cpp,c,java"/> </p>
📊 Data Analytics & ML
<p align="center"> <img src="https://skillicons.dev/icons?i=numpy,pandas,matplotlib"/> <img src="https://img.shields.io/badge/Seaborn-9E3F9E?style=for-the-badge"/> <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge"/> </p>
🧰 Tools & Platforms
<p align="center"> <img src="https://skillicons.dev/icons?i=git,github,vscode,jupyter,html"/> </p>
🌱 Currently Learning
Machine Learning
Data Analysis
Open Source Contribution
Data Structures & Algorithms
📂 Featured Projects
🔹 Movie Recommendation System
   → Machine Learning based recommendation engine
   → Uses cosine similarity

🔹 Data Analysis Dashboard
   → Real-world dataset insights
   → Pandas + Matplotlib

🔹 DSA Problem Solver
   → Regular LeetCode practice
   → Focus on strong fundamentals
🌐 Connect With Me
<p align="center"> <a href="mailto:kky957242@gmail.com"> <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail"/> </a> <a href="https://www.linkedin.com/in/khushi-yadav8757"> <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/> </a> <a href="https://leetcode.com/u/khushi_kyad/"> <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode"/> </a> </p>
📊 GitHub Stats
<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=Khushi-yadav8757&show_icons=true&theme=tokyonight"/> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Khushi-yadav8757&layout=compact&theme=tokyonight"/> </p>
🔥 GitHub Streak
<p align="center"> <img src="https://github-readme-streak-stats.herokuapp.com/?user=Khushi-yadav8757&theme=tokyonight"/> </p>
🏆 GitHub Trophies
<p align="center"> <img src="https://github-profile-trophy.vercel.app/?username=Khushi-yadav8757&theme=tokyonight&row=1&column=6"/> </p>
🐍 Contribution Snake Animation
<p align="center"> <img src="https://raw.githubusercontent.com/Khushi-yadav8757/Khushi-yadav8757/output/snake.svg" alt="Snake animation"/> </p>
🎯 Open Source Goals
+ Make meaningful contributions
+ Fix bugs & improve documentation
+ Build strong GitHub presence
+ Collaborate with developers worldwide
🚀 Coding Journey
Learning Daily
Building Consistently
Improving Step-by-Step

Focused on becoming a strong ML Engineer 🚀

---

# 🐍 IMPORTANT — Snake Animation Setup (1 baar karna padega)

Ye step **bahut important hai**, warna snake animation nahi chalega.

### Step 1  
Apne profile repo me jao:


Khushi-yadav8757


---

### Step 2  
Folder create karo:


.github/workflows


---

### Step 3  
File create karo:


snake.yml


---

### Step 4  
Isme ye code paste karo:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"

  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Khushi-yadav8757
          outputs: |
            dist/snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
