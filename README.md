from pathlib import Path

readme = r'''<div align="center">

<!-- Replace USERNAME with your GitHub username in the stats and contribution URLs below. -->

<a href="https://github.com/USERNAME">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rounded&height=210&section=header&text=Nam%20Khanh&fontSize=64&fontColor=58A6FF&fontAlignY=38&desc=BACKEND%20ENGINEER%20%7C%20JAVA%20%7C%20.NET%20%7C%20AI%2FRAG&descSize=17&descAlignY=62&animation=fadeIn&color=0:0D1117,50:161B22,100:1F6FEB" alt="Nam Khanh — Backend Engineer, Java, .NET, AI/RAG" />
</a>

<p>
  <a href="mailto:khanhsteve21@gmail.com"><img src="https://img.shields.io/badge/EMAIL-Contact%20me-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" /></a>
  <img src="https://img.shields.io/badge/LOCATION-Da%20Nang%2C%20Vietnam-0D1117?style=for-the-badge&logo=googlemaps&logoColor=58A6FF" alt="Da Nang, Vietnam" />
  <img src="https://img.shields.io/badge/FOCUS-Backend%20%2B%20AI-0D1117?style=for-the-badge&logo=github&logoColor=58A6FF" alt="Backend and AI" />
</p>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2600&pause=850&color=58A6FF&center=true&vCenter=true&width=700&height=45&lines=Designing+reliable+backend+systems;Building+RAG+%26+LLM-powered+features;Java+%2F+Spring+Boot+%7C+C%23+%2F+ASP.NET+Core;Clean+Architecture+%7C+Testing+%7C+CI%2FCD;Currently+building+NoteMind" alt="Animated introduction" />

<br/>

[About](#-about-me) · [Featured Projects](#-featured-projects) · [Tech Stack](#-tech-stack) · [Experience](#-experience) · [GitHub Activity](#-github-activity)

</div>

---

## 👨‍💻 About Me

I'm a Software Engineering graduate from **FPT University, Da Nang** (October 2026), focused on backend engineering and AI-powered applications.

- 🧱 **Backend:** Java, Spring Boot, C#, ASP.NET Core, REST APIs
- 🧠 **Applied AI:** RAG pipelines, embeddings, LLM integrations, source-grounded answers
- 🏗️ **Engineering:** Clean Architecture, CQRS, validation, security, automated testing
- 🚀 **Delivery:** Docker, GitHub Actions, database migrations, observability
- 🤝 **Teamwork:** Led a five-person Scrum capstone team using Jira and sprint planning

I enjoy turning complex requirements into maintainable services—with clear boundaries, secure data access, useful tests, and deployment workflows that can be repeated.

> **Engineering mindset:** ship useful features, measure what matters, and keep the system understandable.

## 🚧 Currently Building — NoteMind

**NoteMind is an AI knowledge workspace** that turns videos, audio, and documents into structured, source-grounded learning materials.

| Capability | What it does |
|---|---|
| 🎧 Media ingestion | Import media and process it through an asynchronous pipeline |
| 📝 Timestamped notes | Generate structured notes with claims linked to exact source timestamps |
| 🔎 Chat with sources | Retrieve relevant passages and answer with source context using RAG |
| 🧠 Learning tools | Generate mind maps and flashcards from source material |

**Progress**
- ✅ Email OTP sign-up with hashed codes and brute-force limits
- ✅ Workspace and folder management with tenant isolation
- ✅ Initial application shell
- 🛠️ Media ingestion: upload → queued job → transcription

**Architecture & stack**

`React + Vite` → `Java 21 / Spring Boot 3.5` → `PostgreSQL + pgvector`  
`Redis Streams` · `MinIO` · `Python worker (Whisper, bge-m3)` · `Docker Compose`  
`Spring Security (JWT)` · `Flyway` · `Testcontainers` · `ArchUnit`

<sub>Work in progress — repository link will be added when it is public.</sub>

## 🌟 Featured Projects

### 01 / OJT Hub — Internship Placement Platform
<sub><b>Capstone · Team Lead · 2026</b></sub>

A platform commissioned by FPT University Da Nang to manage internship placement across **students, employers, career-relations staff, and administrators**.

- 🔄 Two-stage applications: university CV screening before employer review
- 🗂️ Semester-based data separation and job-posting state transitions
- 🧱 Clean Architecture + CQRS with MediatR and FluentValidation
- 🤖 Gemini-assisted job description drafting, student–job matching, and PDF CV parsing
- 💬 Real-time chat and notifications with SignalR
- ⚙️ Hangfire background jobs, Redis caching, PostgreSQL, and Serilog
- 🚢 Docker Compose behind Caddy; GitHub Actions CI/CD; Prometheus metrics

**Stack:** `ASP.NET Core 8` · `React / TypeScript` · `PostgreSQL` · `Redis` · `SignalR` · `Hangfire` · `Gemini API` · `Docker` · `GitHub Actions`

<sub>Repository: add link when public.</sub>

### 02 / ExamBuddy — Online Exam Preparation
<sub><b>Academic Project</b></sub>

An exam-preparation app where teachers manage question banks and mock exams, while students take tests, track progress, and receive AI-generated explanations after each mock exam.

- 🧑‍🏫 Role-based workflows for teachers and students
- 📊 Practice tests and progress tracking
- 💡 AI-assisted explanations for learning from mistakes

**Stack:** `Spring Boot` · `Layered MVC` · `Firebase` · `Docker`

<sub>Repository: add link when public.</sub>

### 03 / RAG Research Chatbot — FPT Software
<sub><b>Software Engineering Intern · F1.JAS</b></sub>

Contributed to a document-research chatbot using retrieval-augmented generation.

- 📚 Built parts of a Python indexing pipeline for document chunking and embeddings
- 🔍 Stored vectors in Pinecone to retrieve relevant document passages
- 💬 Contributed to question-answering features and prompt refinement

**Stack:** `Python` · `OpenAI API` · `RAG` · `Embeddings` · `Pinecone`

## 🧰 Tech Stack

<div align="center">

### Backend & Languages
<img src="https://skillicons.dev/icons?i=java,spring,cs,dotnet,python,ts,js&perline=7&theme=dark" alt="Java, Spring, C sharp, .NET, Python, TypeScript, JavaScript" />

### Frontend
<img src="https://skillicons.dev/icons?i=react,vite,html,css&perline=7&theme=dark" alt="React, Vite, HTML, CSS" />

### Databases & Messaging
<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,firebase&perline=7&theme=dark" alt="PostgreSQL, MySQL, Redis, Firebase" />

### DevOps & Developer Tools
<img src="https://skillicons.dev/icons?i=docker,githubactions,linux,git,github,idea,vscode&perline=7&theme=dark" alt="Docker, GitHub Actions, Linux, Git, GitHub, IntelliJ IDEA, VS Code" />

</div>

<details>
<summary><b>More about my toolkit</b></summary>

- **Backend:** Spring Boot, ASP.NET Core, EF Core, Spring Security, REST APIs, MVC
- **Architecture:** Clean Architecture, CQRS, layered architecture, background jobs
- **AI / LLM:** RAG, embeddings, OpenAI API, Google Gemini API, prompt engineering, AI agents
- **Data:** PostgreSQL, pgvector, SQL Server, MySQL, Redis, Firebase, Pinecone
- **Quality:** JUnit, Mockito, Testcontainers, ArchUnit, FluentValidation
- **Infrastructure:** Docker Compose, Caddy, GitHub Actions, Prometheus, Serilog
- **Workflow:** Git, Jira, Scrum, sprint planning, code reviews

</details>

## 💼 Experience

### FPT Software — Intern
<sub>May 2025 – September 2025</sub>

**Software Engineering Intern — F1.JAS**
- Contributed to a RAG chatbot for document research using the OpenAI API.
- Worked on Python document indexing, chunking, embedding storage in Pinecone, Q&A, and prompt refinement.

**Data Engineering Intern**
- Supported data migration from Oracle to SQL Server.
- Used Informatica PowerCenter for ETL mappings and workflows.
- Validated migration results by reconciling row counts and sampling records.

## 📊 GitHub Activity

<!-- Replace USERNAME with your actual GitHub username. These cards use public third-party services and may occasionally be unavailable. -->

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&hide_border=true&rank_icon=github&theme=github_dark&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&hide_border=true&theme=github_dark&langs_count=8" alt="Top languages" />
  <br/>
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=USERNAME&bg_color=0d1117&color=58a6ff&line=1f6feb&point=79c0ff&area=true&hide_border=true" alt="Contribution activity graph" />
</div>

## 🎓 Certifications

- Artificial Intelligence: An Overview Specialization — 2026
- User Experience Research and Design Specialization — 2026
- Project Management Principles and Practices — 2025
- Software Development Lifecycle — 2024
- Computer Communications Specialization — 2024
- Web Design for Everybody: Basics of Web Development & Coding — 2023

## 🤝 Let's Connect

I'm open to **Backend Engineer / Software Engineer / Full-stack opportunities**, especially roles involving Java/Spring Boot, .NET, and AI-powered products.

<div align="center">

<a href="mailto:khanhsteve21@gmail.com">
  <img src="https://img.shields.io/badge/Let's%20talk-khanhsteve21%40gmail.com-1F6FEB?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Nam Khanh" />
</a>

<br/><br/>
<sub>Built with curiosity, clean code, and a little ☕.</sub>

</div>
'''
path = Path("/mnt/data/README_GitHub_Nam_Khanh.md")
path.write_text(readme, encoding="utf-8")
print(f"Created: {path}")
