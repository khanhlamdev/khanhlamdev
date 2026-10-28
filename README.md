<div align="center">

<img src="assets/hero.svg" width="100%" alt="Nam Khanh, Backend Software Engineer: Java, Spring Boot, .NET, RAG. A red sun behind a torii gate over moving waves, with falling cherry blossoms.">

<img src="https://readme-typing-svg.demolab.com?font=Noto+Serif+JP&weight=600&size=22&duration=3000&pause=1400&color=D9412B&center=true&vCenter=true&width=620&height=44&lines=%E3%83%90%E3%83%83%E3%82%AF%E3%82%A8%E3%83%B3%E3%83%89%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2+%E3%83%BB+Java+%E3%83%BB+.NET;RAG%E3%83%BBLLM+%E6%A9%9F%E8%83%BD%E3%82%92%E9%96%8B%E7%99%BA%E4%B8%AD;%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%A2%E3%83%BC%E3%82%AD%E3%83%86%E3%82%AF%E3%83%81%E3%83%A3+%E3%83%BB+CQRS;NoteMind+%E3%82%92%E5%88%B6%E4%BD%9C%E4%B8%AD" alt="Backend engineer (Java, .NET). Building RAG and LLM features. Clean Architecture and CQRS. Currently building NoteMind.">

<a href="mailto:khanhsteve21@gmail.com"><img alt="Email: khanhsteve21@gmail.com" src="https://img.shields.io/badge/Email-khanhsteve21%40gmail.com-D9412B?style=flat-square&logo=gmail&logoColor=white"></a>
<!-- TODO: LinkedIn. Replace YOUR-LINKEDIN in the next line, then remove the comment markers around it. -->
<!-- <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img alt="LinkedIn profile" src="https://img.shields.io/badge/LinkedIn-Nam%20Khanh-D9412B?style=flat-square&logo=linkedin&logoColor=white"></a> -->

</div>

<img src="assets/h-about.svg" alt="About me">

Software Engineering graduate from FPT University Da Nang (October 2026). I work mostly on the backend, in Java/Spring Boot and C#/ASP.NET Core, with React on the front. My internship at FPT Software gave me hands-on experience with RAG and LLMs, and on my capstone I led a five-person Scrum team. I care about clean architecture, security, and code that is documented and tested.

<img src="assets/h-building.svg" alt="Currently building">

### NoteMind

An AI knowledge workspace. Import a YouTube video, audio or a document, and NoteMind transcribes it and writes a structured note in which **every claim cites the exact timestamp it came from**. On top of that note it adds mind maps, chat with your sources (RAG) and flashcards.

- **Done so far:** sign-up with email OTP verification (hashed codes, brute-force limits), workspace and folder management with tenant isolation, app shell UI
- **In progress:** media ingestion pipeline (upload → job queue → transcription)

<sub><b>Stack:</b> Java 21 · Spring Boot 3.5 · Spring Security (JWT) · PostgreSQL + pgvector · Flyway · Redis Streams · MinIO · React + Vite · Python worker (Whisper, bge-m3 embeddings) · Docker Compose · Testcontainers · ArchUnit</sub>

<sub><i>Work in progress. Repo coming soon.</i></sub>
<!-- TODO: link to the NoteMind repo once it is public -->

<img src="assets/h-projects.svg" alt="Featured projects">

### OJT Hub: internship placement platform
<sub>Capstone · Team leader · 2026</sub>
<!-- TODO: link to the OJT Hub repo if it is public -->

Commissioned by FPT University Da Nang to run the full internship placement cycle for four roles: students, employers, university career-relations staff and admins. I led the five-person Scrum team (Jira, sprint planning, feature-folder codebase).

- **Two-stage applications:** the university screens each CV before releasing it to the employer; job postings follow a state machine; data is isolated per semester
- **Architecture:** Clean Architecture + CQRS (MediatR, FluentValidation), Hangfire jobs, Redis cache and SignalR backplane, realtime chat and notifications over SignalR
- **AI:** Google Gemini drafts job descriptions and scores student–job matches; PDF CV parsing
- **Delivery:** PostgreSQL schema design, Docker Compose behind Caddy, GitHub Actions CI/CD, Serilog, Prometheus

<sub><b>Stack:</b> ASP.NET Core 8 · React (TypeScript) · PostgreSQL · Redis · SignalR · Hangfire · Google Gemini · Docker · GitHub Actions</sub>

### ExamBuddy: online exam preparation
<sub>Academic project</sub>
[View repo](https://github.com/khanhlamdev/Exambuddy)

Teachers build question banks and mock exams; students take tests, track their progress and get AI explanations of the answers after each mock test. Role-based access for teachers and students.

<sub><b>Stack:</b> Spring Boot (layered MVC) · Firebase · Docker</sub>

<img src="assets/h-experience.svg" alt="Experience">

**FPT Software** · Intern · May 2025 – Sep 2025<br>
Two roles: Software Engineering Intern (F1.JAS), working on a RAG chatbot, and Data Engineering Intern, on an Oracle to SQL Server migration.

<details>
<summary>詳細 · Details</summary>
<br>

- **Software Engineering Intern (F1.JAS):** contributed to a document-research AI chatbot using RAG with the OpenAI API. Built the indexing pipeline in Python (chunking, embeddings stored in Pinecone) and worked on Q&A features and prompt refinement.
- **Data Engineering Intern:** migrated tables from Oracle to SQL Server, automated with Informatica PowerCenter (ETL mappings and workflows), and validated the results by reconciling row counts and sample records.

</details>

<img src="assets/h-stack.svg" alt="Tech stack">

**Languages**<br>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=java,cs,ts,js,py,c&theme=dark">
  <img alt="Java, C#, TypeScript, JavaScript, Python, C" src="https://skillicons.dev/icons?i=java,cs,ts,js,py,c&theme=light">
</picture>

**Backend and frontend**<br>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=spring,dotnet,react,vite&theme=dark">
  <img alt="Spring Boot, .NET, React, Vite" src="https://skillicons.dev/icons?i=spring,dotnet,react,vite&theme=light">
</picture><br>
<sub>Spring Boot · ASP.NET Core 8 · EF Core · JSP/Servlet · React · Vite</sub>

**Data**<br>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=postgres,mysql,redis,firebase&theme=dark">
  <img alt="PostgreSQL, MySQL, Redis, Firebase" src="https://skillicons.dev/icons?i=postgres,mysql,redis,firebase&theme=light">
</picture><br>
<sub>PostgreSQL (+ pgvector) · SQL Server · MySQL · Redis · Firebase</sub>

**AI / LLM**<br>
<sub>RAG · Embeddings · OpenAI API · Google Gemini API · Pinecone · Prompt engineering · AI agents</sub>

**Architecture**<br>
<sub>Clean Architecture · CQRS · REST APIs · MVC</sub>

**DevOps and tools**<br>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=docker,githubactions,linux,git,idea,vscode&theme=dark">
  <img alt="Docker, GitHub Actions, Linux, Git, IntelliJ IDEA, VS Code" src="https://skillicons.dev/icons?i=docker,githubactions,linux,git,idea,vscode&theme=light">
</picture><br>
<sub>Docker Compose · Caddy · Jira · Hangfire · Informatica PowerCenter</sub>

<details>
<summary><b>資格 · Certifications</b></summary>
<br>

- Artificial Intelligence: an Overview Specialization, 2026
- User Experience Research and Design Specialization, 2026
- Project Management Principles and Practices, 2025
- Software Development Lifecycle, 2024
- Computer Communications Specialization, 2024
- Web Design for Everybody: Basics of Web Development & Coding, 2023

</details>

<br>

<div align="center">

<img src="assets/footer.svg" width="100%" alt="Feel free to get in touch. Open to Backend and Fullstack Software Engineer roles.">

<a href="mailto:khanhsteve21@gmail.com">khanhsteve21@gmail.com</a>

</div>
