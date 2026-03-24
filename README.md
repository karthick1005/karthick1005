<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Udhayakarthick%20Narayanan&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20AI%20%26%20Systems%20Builder&descAlignY=55&descAlign=50" width="100%" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Building+FAANG-Level+Production+Systems;LeetCode-Style+Online+Judge+%7C+40%2B+subs%2Fsec;Signal+Protocol+E2E+Encryption+%7C+X3DH+%2B+Double+Ratchet;AI-Powered+Dev+Tools+%7C+Gemini+2.5+Flash;Computer+Vision+%7C+YOLOv8+%2B+EasyOCR;Open+to+Exciting+Opportunities+%F0%9F%9A%80" alt="Typing SVG" /></a>

<br/>

[![GitHub followers](https://img.shields.io/github/followers/karthick1005?label=Followers&style=social)](https://github.com/karthick1005)
[![Profile Views](https://komarev.com/ghpvc/?username=karthick1005&color=58A6FF&style=flat-square&label=Profile+Views)](https://github.com/karthick1005)
[![Portfolio](https://img.shields.io/badge/Portfolio-udhayakarthick.vercel.app-58A6FF?style=flat-square&logo=vercel)](https://udhayakarthick.vercel.app/)
[![LeetCode](https://img.shields.io/badge/LeetCode-karthick2005-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/karthick2005/)

</div>

---

## 🧑‍💻 About Me

I'm **Udhayakarthick Narayanan**, a **Full-Stack Developer** who builds production-grade, FAANG-quality systems — from horizontally-scalable online judges with Docker container pools to fully end-to-end encrypted messaging apps that implement the real Signal Protocol.

- 🏗️ Built a **LeetCode-scale Online Judge** — pre-warmed Docker pools, RabbitMQ, Redis, 40+ submissions/sec
- 🔐 Implemented the full **Signal Protocol (X3DH + Double Ratchet)** — the same crypto WhatsApp uses
- 🤖 Integrating **LLMs (Google Gemini 2.5 Flash)** into interactive, browser-based developer tools
- 🎯 Strong focus on **system design**, **security best practices**, and **scalable architecture**
- 💡 Competitive programmer — solving DSA daily on [LeetCode](https://leetcode.com/u/karthick2005/)

---

## ⭐ FAANG-Level Flagship Projects

> These two projects demonstrate the depth of systems design, distributed architecture, and security engineering expected at top-tier companies.

---

### 🏆 LeetCode Clone — Full Online Judge System

> *"I didn't just clone the UI — I engineered the entire execution infrastructure from scratch."*

<table>
  <tr>
    <td width="55%" valign="top">

**A production-grade, horizontally scalable online judge** — the same class of system that powers LeetCode, HackerRank, and Codeforces.

**⚙️ Backend Infrastructure (The Hard Part)**
- **Pre-warmed Docker container pool** (10 containers/worker) — zero cold-start, instant execution
- **RabbitMQ job queue** — async submission processing with back-pressure management
- **Redis result cache** — < 1ms read latency, 1-hour TTL, binary cache for compiled languages
- **WebSocket real-time delivery** — live status updates pushed to client
- **Horizontal scaling** — stateless workers, linear throughput growth
- **Sandbox security** — network-isolated, memory/CPU-limited, non-root containers

**📊 Performance Benchmarks**

| Metric | Value |
|---|---|
| Throughput (1 worker) | 8–10 submissions/sec |
| Throughput (5 workers) | **40+ submissions/sec** |
| P95 Latency | **< 250 ms** |
| Compiled language speedup | 10–100× (binary cache) |

**🖥️ Frontend (IDE Experience)**
- Monaco Editor (VS Code engine) with TextMate grammar support
- Multi-language: Python, JavaScript, C++, Java
- Dockable IDE panel layout (Flexlayout-react)
- Auto-save via IndexedDB, Firebase Auth, full submission history

    </td>
    <td width="45%" valign="top">

**Tech Stack**

*Backend:*
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socket.io)

*Frontend:*
![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white)
![Monaco](https://img.shields.io/badge/Monaco_Editor-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Repositories:**
🔗 [Leetcode_Frontend](https://github.com/karthick1005/Leetcode_Frontend)
🔗 [Leetcode_backend](https://github.com/karthick1005/Leetcode_backend)

**What makes this FAANG-level:**
- ✅ Distributed job queue (RabbitMQ)
- ✅ Container orchestration (Docker pools)
- ✅ In-memory caching layer (Redis)
- ✅ Real-time WebSocket delivery
- ✅ Measured performance benchmarks
- ✅ Horizontal scaling design

    </td>
  </tr>
</table>

---

### 🔒 Signal Chat App — End-to-End Encrypted Messenger

> *"I implemented the same cryptographic protocol that powers WhatsApp and Signal — from scratch."*

<table>
  <tr>
    <td width="55%" valign="top">

**A production-ready, end-to-end encrypted messaging app** that implements the complete **Signal Protocol** — the gold standard for secure communications used by Signal, WhatsApp, and Google Messages.

**🔐 Cryptographic Architecture (The Hard Part)**
- **X3DH (Extended Triple Diffie-Hellman)** — secure session establishment without a shared secret ever touching the server
- **Double Ratchet Algorithm** — forward secrecy + break-in recovery on every single message
- **Sender Key Scheme (Groups)** — WhatsApp-style distributed group encryption
- **No plaintext ever leaves the device** — all encryption is client-side only
- Key material stored exclusively in IndexedDB — never serialized to a server

**📱 App Features**
- Group chats with WhatsApp-style distributed metadata (no central DB)
- Video calling via ZegoCloud
- PWA — installable, works offline
- IndexedDB local-first architecture with background sync
- Optimistic UI updates + Socket.IO real-time transport

    </td>
    <td width="45%" valign="top">

**Tech Stack**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Signal Protocol](https://img.shields.io/badge/Signal_Protocol-3A76F0?style=flat-square&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io)
![Zustand](https://img.shields.io/badge/Zustand-FF4154?style=flat-square)
![IndexedDB](https://img.shields.io/badge/IndexedDB-FF6B35?style=flat-square)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Repository:**
🔗 [signal-chat-app](https://github.com/karthick1005/signal-chat-app)

**What makes this FAANG-level:**
- ✅ Full Signal Protocol (X3DH + Double Ratchet)
- ✅ Zero-knowledge server architecture
- ✅ Local-first / offline-first PWA
- ✅ Cryptographic forward secrecy
- ✅ Real-time + async hybrid architecture
- ✅ Group key distribution protocol

    </td>
  </tr>
</table>

---

## 🚀 More Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://github.com/karthick1005/alogvis">AlgoVis — AI Algorithm Visualizer</a></h3>
      <p>Paste code → <strong>Google Gemini 2.5 Flash</strong> generates a full step-by-step execution trace. Animated call stack, recursion tree, variable state panel, and time/space complexity analysis — all in the browser.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js_15-000?style=flat-square&logo=next.js" />
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini_2.5_Flash-4285F4?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/Firebase_Genkit-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🎫 <a href="https://github.com/karthick1005/Online-complaint-Resolution">Online Complaint Resolution</a></h3>
      <p>Enterprise complaint management with <strong>RBAC</strong>, <strong>SLA tracking</strong>, real-time WebSocket notifications, automated cron escalation, and an analytics dashboard. Secured with JWT, rate limiting, and Helmet.</p>
      <p>
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Prisma-3982CE?style=flat-square&logo=prisma&logoColor=white" />
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🚗 <a href="https://github.com/karthick1005/License-Plate-Detector">License Plate Detector</a></h3>
      <p>Computer vision pipeline: two <strong>YOLOv8</strong> models (vehicle + plate), <strong>EasyOCR</strong>, and <strong>SORT</strong> multi-object tracker — reads Indian license plates from live webcam or video with Firebase cloud persistence.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/YOLOv8-00CFFF?style=flat-square" />
        <img src="https://img.shields.io/badge/EasyOCR-FF4B4B?style=flat-square" />
        <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔬 <a href="https://github.com/karthick1005/code-complexity-analyzer">Code Complexity Analyzer</a></h3>
      <p>Chrome Extension (Manifest V3) — auto-extracts code from <strong>LeetCode</strong> &amp; <strong>HackerRank</strong> editors and returns instant time &amp; space complexity. Zero data stored, clean popup UI.</p>
      <p>
        <img src="https://img.shields.io/badge/Chrome_MV3-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

### 🌐 Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

### ⚙️ Backend & Infrastructure
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=prisma&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### 🤖 AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Firebase Genkit](https://img.shields.io/badge/Firebase_Genkit-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00CFFF?style=for-the-badge&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white)

### ☁️ Cloud & DevOps
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

---

## 📊 GitHub & LeetCode Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=karthick1005&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=karthick1005&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&langs_count=8" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=karthick1005&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58A6FF&fire=FF6B35&currStreakLabel=58A6FF" />

<br/><br/>

<a href="https://leetcode.com/u/karthick2005/">
  <img src="https://leetcard.jacoblin.cool/karthick2005?theme=dark&font=Fira%20Code&ext=heatmap&border=0&radius=10" alt="LeetCode Stats" />
</a>

</div>

---

## 🏆 Engineering Highlights

```
⭐  FAANG-Level: Online Judge   →  Docker pools, RabbitMQ, Redis, 40+ subs/sec, <250ms P95
⭐  FAANG-Level: Signal Clone   →  X3DH + Double Ratchet, zero-knowledge server, local-first PWA
✅  AI Integration              →  Gemini 2.5 Flash, Firebase Genkit, Zod schema validation
✅  Distributed Systems         →  Message queues, container orchestration, WebSocket push
✅  Security Engineering        →  E2E encryption, RBAC, SLA, rate-limiting, JWT, Helmet
✅  Computer Vision             →  YOLOv8 × 2, EasyOCR, SORT multi-object tracker, OpenCV
✅  Developer Tooling           →  Chrome Extension MV3, Monaco Editor, AlgoVis AI debugger
```

---

## 📫 Get In Touch

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-udhayakarthick.vercel.app-58A6FF?style=for-the-badge)](https://udhayakarthick.vercel.app/)
[![LeetCode](https://img.shields.io/badge/LeetCode-karthick2005-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/karthick2005/)
[![GitHub](https://img.shields.io/badge/GitHub-karthick1005-181717?style=for-the-badge&logo=github)](https://github.com/karthick1005)

*Open to Full-Stack, Backend, or AI-focused roles — let's build something great together!*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%" />
