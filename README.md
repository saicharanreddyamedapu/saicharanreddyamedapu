<h1 align="center">Hi 👋, I'm Sai Charan Reddy</h1>

<h3 align="center">
  Computer Science Student | Full-Stack Developer | AI/ML Enthusiast | DevOps & Cloud
</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=Full-Stack+Development;AI%2FML+%26+Generative+AI;DevOps+%26+Cloud+Engineering;Software+Testing+%26+QA;Building+Reliable+Software" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/saicharanreddyamedapu">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/sai-charan-reddy-amedapu-6b6924291/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
  <a href="https://leetcode.com/u/saicharanreddy01/">
    <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
</p>

---

## 🚀 About Me

I'm a Computer Science undergraduate at **Bennett University** who enjoys building software, exploring AI, automating infrastructure, and improving application quality.

- 💻 Interested in **full-stack development and backend engineering**.
- 🤖 Building AI-powered applications using **LLMs, RAG, embeddings, and multi-agent workflows**.
- ☁️ Exploring **AWS, Linux, Docker, Kubernetes, and CI/CD automation**.
- 🧪 Practicing software quality through **test case design, functional testing, bug reporting, and test automation**.
- 🛠️ Enjoy solving problems, debugging applications, and learning technologies through hands-on projects.

My goal is to build applications that are useful, scalable, secure, and reliable.

---

## 💻 1. Software Development Projects

### 🔹 [Hirely — Full-Stack Job Platform](https://github.com/saicharanreddyamedapu/Hirely)

**Tech Stack:** Java · Spring Boot · React · PostgreSQL · Spring Security · AWS

- Developed a full-stack job platform supporting Candidate, Company, and Hiring Manager roles.
- Built REST APIs using a layered Spring Boot architecture with PostgreSQL and JPA/Hibernate.
- Implemented JWT authentication, BCrypt password hashing, and role-based authorization.
- Added features for job postings, applications, resume uploads, and asynchronous email notifications.
- Deployed the backend on AWS EC2 and the frontend on Vercel.

🔗 [Live Demo](https://hireyou-opal.vercel.app)

### 🔹 [Task Tracker](https://github.com/saicharanreddyamedapu/Task_Tracker)

**Tech Stack:** Java · Spring Boot · React · Vite · PostgreSQL

- Built a full-stack task management application with a React frontend and Spring Boot REST API.
- Implemented authentication and user-specific task management.
- Developed CRUD operations, deadline tracking, and task completion status.
- Used PostgreSQL for persistent storage and Spring Data JPA for database operations.

### 🔹 Parking Lot System — Low-Level Design

**Tech Stack:** Java · Object-Oriented Programming · Design Patterns · Multithreading

- Designed a parking lot system supporting multiple floors and different vehicle types.
- Applied Factory, Strategy, and Singleton design patterns.
- Implemented configurable pricing, payment options, and parking ticket generation.
- Explored object-oriented design and concurrent vehicle entry and exit.

### 🔹 [Laundry Management System](https://github.com/saicharanreddyamedapu/laundry-management-system-bu)

**Tech Stack:** Python · Django · SQLite · HTML · CSS · JavaScript

- Developed a web application for managing laundry orders and services.
- Built backend functionality using Django and SQLite.
- Created interfaces for order tracking and service management.

---

## 🤖 2. AI, Machine Learning & Generative AI Projects

### 🔹 [SkillLens — AI Resume Screening](https://github.com/saicharanreddyamedapu/SkillLens)

**Tech Stack:** Python · FastAPI · Gemini · Qdrant · Dense & Sparse Embeddings

- Built an AI-powered resume-screening pipeline that retrieves relevant candidate information beyond simple keyword matching.
- Combined dense embeddings using `BAAI/bge-base-en-v1.5` with sparse `SPLADE++` retrieval.
- Developed resume-level ranking using the top-three chunk similarity scores for each resume.
- Integrated Gemini for natural-language query enhancement and inference of the requested number of results.

### 🔹 [Float Chat — Multi-Agent Data Retrieval](https://github.com/saicharanreddyamedapu/Float_Chat)

**Tech Stack:** Python · LangGraph · Gemini · MongoDB · PostgreSQL

- Developed a natural-language interface for retrieving oceanographic float data.
- Designed a three-agent workflow consisting of Decomposition, Filter, and SQL agents.
- Combined MongoDB geospatial and metadata filtering with structured PostgreSQL queries.
- Routed user queries to retrieval methods appropriate to the underlying data.

### 🔹 [GPT-2 Implementation from Scratch](https://github.com/saicharanreddyamedapu/GPT2)

**Tech Stack:** Python · PyTorch · Transformers · Deep Learning

- Implemented GPT-2 architecture components, including token and positional embeddings, causal multi-head self-attention, and transformer blocks.
- Explored residual connections, normalization, and autoregressive text generation.
- Implemented KV-cache support for separate prefill and decode passes.
- Trained on FineWeb using gradient accumulation, cosine learning-rate decay, and bfloat16 mixed precision.

### 🔹 [WhatsApp Chat Analyzer](https://github.com/saicharanreddyamedapu/Whatsapp-Chat-Analyzer)

**Tech Stack:** Python · Streamlit · Pandas · Matplotlib · WordCloud

- Built a chat-analysis application to explore message activity and communication patterns.
- Visualized timelines, activity patterns, frequent words, and emoji usage.
- Applied text filtering to improve the relevance of multilingual text analysis.

---

## ☁️ 3. DevOps, Cloud & Automation Projects

### 🔹 AI Kubernetes Troubleshooting Agent

**Tech Stack:** Python · FastAPI · Kubernetes · kubectl · OpenRouter

- Developed an AI-assisted troubleshooting platform for investigating Kubernetes workloads.
- Collected structured evidence from pod inspection, logs, events, deployment checks, and network diagnostics.
- Integrated an LLM to correlate investigation results, suggest likely root causes, and recommend kubectl or YAML fixes.
- Covered scenarios such as `CrashLoopBackOff`, `ImagePullBackOff`, pending pods, rollout failures, and service connectivity issues.
- Built a dashboard with authentication, live investigation progress, and stored troubleshooting history.

### 🔹 CI/CD Pipeline for a Dockerized Web Application

**Tech Stack:** Docker · Jenkins · AWS EC2 · Linux · Git · GitHub

- Containerized a web application using Docker and a custom Dockerfile.
- Built a Jenkins pipeline to automate repository checkout, build steps, Docker image creation, and deployment.
- Configured a Linux-based AWS EC2 environment, including SSH access and security groups.
- Practiced automated deployments and container lifecycle management.

### 🛠️ DevOps & Cloud Technologies

- **Cloud:** AWS EC2, S3, EBS, IAM, VPC, CloudWatch, SNS, ELB, Auto Scaling, Lambda
- **Containers:** Docker, Docker Compose, Kubernetes
- **CI/CD:** Jenkins, Maven, SonarQube, Nexus
- **Infrastructure as Code:** Terraform, Ansible
- **Monitoring:** Prometheus, Grafana, CloudWatch
- **Operating Systems & Scripting:** Linux (Ubuntu), Bash, Python

---

## 🧪 4. Software Testing & Quality Assurance

### 🔹 [ShopperStack E-commerce Testing](https://github.com/saicharanreddyamedapu/shoppersstack-test-cases)

**Focus:** Manual Testing · Functional Testing · Integration Testing

- Designed and executed **25+ test cases** covering registration, login, product search, cart, and checkout.
- Performed functional and integration testing to validate end-to-end workflows.
- Identified and documented **10+ defects** with reproduction steps, expected versus actual results, and severity classifications.
- Tested invalid inputs, boundary values, and error-handling scenarios.

### 🔍 Testing Skills & Tools

- **Testing:** Manual Testing, Functional Testing, Integration Testing, Regression Testing
- **Automation:** Selenium WebDriver, TestNG, Page Object Model (POM), Data-Driven Testing
- **Test Design:** Test Case Design, Test Execution, Bug Reporting, Defect Life Cycle
- **API Testing:** Postman
- **Fundamentals:** Software Development Life Cycle (SDLC), Software Testing Life Cycle (STLC)
- **Supporting Tools:** Jira, Git, GitHub, Linux, Maven

---

## 🛠️ Technical Skills

| Category | Technologies |
|---|---|
| **Languages** | Java, Python, JavaScript, Bash |
| **Frontend** | React, HTML, CSS, Vite |
| **Backend** | Spring Boot, FastAPI, Django, REST APIs, Spring Security, JPA/Hibernate |
| **AI/ML** | Machine Learning, Deep Learning, NLP, Generative AI, LLMs, RAG, Transformers, Embeddings |
| **AI Frameworks & Tools** | PyTorch, LangChain, LangGraph, Gemini, Qdrant, MongoDB |
| **Databases** | PostgreSQL, MySQL, MongoDB, SQLite |
| **Cloud & DevOps** | AWS, Docker, Kubernetes, Jenkins, Terraform, Ansible, Linux |
| **Version Control & Tools** | Git, GitHub, Maven, Postman, Selenium, Jira |
| **Core Concepts** | Data Structures & Algorithms, OOP, Design Patterns, Debugging |

---

## 🎓 Certifications

- [Database Management Essentials](https://www.coursera.org/account/accomplishments/verify/Q6S1IYLNN78C)
- [Data Structures](https://www.coursera.org/account/accomplishments/verify/Q9CAHXYIR3Y2)
- [AI Workflow: Data Analysis and Hypothesis Testing](https://www.coursera.org/account/accomplishments/verify/BPBOS2U4WB05)
- [Foundations of Deep Learning: Concepts and Applications](https://nptel.ac.in/noc/E_Certificate/NOC26CS01S95620447704494608)

---

## 📊 GitHub Overview

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=saicharanreddyamedapu&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saicharanreddyamedapu&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

---

## 📫 Connect With Me

<p align="left">
  <a href="mailto:saicharanreddyamedapu4@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/sai-charan-reddy-amedapu-6b6924291/">LinkedIn</a> ·
  <a href="https://github.com/saicharanreddyamedapu">GitHub</a> ·
  <a href="https://leetcode.com/u/saicharanreddy01/">LeetCode</a>
</p>

<p align="center">
  <i>Build. Learn. Test. Automate. Improve. 🚀</i>
</p>
