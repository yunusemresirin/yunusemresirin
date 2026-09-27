# Hi, I'm Yunus Emre Sirin 👋

**Software architecture · distributed systems · AI infrastructure · autonomous systems**

I'm currently working at the **DLR Institute for AI Safety** while pursuing my **M.Sc. in Computer Science at Hochschule Bonn-Rhein-Sieg**.

I mostly work on systems where the interesting part starts after the first endpoint is written: service boundaries, configuration, interfaces, orchestration, testing, and keeping components understandable as the codebase grows.

On paper, my stack is **Python, FastAPI, TypeScript, React, Java, C++, Docker and ROS 2**. In practice, I spend more time deciding what should depend on what — and what probably shouldn't.

---

## 🚀 Current focus

At DLR, I'm working on **service-based software architecture** with configuration-driven components and shared interfaces across API, CLI and MCP-facing functionality.

A recurring question in that work is how to add new capabilities without making every part of the system know about every other part. That has led me toward registries, adapters, explicit interfaces and small services with clearly defined responsibilities.

I'm also exploring **Model Context Protocol (MCP)** and LLM integration: not as a separate AI layer, but as another interface that should fit cleanly into an existing architecture.

---

## 🧩 Selected work

### ⚙️ [WirSchiffenDas](https://github.com/yunusemresirin/WirSchiffenDas)

Microservice-based quality analysis for diesel-engine configurations.

Six backend services collaborate through a choreographed analysis flow. Circuit breakers handle service failures, while a React frontend exposes runtime health, analysis state and results without taking over backend orchestration.

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-6C63FF?logoColor=white)

### 🏢 [ERP System for Personnel & Shift Planning](https://github.com/yunusemresirin/RestOfGibrAlda)

A modular ERP system built around personnel management, shift planning and payroll logic.

The project focused on integration architecture, separation of responsibilities, business-rule processing and persistent data exchange between system components.

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Architecture](https://img.shields.io/badge/Software_Architecture-4B5563?logoColor=white)
![Integration](https://img.shields.io/badge/Integration_Patterns-8B5CF6?logoColor=white)

### 🤖 [Robile Navigation & SLAM](https://github.com/yunusemresirin/amr-ss25-projects-stark_syndicate_m42)

Autonomous navigation for a mobile robot using ROS 2.

The project combines **A\* global planning**, **potential-field navigation**, **Monte Carlo localization**, automated mapping and environment exploration.

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?logo=ros&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SLAM](https://img.shields.io/badge/SLAM-0EA5E9?logoColor=white)
![Autonomous Navigation](https://img.shields.io/badge/Autonomous_Navigation-14B8A6?logoColor=white)

---

## 🛠️ Technologies

### Architecture & Backend

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-02569B?logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-6C63FF?logoColor=white)

### Frontend

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?logo=mui&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)

### AI & Developer Tooling

![MCP](https://img.shields.io/badge/Model_Context_Protocol-7C3AED?logoColor=white)
![LLM](https://img.shields.io/badge/LLM_Integration-8B5CF6?logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)

### Robotics & Systems

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?logo=ros&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![SLAM](https://img.shields.io/badge/SLAM-0EA5E9?logoColor=white)
![Simulation](https://img.shields.io/badge/Simulation-64748B?logoColor=white)

### Quality & Delivery

![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?logo=githubactions&logoColor=white)

---

## 🧠 How I work

I usually spend more time on boundaries than on frameworks: between services, between modules, and between what a feature appears to need and what the system actually needs.

I prefer understanding a system before changing it. Not because everything needs to be perfect, but because a lot of architectural complexity starts with solving the visible problem too quickly.

Outside of my current work, I'm particularly interested in **distributed systems, software verification, developer tooling and aerospace software** — especially systems where reliability is part of the architecture rather than something added at the end.

Still learning, still building, and generally more interested in understanding systems than collecting technologies.

---

## 🎓 Education

**M.Sc. Computer Science**  
Hochschule Bonn-Rhein-Sieg · 2025 – Present

**B.Sc. Business Information Systems**  
Hochschule Bonn-Rhein-Sieg · Graduated 2025

---

## 🤝 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yunus_Emre_Sirin-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yunus-emre-sirin/)
[![GitHub](https://img.shields.io/badge/GitHub-yunusemresirin-181717?logo=github&logoColor=white)](https://github.com/yunusemresirin)
[![Email](https://img.shields.io/badge/Email-Yunus.Emre.Sirin%40outlook.de-0078D4?logo=microsoftoutlook&logoColor=white)](mailto:Yunus.Emre.Sirin@outlook.de)
