### Hi there 👋

<!--
**CodeChenxi/CodeChenxi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
![](https://github-readme-stats.vercel.app/api?username=CodeChenxi)


游客您好！欢迎来到我的主页。

自我介绍一下，我是一名大三学生，是2023的考研党。我将会在这里分享我考研期间的学习生活和一些笔记。

name: WakaTime Readme

on:
  push:
    branches:
      - master
  schedule:
    - cron: '0 19 * * *'

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
