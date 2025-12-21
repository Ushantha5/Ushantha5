
# GitHub Action for generating a contribution graph with a snake eating your contributions.

name: Generate Snake

# Controls when the action will run. This action runs every 6 hours.

on:
  schedule:
      # every 6 hours
    - cron: "0 */6 * * *"

# This command allows us to run the Action automatically from the Actions tab.
  workflow_dispatch:

# The sequence of runs in this workflow:
jobs:
  # This workflow contains a single job called "build"
  build:
    # The type of runner that the job will run on
    runs-on: ubuntu-latest

    # Steps represent a sequence of tasks that will be executed as part of the job
    steps:

    # Checks repo under $GITHUB_WORKSHOP, so your job can access it
      - uses: actions/checkout@v2

    # Generates the snake  
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: Ushantha5
          # these next 2 lines generate the files on a branch called "output". This keeps the main branch from cluttering up.
          gif_out_path: dist/github-contribution-grid-snake.gif
          svg_out_path: dist/github-contribution-grid-snake.svg

     # show the status of the build. Makes it easier for debugging (if there's any issues).
      - run: git status

      # Push the changes
      - name: Push changes
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          branch: master
          force: true

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          # the output branch we mentioned above
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
## Hi there 👋
<p align="left">
  <img src="https://komarev.com/ghpvc/?username=Ushantha5&color=blue" />
  <a href="https://www.youtube.com/@Mr.Ushantha/playlists">
    <img src="https://img.shields.io/youtube/channel/subscribers/UCMhhk4PwFN5brZJks8Nr4aQ?style=social" />
  </a>
</p>

<h1>Hello < World >! I'm Mr ushantha 👋</h1>


<h3>Full-Stack Developer | 3D Game Developer | CEO – Mr5</h3>

---

<img src="[https://media2.dev.to/dynamic/image/width=1080,height=1080,fit=cover,gravity=auto,format=auto/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9dogbs90xhi2j1osxlni.jpg](https://cdn.dribbble.com/userupload/22408110/file/original-dd8968e341f92b175cb61748f7ebd6c0.gif)" />
🌐 **Website:** https://mr5school.vercel.app  
✍️ **Blog:** https://medium.com/@ushanthamr  
📺 **YouTube:** https://www.youtube.com/@Mr.Ushantha/playlists  
💻 **GitHub:** https://github.com/Ushantha5  

---

## 💻 Tech Stack

![JavaScript](https://img.shields.io/badge/javascript-black?style=for-the-badge&logo=javascript)
![React](https://img.shields.io/badge/react-black?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/nodejs-black?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/mongodb-black?style=for-the-badge&logo=mongodb)
![Python](https://img.shields.io/badge/python-black?style=for-the-badge&logo=python)

---

## ⏱ Coding Activity

![Wakatime](https://wakatime.com/static/img/ScreenShots/editor-and-dashboard-b.png)

---

## 😂 Programming Joke

![Jokes Card](https://readme-jokes.vercel.app/api?theme=dark)

---

### 🎵 Favorite Song
🔊 Nee Singam Dhan –  

<audio controls>
  <source src="  https://www.masstamilan.dev/2466/nee-singam-dhan-mp3-song " type="audio/mpeg">
  <source src="audiofile.ogg" type="audio/ogg">
  https://www.masstamilan.dev/2466/nee-singam-dhan-mp3-song 

</audio>

<!--
**Ushantha5/Ushantha5** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
<img src="[https://upload.wikimedia.org/wikipedia/commons/2/2c/Rotating_earth_%28large%29.gif](https://mir-s3-cdn-cf.behance.net/project_modules/hd/5eeea355389655.59822ff824b72.gif)" />


<img src="https://media.licdn.com/dms/image/v2/D4E03AQFj9cC2eg0wFg/profile-displayphoto-crop_800_800/B4EZp3wzcnIoAI-/0/1762945875011?e=1767225600&v=beta&t=0KNJnTtGfR97Wwz-sZweNH3MQlDRXX8L3hyz6GwvPPA" />


<img src="https://media.licdn.com/dms/image/v2/D4E16AQEq3lEHUvp8iQ/profile-displaybackgroundimage-shrink_350_1400/B4EZj5MUU0IIAY-/0/1756527414060?e=1767225600&v=beta&t=z0KprEy15rjprnUUviVh_H1cKVIk5OvpBm_eqRqpkho" />

