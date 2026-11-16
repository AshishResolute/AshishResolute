<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Ashish%20Gourh&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Developer%20%7C%20Node.js%20%C2%B7%20TypeScript%20%C2%B7%20PostgreSQL&descAlignY=58&descSize=16" width="100%"/>

  <p>
    <a href="https://portfolio-seven-theta-gr81z8gaqt.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-A78BFA?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    <a href="https://www.linkedin.com/in/ashishgourh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
    <a href="mailto:ashishresolute@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
    <a href="https://leetcode.com/AshishResolute"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" /></a>
  </p>
</div>

## About

Backend developer in Bengaluru. I'm a Mechanical Engineering graduate (B.Tech, UVCE) who taught myself to build backends.

I focus on the parts of a backend that break under real use: **auth flows, caching, background jobs, rate limiting, and correctness under concurrency.**

**Open to backend and full-stack roles at product companies.**

## Projects

### [SocialBuzz](https://github.com/AshishResolute/socialBuzz)
A social media backend built for reliability and performance.

- JWT auth with **refresh token rotation**, reuse detection, and session revocation
- Redis cache-aside took feed latency from **170ms to 5ms**
- BullMQ for fan-out notifications, plus cursor-based pagination
- **81.57% test coverage** (49 tests, Jest + Supertest)
- TypeScript throughout, with Docker Compose and GitHub Actions CI

`TypeScript` `Node.js` `PostgreSQL` `Redis` `BullMQ` `Docker`

### [BankAPI](https://github.com/AshishResolute/bankapi)
A banking-style REST API where correctness comes before speed.

- PostgreSQL **row-level locking** for safe concurrent transactions
- Rate limiting with Redis and Lua scripts (Upstash)
- JWT refresh token rotation
- 70%+ test coverage
- [Live Swagger docs](https://github.com/AshishResolute/bankapi)

`Node.js` `PostgreSQL` `Redis` `JWT` `Swagger`

### [Job Application Tracker](https://github.com/AshishResolute/tracker)
My first end-to-end project: a React frontend with a Node/TypeScript backend, using Prisma and PostgreSQL. Frontend on Vercel, backend on Render.

`React` `TypeScript` `Express` `Prisma` `PostgreSQL`

## Currently working on

TypeScript depth, Node.js core modules (streams, `fs`, events), DSA, and React state management.

> Build it, break it, understand why it broke, ship the better version.

## Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,ts,js,postgres,mysql,redis,prisma,docker,githubactions,git,github&theme=dark" />
</p>

**Auth and security:** JWT, refresh token rotation, RBAC, bcrypt, OAuth 2.0
**Testing:** Jest, Supertest, Vitest
**Infra and docs:** Docker, GitHub Actions, Swagger
