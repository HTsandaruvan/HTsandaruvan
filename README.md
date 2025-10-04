<!-- Banner & Greeting -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0ABAB5&height=200&section=header&text=Harsha%20Tharuka&fontSize=40&fontColor=ffffff" alt="header"/>
</p>

<h2 align="center">👋 Hey there! I'm Harsha Tharuka</h2>
<h3 align="center">💻 Software Engineer | 🌍 Open Source Enthusiast</h3>

<p align="center">
  <a href="mailto:tsandaruvan298@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://twitter.com/" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1da1f2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/harsha-tharuka-sandaruvan-586a85233/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://stackoverflow.com/users/19280169/harsha" target="_blank">
    <img src="https://img.shields.io/badge/StackOverflow-f48024?style=for-the-badge&logo=stackoverflow&logoColor=white" />
  </a>
  <a href="https://medium.com/@tsandaruvan298" target="_blank">
    <img src="https://img.shields.io/badge/Medium-12100e?style=for-the-badge&logo=medium&logoColor=white" />
  </a>
</p>

<!-- Profile Views -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=HTsandaruvan&label=Profile%20views&color=0e75b6&style=flat" alt="HTsandaruvan" />
</p>

---

<!-- About Section -->
### 🙋‍♂️ About Me
- 🔭 I’m currently working on **Full Stack Web & Mobile Applications**
- 🌱 I’m learning **Cloud Engineering, DevOps, and Modern JavaScript Frameworks**
- 👨‍💻 All my projects are available at [My GitHub Repositories](https://github.com/HTsandaruvan?tab=repositories)
- 💬 Ask me about **Laravel, React.js, PHP, Node.js, Flutter, React Native**
- 📫 Reach me at **tsandaruvan298@gmail.com**
- ⚡ Fun fact: I love contributing to open-source and writing tech blogs!

---

<!-- Skills Section -->
### 🚀 Languages & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=laravel,vue,php,nodejs,js,ts,python,java,django,flask,go,flutter,react,redux,html,css,sass,tailwind,bootstrap,mysql,nextjs,postgres,mongodb,sqlite,aws,gcp,docker,kubernetes,nginx,git,linux,figma,heroku,redis,graphql,electron,postman,webpack" />
</p>

---

<!-- GitHub Stats -->
### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=HTsandaruvan&show_icons=true&theme=tokyonight" alt="HTsandaruvan" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HTsandaruvan&layout=compact&theme=tokyonight" alt="HTsandaruvan" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=HTsandaruvan&theme=tokyonight" alt="HTsandaruvan" />
</p>

---
name: Top GitHub Users
on:
  schedule:
    - cron: '0 * * * *'
  workflow_dispatch:
jobs:
  release:
    name: GitHub Active Users
    runs-on: ubuntu-20.04
    steps:
      - uses: actions/checkout@v2.3.4
        with:
          ref: ${{ github.head_ref }}
          token: ${{ secrets.CUSTOM_TOKEN }}
      - uses: actions/setup-node@v2.1.5
        with:
          node-version: 14.17.0
      - uses: gayanvoice/top-github-users-action@master
        env:
          CUSTOM_TOKEN: ${{ secrets.CUSTOM_TOKEN }}


<!-- Trophies -->
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=HTsandaruvan&theme=tokyonight&row=1&column=7" alt="trophies" />
</p>

---

<!-- Quote or Fun Footer -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&pause=1000&color=0e75b6&center=true&vCenter=true&width=435&lines=Happy+Coding!;Let's+build+something+amazing+together!;Open+to+collaboration+and+new+opportunities."/>
</p>
