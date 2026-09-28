from pathlib import Path

md = r'''# Junayed Hasan

> **CSE Student & Web Development Learner**

Passionate about **problem solving, web development, photography, chess, and mathematics.**

---

## 👋 Hello, I'm Junayed Hasan

I am currently studying **Computer Science and Engineering** and focusing on improving my web development skills. I enjoy learning by building real projects and solving programming problems.

My current focus is **React and Next.js**, while continuously improving my **JavaScript, TypeScript, problem solving, and software development fundamentals.**

---

## 🎓 Education

### Bachelor of Science in CSE

**Bangladesh University of Business & Technology (BUBT)**

Department of Computer Science & Engineering

---

## 🔗 Connect

- [GitHub](https://github.com/junayedhasan302)
- [LinkedIn](https://www.linkedin.com/in/junayet-hasan-jh/)
- [Twitter / X](https://x.com/junayed_jh)
- [Facebook](https://www.facebook.com/junayed.hasan.302/)
- [Instagram](https://www.instagram.com/jhjunayed/)
- [Quora](https://bn.quora.com/profile/Junayed-Hasan-108)
- [Chess.com](https://www.chess.com/member/jhjunayed)
- [LeetCode](https://leetcode.com/u/jhjunayed/)
- [Codeforces](https://codeforces.com/profile/mjunayed302)
- [Pexels](https://www.pexels.com/@junayed-hasan-2156679708/)

---

## 🛠️ Tech Stack

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [TypeScript](https://www.typescriptlang.org/docs/)
- [React](https://react.dev/)
- [Next.js](https://nextjs.org/docs)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [Git](https://git-scm.com/doc)

Click any technology to open its documentation.

---

## 👨‍💻 About Me

### A learner who loves to build.

I am currently studying Computer Science and Engineering and focusing on improving my web development skills. I enjoy learning by building real projects and solving programming problems.

My current focus is React and Next.js, while continuously improving my JavaScript, TypeScript, problem solving, and software development fundamentals.

---

## 🚀 Projects

### 1. JH DevStack

**Personal developer portfolio and web development showcase.**

**Tech:** React · JavaScript · CSS

🔗 [Live Project](https://jhdevstack.netlify.app/)

---

### 2. FitLog

**Workout management app for exploring exercises, saving workouts, and creating workout plans.**

**Tech:** Next.js · React · Tailwind CSS

🔗 [Live Project](https://jhfitlog.vercel.app/)

---

### 3. BPL Players Market

**Cricket player selection app with player cards, coin management, and selection logic.**

**Tech:** React · TypeScript · Tailwind CSS

🔗 [Live Project](https://playermarket.netlify.app/)

---

### 4. Hello World

**A simple web project created while learning and practicing frontend development.**

**Tech:** HTML · CSS · JavaScript

🔗 [Live Project](https://heyhelloworld.netlify.app/)

---

### 5. World Cup 2026

**A football World Cup 2026 themed web project with an interactive tournament experience.**

**Tech:** React · JavaScript · CSS

🔗 [Live Project](https://world-cup-2026-green-beta.vercel.app/)

---

### 6. Country Explorer

**Explore country information, flags, and visited countries using API data.**

**Tech:** React · TypeScript · API

🔗 [Live Project](https://heyhelloworld.netlify.app/)

---

## 📸 Beyond Code

### What I enjoy

| Interest | |
|---|---|
| 📸 | Street Photography |
| ♟️ | Chess |
| 🧮 | Mathematics |
| 💻 | Web Development |

---

## 📬 Let's Connect

### Have an idea or want to talk?

Feel free to reach out. I'm always interested in discussing **technology, projects, photography, or new ideas.**

📧 **Email:** [junayedhasan302@gmail.com](mailto:junayedhasan302@gmail.com)

[**Send me an Email**](mailto:junayedhasan302@gmail.com)

---

## 🌃 Design / Visual Theme

The original website uses a **cyberpunk / synthwave** visual style featuring:

- 🌌 Dark purple-black background
- 💙 Cyan neon highlights
- 💗 Magenta neon highlights
- ⚡ Animated lightning effects
- 🏙️ Cyberpunk city skyline
- 🚗 Moving neon cars
- 💡 Flickering street lights
- 🔲 Animated synthwave grid floor
- 🖱️ Cursor light trail
- 💥 Click ripple effects
- 🧊 Glassmorphism card
- 🎯 HUD-style profile image frame
- 🌀 3D card tilt interaction
- 📱 Responsive layout
- ♿ Reduced-motion support

> **Note:** Markdown can preserve the site's content, sections, links, and documentation, but CSS animations, cursor effects, 3D tilt, moving cars, lightning, and other interactive visual effects require HTML/CSS/JavaScript and cannot be reproduced by plain Markdown alone.
'''

path = Path("/mnt/data/junayed-portfolio.md")
path.write_text(md, encoding="utf-8")

print(f"Created: {path}")
