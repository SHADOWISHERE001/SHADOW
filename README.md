(async()=>{
const resume = `# 👋 Hi, I'm YOUR NAME
**Full Stack Developer** • YOUR CITY • [your.email@example.com](mailto:your.email@example.com)

[![GitHub followers](https://img.shields.io/github/followers/YOURUSERNAME?label=Followers)](https://github.com/YOURUSERNAME)
[![Stars](https://img.shields.io/github/stars/YOURUSERNAME?label=Stars)](https://github.com/YOURUSERNAME?tab=repositories)

## 🚀 About Me
Passionate developer with 3+ years building scalable web apps. Love React, Node.js, and cloud architecture.

## 🛠️ Skills
| Frontend | Backend | DevOps | Database |
|----------|---------|--------|----------|
| ![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat&logo=typescript) | ![Node.js](https://img.shields.io/badge/-Node.js-43853D?style=flat&logo=node.js) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python) | ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker) ![AWS](https://img.shields.io/badge/-AWS-FF9900?style=flat&logo=amazon-aws) | ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql) |

## 💼 Experience
### Company XYZ • Full Stack Developer (2022-Present)
- Built 5+ production apps serving 10K+ users/month
- Reduced API response time 60% with caching
- Led migration to microservices architecture

## 🔥 Projects
[![Project 1](https://img.shields.io/badge/-E--Commerce-61DAFB?style=flat&logo=react)](https://github.com/YOURUSERNAME/project1) • React + Node • 500⭐

## 📚 Education
**BS Computer Science** • University Name • 2022

---
⭐ Star this repo & follow me for more!
`;
console.log('%c📄 RESUME READY! Copy the Markdown below 👇', 'color:#0e9f6e;font-size:20px;font-weight:bold');
console.log(resume);
navigator.clipboard.writeText(resume).then(()=>console.log('%c✅ Copied to clipboard!', 'color:#10b981;font-size:16px'));
})();
