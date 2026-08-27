<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=22C55E&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Ashish;I+build+backend+systems+that+stay+correct+under+load;Node.js+%C2%B7+PostgreSQL+%C2%B7+Redis" alt="Typing SVG" />
</p>

<p align="center">
  Self-taught backend developer · Final-year B.Tech @ UVCE Bengaluru<br/>
  14 months building REST APIs with real auth, real caching, and tests that catch real bugs.
</p>

<p align="center">
  <a href="https://portfolio-seven-theta-gr81z8gaqt.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-22C55E?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/ashishgourh">
    <img src="https://img.shields.io/badge/LinkedIn-22C55E?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:ashishresolute@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-22C55E?style=flat-square&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://leetcode.com/AshishResolute">
    <img src="https://img.shields.io/badge/LeetCode-353%2B-22C55E?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Backend%20%2F%20Full--Stack%20Roles-22C55E?style=flat-square" alt="Open to work"/>
</p>

---

### About

I got into backend because I like systems that don't fall over under load — auth that doesn't leak, caches that actually hit, transactions that don't race. Most of what I build is a REST API with JWT + refresh rotation, Postgres, Redis, and enough tests that I trust a deploy.

Currently applying for **Backend / Full-Stack roles** — Bengaluru or remote.

---

### Featured builds

**[SocialBuzz](https://github.com/AshishResolute/socialBuzz)** — social media backend (follow graph, feed, notifications)
- Redis cache-aside dropped feed latency **170ms → 5ms**
- JWT refresh rotation with reuse detection (self-referencing FK token chain — theft revokes the whole session family)
- BullMQ + Redis for async notification fan-out and email delivery
- 81% coverage, 49 tests, GitHub Actions CI on every push

<p>
<img src="https://img.shields.io/badge/Node.js-22C55E?style=flat-square&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-22C55E?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-22C55E?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-22C55E?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/BullMQ-22C55E?style=flat-square"/>
<img src="https://img.shields.io/badge/Docker-22C55E?style=flat-square&logo=docker&logoColor=white"/>
</p>

**[BankAPI](https://github.com/AshishResolute/bankapi)** — banking REST API · [live docs](https://bankapi-1-5iag.onrender.com/api-docs/)
- Row-level locking on transaction records — no concurrent balance corruption
- Redis + Lua scripts for atomic, race-condition-safe rate limiting (Upstash)
- JWT refresh rotation with HTTP-only cookies, 70%+ test coverage

<p>
<img src="https://img.shields.io/badge/Node.js-22C55E?style=flat-square&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-22C55E?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-22C55E?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-22C55E?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Swagger-22C55E?style=flat-square&logo=swagger&logoColor=white"/>
</p>

**[Job Application Tracker](https://github.com/AshishResolute/tracker)** — full-stack CRUD app · [live](https://tracker-front-end-xi.vercel.app)
- React/Vite frontend + Express/TypeScript/Prisma API, deployed independently on Vercel + Render
- 6-state pipeline (Applied → Interview → Offer/Rejected/Ghosted) modeled in Postgres via Prisma
- Optimistic UI updates — every CRUD action reflects instantly, no reload

<p>
<img src="https://img.shields.io/badge/React-22C55E?style=flat-square&logo=react&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-22C55E?style=flat-square&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-22C55E?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-22C55E?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-22C55E?style=flat-square&logo=prisma&logoColor=white"/>
</p>

**[Finance API](https://github.com/AshishResolute/finance_backend)** — role-based ledger & analytics API
- RBAC across viewer / analyst / admin roles
- Dynamic SQL with field whitelisting — aggregate queries (SUM/CASE/GROUP BY) without injection risk

<p>
<img src="https://img.shields.io/badge/Node.js-22C55E?style=flat-square&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Express-22C55E?style=flat-square&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-22C55E?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT-22C55E?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
<img src="https://img.shields.io/badge/RBAC-22C55E?style=flat-square"/>
</p>

---

### Stack

| | |
|---|---|
| **Backend** | Node.js, Express, TypeScript |
| **Databases** | PostgreSQL, Redis, MySQL, MongoDB |
| **Auth & Security** | JWT, Refresh Token Rotation, RBAC, bcrypt |
| **Testing** | Jest, Supertest |
| **DevOps** | Docker, GitHub Actions, Render, Vercel |
| **Docs** | Swagger / OpenAPI |

---

<p align="center">
  <img src="https://github-readme-stats-eight-rho-81.vercel.app/api?username=AshishResolute&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github&cache_seconds=1800" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats-eight-rho-81.vercel.app/api/top-langs/?username=AshishResolute&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&cache_seconds=1800" alt="Top Languages" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AshishResolute&theme=tokyonight&hide_border=true&cache_seconds=1800" alt="GitHub Streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AshishResolute&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" />
</p>

---

### DSA

<p align="center">
  <a href="https://leetcode.com/AshishResolute">
    <img src="https://img.shields.io/badge/LeetCode-353%2B%20solved-22C55E?style=flat-square&logo=leetcode&logoColor=white"/>
  </a>
  <a href="https://www.geeksforgeeks.org/profile/ashishren9md">
    <img src="https://img.shields.io/badge/GFG-300%2B%20solved-22C55E?style=flat-square&logo=geeksforgeeks&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <b>Bengaluru / Remote</b> · <a href="mailto:ashishresolute@gmail.com">ashishresolute@gmail.com</a> · <a href="https://portfolio-seven-theta-gr81z8gaqt.vercel.app/">Portfolio →</a>
</p>
