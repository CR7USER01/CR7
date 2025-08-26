<img width="925" height="488" alt="Screenshot 2023-12-20 010829" src="https://github.com/user-attachments/assets/dfb3308e-8151-42d7-839c-9fc559132404" />
name: Generate Snake
on:
schedule: [{cron: "0 0 * * *"}] # every midnight UTC
workflow_dispatch:
push: {branches: [main]}


jobs:
build:
runs-on: ubuntu-latest
steps:
- uses: actions/checkout@v4
- uses: Platane/snk@v3
with:
github_user_name: your-username
outputs: |
dist/snake.svg
dist/snake-dark.svg?palette=github-dark
- uses: crazy-max/ghaction-github-pages@v4
with:
target_branch: output
build_dir: dist
env:
GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<h1 align="center">Hi 👋, I'm JITU</h1>
<h3 align="center">A passionate frontend developer from India</h3>

- 🌱 I’m currently learning **java script**

- 📫 How to reach me **tusarkhatoi07@gmail.com**

- ⚡ Fun fact **not funny**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> </p>

<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/CR7USER01"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="CR7USER01" /></a><a href="https://ko-fi.com/CR7USER01"> <img align="left" src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" height="50" width="210" alt="CR7USER01" /></a></p><br><br>


