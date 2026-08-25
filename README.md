# 👋 Hi, I'm Sooraj Poojary

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=36BCF7&width=600&lines=DevOps+Engineer;Cloud+%26+Infrastructure+Enthusiast;Linux+%7C+Docker+%7C+AWS;Always+Learning+New+Technology" />

## 🚀 About Me

💻 DevOps & Cloud Enthusiast  
🐳 Docker & Linux  
☁️ Cloud Infrastructure  
🔐 Networking & Security  
🚀 Building and deploying applications

## 🛠️ Technologies

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Sooraj45&show_icons=true&theme=dark)

## 🔥 Contribution Streak

![GitHub Streak](https://streak-stats.demolab.com?user=Sooraj45&theme=dark)

DevOps Engineer → Cloud & Infrastructure → Linux → Docker

## 📌 Featured Projects

- 💊 Pharmacy Management System
- 🐳 Docker Projects
- ☁️ Cloud Infrastructure
- 🔊 Text-to-Speech IoT

 name: Generate Snake Animation
 
on:
  schedule:
    - cron: "0 */6 * * *"    # runs every 6 hours
  push:
    branches:
      - main                 # runs on every push to main
  workflow_dispatch:         # allows manual trigger from the Actions tab
 
jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: Generate Snake SVG
        uses: Platane/snk@v3
        with:
          github_user_name: Sooraj45
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
 
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }} 

## 📫 Connect With Me

[GitHub](https://github.com/Sooraj45)
