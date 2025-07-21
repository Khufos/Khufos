<h1 align="center">🚀 Welcome to Khufos' Universe 👨‍🚀</h1>

<p align="center">
  <img src="https://github.com/Khufos/Khufos/blob/main/freekhufos.gif" alt="Khufos banner" />
</p>

---

<div align="center">
  <strong>I'm Iago Joseph</strong><br/>
  <em>I believe a great programming language is one that brings joy to the process of coding!</em>
</div>

---

## 🧭 Visitors Count

<p align="center">
  <strong>Real-time visitors</strong><br />
  <span id="visits" style="font-size: 32px; font-weight: bold;">Loading...</span>
</p>

<script>
  const counterKey = 'khufos-visit-count';

  fetch(`https://api.countapi.xyz/hit/${counterKey}/visits`)
    .then(res => res.json())
    .then(data => {
      let el = document.getElementById('visits');
      let i = 0;
      let target = data.value;
      let interval = setInterval(() => {
        el.innerText = i;
        if (i++ >= target) clearInterval(interval);
      }, 10);
    });
</script>

---

## 👨‍💻 About Me

- 🧠 Full-stack developer | JavaScript enthusiast  
- 🔐 Passionate about web security, clean code & developer experience  
- 🎓 Always learning: Node.js, TypeScript, React, Next.js  
- 💡 I build things that are fun, fast, and meaningful

---

## 🛠️ Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=flat-square&logo=typescript)
![Node.js](https://img.shields.io/badge/-Node.js-black?style=flat-square&logo=node.js)
![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react)
![Next.js](https://img.shields.io/badge/-Next.js-black?style=flat-square&logo=next.js)
![Express](https://img.shields.io/badge/-Express-black?style=flat-square&logo=express)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-black?style=flat-square&logo=postgresql)
![MongoDB](https://img.shields.io/badge/-MongoDB-black?style=flat-square&logo=mongodb)
![Docker](https://img.shields.io/badge/-Docker-black?style=flat-square&logo=docker)
![Linux](https://img.shields.io/badge/-Linux-black?style=flat-square&logo=linux)

</div>

---

## 🔥 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Khufos&show_icons=true&theme=radical&include_all_commits=true&count_private=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Khufos&layout=compact&theme=radical" />

</div>

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Khufos-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/seu-usuario-aqui)  
[![Twitter](https://img.shields.io/badge/Twitter-@Khufos__-1DA1F2?style=flat-square&logo=twitter)](https://twitter.com/Khufos__)  
[![Portfolio](https://img.shields.io/badge/Portfolio-khufos.dev-000?style=flat-square&logo=vercel)](https://khufos.dev)

</div>

---

## 💬 Fun Fact

> "Code is like humor. When you have to explain it, it’s bad." – Cory House

---

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=111&height=120&section=footer"/>
