<!-- 🔥 Animated Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,100:0072ff&height=200&section=header&text=Kishan%20Sahu&fontSize=45&fontColor=ffffff&animation=fadeIn" />

<h1 align="center">Hey 👋 I'm Kishan Sahu</h1>
<h3 align="center">🚀 BCA Student | Full Stack Developer | AI Enthusiast</h3>

---

<!-- 🔥 Typing Animation -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Smart+AI+Developer;Full+Stack+Engineer;Django+Lover;Always+Learning+New+Tech&center=true&width=500&height=50">
</p>

---

## 👨‍💻 About Me

🔭 Building: Smart AI + Web Projects  
👯 Open to: Collaboration & Hackathons  
🤝 Need help with: Scaling & AI Models  
🌱 Learning: Full Stack + AI Integration  
💬 Ask me: Anything Tech 😄  
⚡ Fun fact: Debugging is my cardio 💻🔥  

---

## 🧠 Who Am I?

```js
const kishan = {
  education: "BCA Student",
  focus: ["Full Stack Development", "AI Projects"],
  skills: ["HTML", "CSS", "JavaScript", "Python", "Django"],
  currentGoal: "Build impactful real-world applications 🚀",
};
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: CodezByKS
          outputs: |
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
