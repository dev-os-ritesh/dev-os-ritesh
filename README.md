<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0d09,50:3a2a00,100:ffb000&height=200&section=header&text=Ritesh&fontSize=58&fontColor=e8e6df&animation=fadeIn&fontAlignY=36&desc=MERN%20Stack%20Developer%20%E2%80%94%20Open%20to%20Internships&descAlignY=58&descSize=17" />

<img src="https://readme-typing-svg.demolab.com/?lines=I+ship+working+products%2C+not+tutorial+clones;Full-stack+MERN+%7C+security-minded+%7C+detail-obsessed;Currently+building%3A+a+secure+QR+event+platform;center=true&font=Fira+Code&width=600&height=40&color=ffb000&vCenter=true&size=19&pause=1300" />

</div>

<br>

## 🧑‍💻 About Me

I'm a full-stack developer who builds things end-to-end — schema to UI, auth to edge cases. I don't just make things that work on the happy path; I think about what breaks, who abuses it, and what happens when 500 people scan a QR code at once.

I'm currently in my penultimate year of a **B.E. in Information Technology at D.Y. Patil College of Engineering, Akurdi, Pune** (SGPA 8.51/10), based in Pune, India. Alongside coursework, I build full production-style systems on my own — most recently a security-conscious event platform and an AI-integrated blog platform — because I'd rather learn architecture by shipping than by reading about it.

What I actually care about:
- 🔍 Getting the *details* right — error states, edge cases, what happens when things go wrong
- 🏗️ Understanding systems end-to-end, not just the part I'm assigned
- 📈 Shipping real, usable things over perfect, unfinished ones

```bash
$ whoami
> name: Ritesh Ranbaware
> role: Full-Stack MERN Developer
> based in: Pune, Maharashtra, India
> currently: B.E. Information Technology, D.Y. Patil College of Engineering (2023–2027)
> shipped: a secure dual-portal QR event check-in platform
> shipped: QuickBlog — an AI-powered MERN blog platform (Groq LLaMA integration)
> learning: TypeScript, System Design
> status: open to internship opportunities — full-stack / backend / frontend
```

<div align="center">

> *"Talk is cheap. Show me the code."*
> — Linus Torvalds

</div>

---

## 🏆 Flagship Build

<table>
<tr>
<td>

### 🎟️ QR-Based Event Check-In Platform
**A full-stack, dual-portal system built solo — this is my strongest technical work.**

Most "QR check-in" projects stop at generating a code and scanning it. Mine goes further, because the interesting engineering is in what happens *after* the scan:

- 🔐 **JWT-authenticated, role-based REST API** with Mongoose schemas and bcryptjs password hashing
- 🎫 **UUID-encoded QR tickets** — auto-generated as PDFs (PDFKit) and delivered via Nodemailer
- ⚔️ **Fraud & abuse prevention** — in-browser camera QR scanning enforcing duplicate-entry and cross-event fraud checks
- 📊 **Live organizer analytics dashboard** — real-time check-in data as scans happen

**Stack:** React 19, Vite, MongoDB · Node.js, Express, JWT, PDFKit, Nodemailer

<a href="https://github.com/dev-os-ritesh/QR-based-Event-Check-in-Platform"><img src="https://img.shields.io/badge/View%20Source-ffb000?style=for-the-badge&logoColor=black" /></a>

</td>
</tr>
<tr>
<td>

### 🤖 QuickBlog — AI-Powered MERN Blog Platform
**A full-stack blog platform with an LLM actually wired into the workflow, not bolted on.**

- ✍️ **Groq LLaMA 3.3 70B integration** — auto-generates blog drafts from topic prompts, paired with a Quill rich-text editor
- 🔑 JWT-secured admin panel with a live dashboard of blog, draft, and comment counts
- 🖼️ **ImageKit CDN** with automatic WebP compression for image delivery, Multer-based uploads
- 🚀 Deployed as separate client/server Vercel projects with production cross-origin configuration

**Stack:** React 19, React Router v7, Tailwind CSS · Node.js, Express 5, MongoDB Atlas · Groq LLaMA API, ImageKit

</td>
</tr>
</table>

<details>
<summary><b>🔍 Also worth a look</b></summary>
<br>

**CodeClarity** — an AI-powered VS Code extension giving inline code explanations and error breakdowns, built to support multiple AI providers (Gemini, OpenAI, local models) instead of locking to one vendor.
[→ View repo](https://github.com/dev-os-ritesh/CodeClarity)

**Investo** — a full-stack trade-simulation platform exploring real-world trading-system architecture across three integrated services: authentication, portfolio management, and order execution.
[→ View repo](https://github.com/dev-os-ritesh/Investo)

</details>

---

## 🏅 Achievements

- 🏆 **Smart India Hackathon 2025** — qualified the internal round, presenting a scalable software solution to a national panel of 10+ industry experts, advancing from 100+ competing teams
- 📊 **McKinsey & Company Forward Learner 2026** — completed structured modules on problem decomposition, data-driven communication, and leadership frameworks
- 🎯 **JEE Advanced 2022** — All India Rank 6313 among 180,000+ candidates (top 0.3%)
- 🥈 **International Mathematics Olympiad 2020** — State-Level Qualifier

---

## 🛠️ Tech Stack

<div align="center">

**Core — comfortable & production-ready**
<br>
<img src="https://skillicons.dev/icons?i=mongodb,express,react,nodejs,js,tailwind" />

<br><br>

**Languages & CS Fundamentals**
<br>
<img src="https://skillicons.dev/icons?i=cpp,java,python" />
<br>
<sub>DSA: Arrays, Hash Tables, Binary Search, Trees, Graphs, DP, Divide & Conquer · OOP · DBMS · OS · System Design</sub>

<br><br>

**Auth, Cloud & AI Integrations**
<br>
<sub>JWT · bcryptjs · Role-Based Access Control · Groq LLaMA API · ImageKit CDN · PDFKit · Nodemailer · TanStack Query</sub>

<br><br>

**Tools**
<br>
<img src="https://skillicons.dev/icons?i=git,github,postman,vscode,vite,vercel" />

<br><br>

**Currently leveling up**
<br>
<img src="https://skillicons.dev/icons?i=typescript" />

</div>

---

## 🧭 How I Build

Not a stats widget — how I actually work when I start a project:

```
01  Break the idea into real user roles first
    (e.g. "attendee" vs "organizer" — not just "user")

02  Design the failure states before the happy path
    what happens on a duplicate scan, a bad token, a network drop?

03  Build the boring backend logic properly
    auth, validation, atomic operations — before touching UI polish

04  Ship it, then go back and harden it
    rate limiting, edge-case testing, cleanup
```

<div align="center">
<i>This is the actual process behind the QR platform above — not a template answer.</i>
</div>

---

## 📚 Right Now

- 🔨 Building: the QR check-in platform's analytics dashboard
- 📖 Learning: TypeScript, and how to structure larger backend codebases
- 🎯 Looking for: an internship where I can work on real systems, not just tickets

---

## 📫 Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/Ritesh-Ranbaware" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:riteshranbaware@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://leetcode.com/u/Ritesh_Ranbaware" target="_blank"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=dev-os-ritesh&label=Profile%20Views&color=ffb000&style=for-the-badge" />

</div>
