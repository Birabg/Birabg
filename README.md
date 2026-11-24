
<div align="center">

  <a href="mailto:biragirma4@gmail.com">
    <img src="assets/hero.svg" width="100%" alt="Bira Girma | Design Engineer" />
  </a>

  <h3>Design Engineer · ProductDesigner · Developer</h3>

  <p>
    I turn ideas into thoughtful digital experiences.<br/>
    Designing interfaces, building products, and exploring the technology behind them.
  </p>

  <p>
    <a href="https://www.linkedin.com/in/bira-girma-441a08319">
      <img src="https://img.shields.io/badge/LinkedIn-0E1330?style=for-the-badge&logo=linkedin&logoColor=0A66C2" />
    </a>
    <a href="https://www.behance.net/biragirma">
      <img src="https://img.shields.io/badge/Behance-0E1330?style=for-the-badge&logo=behance&logoColor=1769FF" />
    </a>
    <a href="https://t.me/Bira_G">
      <img src="https://img.shields.io/badge/Telegram-0E1330?style=for-the-badge&logo=telegram&logoColor=26A5E4" />
    </a>
    <a href="mailto:biragirma4@gmail.com">
      <img src="https://img.shields.io/badge/Email-0E1330?style=for-the-badge&logo=gmail&logoColor=EA4335" />
    </a>
  </p>

  <p>
    <img src="https://komarev.com/ghpvc/?username=Birabg&style=flat-square&color=0D99FF&label=PROFILE+VIEWS" />
  </p>

</div>

---

name: Profile Summary Cards

on:
  schedule:
    - cron: "0 0 * * *"   # updates daily
  workflow_dispatch:       # lets you run it manually

jobs:
  build:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: actions/checkout@v4
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}
          BRANCH_NAME: main

## 📊 GitHub Statistics

<div align="center">

  <img width="100%" src="./profile-summary-card-output/tokyonight/0-profile-details.svg" alt="Profile details" />

  <br/><br/>

  <img height="180" src="./profile-summary-card-output/tokyonight/3-stats.svg" alt="GitHub statistics" />
  <img height="180" src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="Most used languages" />

  <br/><br/>

  <a href="https://git.io/streak-stats">
    <img width="80%" src="https://streak-stats.demolab.com?user=Birabg&hide_border=true&background=0E1330&stroke=1E2650&ring=0D99FF&fire=0D99FF&currStreakLabel=0D99FF&sideLabels=B4BCE0&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=7F89B8" alt="GitHub contribution streak" />
  </a>

</div>

