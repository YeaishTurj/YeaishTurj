# Yeaish Jahan Turj

### Software Engineer | Backend & Full-Stack Development | Applied AI

Computer Science & Engineering student at **CUET** (Expected 2027), building production-oriented web applications, scalable backend microservices, and applied AI/LLM solutions. Experienced across **Next.js, Node.js, FastAPI, TypeScript, PostgreSQL, and Redis**.

[Portfolio](https://yjturj.netlify.app) · [LinkedIn](https://linkedin.com/in/yj-turj) · [GitHub](https://github.com/YeaishTurj) · [Email](mailto:yjturj12104@gmail.com)

---

## 🛠️ Technical Skills

### 🚀 Programming Languages
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![SQL](https://img.shields.io/badge/sql-%2300758F.svg?style=for-the-badge&logo=mysql&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)

### 🛠️ Frameworks & Backend
![Next.js](https://img.shields.io/badge/next.js-%23000000.svg?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Node.js](https://img.shields.io/badge/node.js-%23339933.svg?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%3338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)

### 🗄️ Databases & Caching
![PostgreSQL](https://img.shields.io/badge/postgresql-%33336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/mongodb-%2347A248.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)

### 📦 DevOps & Tools
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/postman-%23FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📌 Featured Projects

### [CareerGap — AI-Assisted Skill Gap Analyzer with Human Review](https://github.com/CUET-Synesis-IT/careergap)
*Modular monolith built during Academic Industrial Attachment at Synesis IT PLC. (CUET CSE-402)*
- **Problem:** Automated resume screeners often produce inaccurate or overly optimistic match scores when relying entirely on generative AI.
- **Engineering:** 
  - Designed a hybrid architecture: constrained Google Gemini API strictly to parsing technical skills from PDF resumes, while computing fit scores deterministically against weighted skill hierarchies (High, Medium, Bonus).
  - Implemented distributed locking with Redis (`SET NX PX`) to safely handle concurrent task claiming in human reviewer queues and eliminate race conditions.
  - Architected as a modular monolith with clean separation between the Next.js client, Express REST API, Prisma ORM, and PostgreSQL.
- **Stack:** Next.js 16, React 19, TypeScript, Node.js, Express.js, PostgreSQL 16, Prisma, Redis, Gemini API, Docker
- **Links:** [Repository](https://github.com/CUET-Synesis-IT/careergap)

### [SpendWise — Personal Finance & Budgeting Dashboard](https://github.com/YeaishTurj/spendwise)
*Full-stack financial management platform with analytics and reporting*
- **Problem:** Existing budgeting apps are either bloated or lack granular multi-currency tracking and clean export capabilities.
- **Engineering:** 
  - Built an interactive analytics dashboard supporting recurring transactions, category budgeting thresholds, and CSV report export.
  - Optimized database operations using Prisma ORM with Supabase PostgreSQL, leveraging server components for fast initial page loads and secure session authentication.
- **Stack:** Next.js, TypeScript, PostgreSQL, Prisma, Supabase, Tailwind CSS
- **Links:** [Repository](https://github.com/YeaishTurj/spendwise)

### [ClaimPoint — Smart Lost & Found Campus Platform](https://github.com/YeaishTurj/claimpoint-smart-lost-found)
*Campus item tracking system with automated similarity matching*
- **Problem:** Campus lost-and-found systems suffer from duplicated reports and slow manual reconciliation.
- **Engineering:** 
  - Implemented role-based access control (RBAC), multi-state status transitions (Reported, Claimed, Verified, Returned), and RESTful API endpoints.
  - Integrated embedding-based similarity matching using Python to automatically flag potential pairings between lost and found item reports.
  - Fully containerized backend and database services using Docker Compose for reproducible local and server setups.
- **Stack:** React, Node.js, Express.js, PostgreSQL, Python ML, Docker
- **Links:** [Repository](https://github.com/YeaishTurj/claimpoint-smart-lost-found)

### [CUET Trade Portal — Student Marketplace Platform](https://github.com/YeaishTurj/CUET-Trade-Lost-Found-Portal)
*Peer-to-peer campus marketplace with bidding and product verification*
- **Problem:** Students lack a trusted, dedicated campus channel for buying, selling, and bidding on textbooks, hardware, and essentials.
- **Engineering:** Built RESTful APIs with Express and MongoDB, integrated JWT authentication with role authorization, Cloudinary media uploads, and real-time product search with bidding capabilities.
- **Stack:** React, Redux, Node.js, Express.js, MongoDB, Tailwind CSS, Cloudinary
- **Links:** [Repository](https://github.com/YeaishTurj/CUET-Trade-Lost-Found-Portal)

---

## 💼 Professional Experience

#### **Siliconx Softwares** — *Full Stack Developer (Next.js & Node.js)*
*March 2026 – Present | Stratford, New Jersey, USA (Remote)*
- Worked on production full-stack web applications using Next.js, React, Node.js, and TypeScript.
- Built RESTful APIs, JWT authentication mechanisms, and relational database integrations.
- Contributed to R&D for AI-powered SaaS products and client deliverables.
*(Previously Frontend Developer, Feb 2026 – Mar 2026)*

#### **TechOptions** — *AI Research & Engineering Intern*
*June 2026 – Present | Dhaka, Bangladesh (Remote)*
- Contribute to **BanglaLLM** research, including bilingual (Bangla-English) dataset curation, prompt engineering, and evaluation benchmarks.
- Worked on backend microservices and catalog search APIs using **FastAPI** and **PostgreSQL**.

#### **Synesis IT PLC.** — *Software Engineering Intern (Industrial Attachment)*
*September 2026 (1 Month) | Dhaka, Bangladesh*
- Completed academic industrial attachment as part of the CUET CSE-402 curriculum.
- Worked on **CareerGap**, developing resume extraction with Gemini API, deterministic weighted matching algorithms, and Redis distributed task locking for human reviewers.

---

## 📄 Research & Publications

- **“An Explainable Photovoltaic Power Output Prediction Model Using LightGBM, RFE, Geospatial Dataset, and SHAP”**  
  *Authors:* Al Shahriar Hossain, **Yeaish Jahan Turj**, Kahakashan Ashraf, Mahfuzulhoq Chowdhury  
  *Venue:* **IEEE ICCPCT 2026** (9th International Conference on Circuit, Power & Computing Technologies), August 2026.  
  *Highlights:* National-scale PVOUT prediction using LightGBM on multi-source geospatial and irradiance data ($R^2 = 96.98\%$, $MAE = 4.89$, $RMSE = 7.62$).  
  *Link:* [IEEE Xplore (DOI: 10.1109/ICCPCT70290.2026.11654848)](https://doi.org/10.1109/ICCPCT70290.2026.11654848)

---

## 🏅 Competitive Programming

Solved **1500+ algorithmic problems** across major online judges:

| Platform | Profile | Max / Contest Rating | Problems Solved |
| :--- | :--- | :--- | :--- |
| **Codeforces** | [Yeaish_Turj](https://codeforces.com/profile/Yeaish_Turj) | 1395 (Pupil) | 750+ |
| **LeetCode** | [Yeaish_Turj](https://leetcode.com/u/Yeaish_Turj) | 1772 (Top ~10%) | 750+ |
| **CodeChef** | [yeaish_turj](https://codechef.com/users/yeaish_turj) | 1632 (3★) | 200+ |
| **AtCoder** | [Yeaish_Turj](https://atcoder.jp/users/Yeaish_Turj) | 470 | 100+ |
| **CSES** | [YeaishTurj](https://cses.fi/user/172887) | Problem Set Complete | 50+ |

**Contest Achievements & Hackathons:**
- **3rd Place** — ASRRO ROBOCODER 2.0 Programming Contest @ CUET (2024)
- **2nd Place** — Group Project Competition, Mysoft Heaven Workshop @ CUET
- **Top 50 Finalist** — Micro-Ops Hackathon, CUET CSE Fest 2025 (*Team AI_WILL_REPLACE_US*)
- **Participant** — Datathon, CUET CSE Fest 2025 (*Team Alpha4*)

---

## 🎓 Education & Campus Leadership

### Education
- **Chittagong University of Engineering & Technology (CUET)**  
  *B.Sc. in Computer Science & Engineering* | 2023 – Expected 2027
- **Notre Dame College, Dhaka**  
  *Higher Secondary Certificate (HSC), Science* | 2019 – 2021

### Leadership & Involvements
- **IEEE Computer Society CUET Student Branch Chapter** — General Secretary, Machine Learning Wing (Aug 2026 – Present)
- **CUET Computer Club** — Joint General Secretary (Aug 2026 – Present) | *Sub-Executive Member (Management Team, CodeStorm 1.0 IUPC 2024)*
- **Notredamian Association of CUET (NDAC)** — Web Development Secretary (Sep 2026 – Present)

### Certifications & Training
- **C#.NET & Full-Stack Development (80 Hours)** — IICT, CUET & EDGE Project, Bangladesh Computer Council (BCC), 2026
- **Basic Programming with Python (42 Hours)** — IICT, CUET & EDGE Project, Bangladesh Computer Council (BCC), 2026
- **Generative AI & LLMs in Cybersecurity & Politics** — Bangladesh Computer Society (BCS International Lecture Series-03), 2026

---

## 🌐 Connect With Me

<a href="https://linkedin.com/in/yj-turj">
  <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://yjturj.netlify.app">
  <img src="https://img.shields.io/badge/Portfolio-FF6B6B?style=for-the-badge&logo=web&logoColor=white" alt="Portfolio"/>
</a>
<a href="mailto:yjturj12104@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
</a>
<a href="https://github.com/YeaishTurj">
  <img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://wa.me/+8801537151211">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
</a>
