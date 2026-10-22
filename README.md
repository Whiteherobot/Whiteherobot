<div align="center">

<img width="100%" alt="Michael Lata banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:040808,100:648887&height=220&section=header&text=MICHAEL%20LATA&fontColor=cedcd4&fontSize=52&fontAlignY=38&animation=fadeIn&desc=freelance%20engineer%20%C2%B7%20computer%20vision%20%C2%B7%20edge%20AI&descAlignY=58&descSize=16&descColor=abccb9" />

# Hi, I'm Michael (Michi)

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=b4e7d8&center=true&vCenter=true&width=680&lines=Freelance+Software+Engineer;Computer+Vision+%26+Edge+AI;Full-stack+web+and+real-time+apps;Distributed+systems+%26+self-hosting;From+Java+Swing+(2022)+to+edge+AI+(2026)" alt="Typing SVG" />

<a href="mailto:mlata6235@gmail.com"><img src="https://img.shields.io/badge/Email-1d2121?style=for-the-badge&logo=gmail&logoColor=b4e7d8" alt="Email"/></a>
<img src="https://hits.sh/github.com/Whiteherobot.svg?style=for-the-badge&label=Profile%20views&color=648887&labelColor=1d2121" alt="Profile views"/>

</div>

<br>

I'm a freelance software engineer from Ecuador (Computer Science, Universidad Politécnica Salesiana). I build
**computer vision and edge AI** systems, and the software around them: **full-stack web apps**, **distributed
back-ends** and **desktop business apps**, with tests and CI from the first commit. Around 90 repositories so
far, from my first Java classes in 2022 to deep learning on microcontrollers.

Open to freelance work on computer vision, AI-backed products and business applications. Reach me by email.

### What I'm working on

- **Thesis — pictogram recognition on the edge.** A MobileNetV3-Small quantized to INT8 recognizes 20 AAC
  pictograms (ARASAAC) directly on an Arduino UNO Q, with no cloud: 92.5 % accuracy at **29.8 ms per image**
  in 51 MB of RAM. Co-authored with Jordy Romero; the repository is private for now.
- **Pliego — a collaborative LaTeX editor.** An Overleaf-style editor I built for writing the thesis together:
  real-time editing with CRDTs (Yjs + CodeMirror 6), a visual mode with KaTeX, live PDF with SyncTeX, comments,
  a self-hosted spell checker, multiple projects from templates and automatic git backups.
- **Homelab.** A Proxmox server at home (LXC, Tailscale) running Pliego, a network print and scan service and a
  game server, plus private MCP servers that let an assistant reach my notes, lights and cameras.

### Products I've built (private)

- **Endify CRM for clinics** — WhatsApp, scheduling, quotes, payments and Ecuadorian e-invoicing (SRI).
- **Forjia** — gym app with routines, progress, achievements, rankings and an AI coach (Angular + Firebase PWA).
- **Mescachi** — personal finance by pay periods, in daily use for months (Angular + Firebase PWA).
- **El Café Que Te Conté** — point of sale for a coffee shop with a teammate (Angular + PrimeNG front end on a NestJS +
  PostgreSQL API) and the demand forecasting model behind it.
- **Endify website** — company site in Next.js, Tailwind and Framer Motion.

### Featured projects

**Computer vision & edge AI**

| Project | What it is |
|---|---|
| [yolo-segmentacion-transito-gpu](https://github.com/Whiteherobot/yolo-segmentacion-transito-gpu) | YOLO11-seg for traffic objects, YOLOv12 and RealPLKSR super-resolution, plus an OpenCV CUDA pipeline in C++ benchmarked GPU vs CPU. |
| [esp32-estereo-y-deteccion-ambulancias](https://github.com/Whiteherobot/esp32-estereo-y-deteccion-ambulancias) | Stereo vision with two ESP32-CAMs (calibration, distance measurement, AR) and HOG+SVM ambulance detection with Telegram alerts. |
| [yolo-personas-autos-perros](https://github.com/Whiteherobot/yolo-personas-autos-perros) | YOLOv8s trained on Pascal VOC 2007 for people, cars and dogs (mAP50 0.856 on test), served through a Flask API. |
| [opencv-android-efectos-camara](https://github.com/Whiteherobot/opencv-android-efectos-camara) | Android camera app with OpenCV in C++ over JNI: chroma key, noise and real-time filters. |

**Applied AI & data**

| Project | What it is |
|---|---|
| [prediccion-demanda-cafeteria](https://github.com/Whiteherobot/prediccion-demanda-cafeteria) | 1/3/7-day demand forecasting for a real coffee shop with SVR, anomaly alerts and SHAP, behind a FastAPI API with an Angular beta. |
| [agente-pedidos-neo4j](https://github.com/Whiteherobot/agente-pedidos-neo4j) | Ordering agent over a Neo4j catalog: similarity routing, LangGraph, FastAPI and optional Gemini. |
| [cifar10-clasificador-feedback](https://github.com/Whiteherobot/cifar10-clasificador-feedback) | CIFAR-10 classifier in Keras behind FastAPI, with label correction and retraining with rehearsal. |
| [crypto-trading-bot](https://github.com/Whiteherobot/crypto-trading-bot) | Algorithmic trading bot on the Binance testnet: three strategies, backtesting, risk management and a dashboard. |

**Distributed systems**

| Project | What it is |
|---|---|
| [microservicios-ordenes](https://github.com/Whiteherobot/microservicios-ordenes) | Purchase orders across Spring Boot, Quarkus and FastAPI microservices behind an nginx gateway, with fault tolerance and idempotency. |
| [reservas-tolerancia-fallos](https://github.com/Whiteherobot/reservas-tolerancia-fallos) | Ticket sales with Node.js microservices: circuit breaker, timeouts with reconciliation, rate limiting, bulkheads and atomic seat allocation in Redis. |
| [k8s-redis-sensores](https://github.com/Whiteherobot/k8s-redis-sensores) | Robot sensors publishing to Redis on Kubernetes with Secrets, PVCs and real probes, verified in kind. |
| [websocket-eleccion-lider](https://github.com/Whiteherobot/websocket-eleccion-lider) | Chang–Roberts leader election over WebSockets with five containers; the ring repairs itself when the leader dies. |
| [rabbitmq-monitoreo-sensores](https://github.com/Whiteherobot/rabbitmq-monitoreo-sensores) | Real-time sensor monitoring with RabbitMQ, HTTP and WebSockets and an operator screen, all in Docker Compose. |

**Web, desktop & foundations**

| Project | What it is |
|---|---|
| [jakarta-postulantes-api](https://github.com/Whiteherobot/jakarta-postulantes-api) | REST API in Jakarta EE 10 (JAX-RS, CDI, JPA) on WildFly, with an end-to-end test in CI and an Angular client. |
| [streamflix-pocketbase](https://github.com/Whiteherobot/streamflix-pocketbase) | Movie and series catalog on PocketBase: role rules, atomic downloads with hooks and migrations. |
| [csharp-centro-medico](https://github.com/Whiteherobot/csharp-centro-medico) | Desktop app for a medical clinic: patients, appointments and invoicing. C#, WPF on .NET 10, MVVM and Oracle. |
| [unity-simulacion-semaforo](https://github.com/Whiteherobot/unity-simulacion-semaforo) | Unity 6 intersection with an adaptive traffic light that splits green time by queue length; EditMode and PlayMode tests. |
| [java-simulador-banco](https://github.com/Whiteherobot/java-simulador-banco) | Animated discrete-event simulation of a bank queue, checked against queueing theory (M/M/c, Erlang C). |
| [java-mvc-biblioteca](https://github.com/Whiteherobot/java-mvc-biblioteca) | Library management in Java Swing with MVC: members, ISBN-13 books and loans with late fees — one of 21 Java projects from 2022. |

All of them include tests and CI; the READMEs (in Spanish) explain where each project came from.

### Journey

| Year | What I was building |
|---|---|
| **2022** | Object-oriented programming in Java: 21 projects with Swing, MVC, JTable, serialization and Java2D. |
| **2024** | Desktop apps in C# and WPF on Oracle; first business software. |
| **2025** | Web with Angular, React and Vue; Spring Boot and Jakarta EE APIs; Neo4j, Firebase and Unity; Docker, RabbitMQ and WebSockets for distributed systems. |
| **2026** | Computer vision (YOLO, OpenCV CUDA, stereo ESP32-CAM), ML and forecasting, Kubernetes and microservices, products for Endify, my homelab and the edge AI thesis. |

<br>

### AI & computer vision
<p> <img src="https://img.shields.io/badge/Python-1d2121?style=for-the-badge&logo=python&logoColor=b4e7d8" alt="Python"/> <img src="https://img.shields.io/badge/PyTorch-1d2121?style=for-the-badge&logo=pytorch&logoColor=b4e7d8" alt="PyTorch"/> <img src="https://img.shields.io/badge/TensorFlow%20Lite-1d2121?style=for-the-badge&logo=tensorflow&logoColor=b4e7d8" alt="TensorFlow Lite"/> <img src="https://img.shields.io/badge/Keras-1d2121?style=for-the-badge&logo=keras&logoColor=b4e7d8" alt="Keras"/> <img src="https://img.shields.io/badge/scikit--learn-1d2121?style=for-the-badge&logo=scikitlearn&logoColor=b4e7d8" alt="scikit-learn"/> <img src="https://img.shields.io/badge/OpenCV-1d2121?style=for-the-badge&logo=opencv&logoColor=b4e7d8" alt="OpenCV"/> <img src="https://img.shields.io/badge/CUDA-1d2121?style=for-the-badge&logo=nvidia&logoColor=b4e7d8" alt="CUDA"/> <img src="https://img.shields.io/badge/YOLO-1d2121?style=for-the-badge&logo=ultralytics&logoColor=b4e7d8" alt="YOLO"/> <img src="https://img.shields.io/badge/ONNX-1d2121?style=for-the-badge&logo=onnx&logoColor=b4e7d8" alt="ONNX"/> <img src="https://img.shields.io/badge/pandas-1d2121?style=for-the-badge&logo=pandas&logoColor=b4e7d8" alt="pandas"/> <img src="https://img.shields.io/badge/NumPy-1d2121?style=for-the-badge&logo=numpy&logoColor=b4e7d8" alt="NumPy"/> <img src="https://img.shields.io/badge/Jupyter-1d2121?style=for-the-badge&logo=jupyter&logoColor=b4e7d8" alt="Jupyter"/> <img src="https://img.shields.io/badge/LangGraph-1d2121?style=for-the-badge&logo=langchain&logoColor=b4e7d8" alt="LangGraph"/> <img src="https://img.shields.io/badge/Gemini-1d2121?style=for-the-badge&logo=googlegemini&logoColor=b4e7d8" alt="Gemini"/> <img src="https://img.shields.io/badge/Streamlit-1d2121?style=for-the-badge&logo=streamlit&logoColor=b4e7d8" alt="Streamlit"/> <img src="https://img.shields.io/badge/Plotly-1d2121?style=for-the-badge&logo=plotly&logoColor=b4e7d8" alt="Plotly"/> <img src="https://img.shields.io/badge/Kaggle-1d2121?style=for-the-badge&logo=kaggle&logoColor=b4e7d8" alt="Kaggle"/> </p>

### Frontend
<p> <img src="https://img.shields.io/badge/TypeScript-1d2121?style=for-the-badge&logo=typescript&logoColor=b4e7d8" alt="TypeScript"/> <img src="https://img.shields.io/badge/JavaScript-1d2121?style=for-the-badge&logo=javascript&logoColor=b4e7d8" alt="JavaScript"/> <img src="https://img.shields.io/badge/Angular-1d2121?style=for-the-badge&logo=angular&logoColor=b4e7d8" alt="Angular"/> <img src="https://img.shields.io/badge/React-1d2121?style=for-the-badge&logo=react&logoColor=b4e7d8" alt="React"/> <img src="https://img.shields.io/badge/Vue.js-1d2121?style=for-the-badge&logo=vuedotjs&logoColor=b4e7d8" alt="Vue.js"/> <img src="https://img.shields.io/badge/Next.js-1d2121?style=for-the-badge&logo=nextdotjs&logoColor=b4e7d8" alt="Next.js"/> <img src="https://img.shields.io/badge/Vite-1d2121?style=for-the-badge&logo=vite&logoColor=b4e7d8" alt="Vite"/> <img src="https://img.shields.io/badge/Tailwind%20CSS-1d2121?style=for-the-badge&logo=tailwindcss&logoColor=b4e7d8" alt="Tailwind CSS"/> <img src="https://img.shields.io/badge/PrimeNG-1d2121?style=for-the-badge&logo=primeng&logoColor=b4e7d8" alt="PrimeNG"/> <img src="https://img.shields.io/badge/Material%20UI-1d2121?style=for-the-badge&logo=mui&logoColor=b4e7d8" alt="Material UI"/> <img src="https://img.shields.io/badge/Radix%20UI-1d2121?style=for-the-badge&logo=radixui&logoColor=b4e7d8" alt="Radix UI"/> <img src="https://img.shields.io/badge/Chart.js-1d2121?style=for-the-badge&logo=chartdotjs&logoColor=b4e7d8" alt="Chart.js"/> <img src="https://img.shields.io/badge/PWA-1d2121?style=for-the-badge&logo=pwa&logoColor=b4e7d8" alt="PWA"/> <img src="https://img.shields.io/badge/HTML5-1d2121?style=for-the-badge&logo=html5&logoColor=b4e7d8" alt="HTML5"/> <img src="https://img.shields.io/badge/CSS-1d2121?style=for-the-badge&logo=css&logoColor=b4e7d8" alt="CSS"/> </p>

### Backend
<p> <img src="https://img.shields.io/badge/Node.js-1d2121?style=for-the-badge&logo=nodedotjs&logoColor=b4e7d8" alt="Node.js"/> <img src="https://img.shields.io/badge/Express-1d2121?style=for-the-badge&logo=express&logoColor=b4e7d8" alt="Express"/> <img src="https://img.shields.io/badge/NestJS-1d2121?style=for-the-badge&logo=nestjs&logoColor=b4e7d8" alt="NestJS"/> <img src="https://img.shields.io/badge/Prisma-1d2121?style=for-the-badge&logo=prisma&logoColor=b4e7d8" alt="Prisma"/> <img src="https://img.shields.io/badge/Java-1d2121?style=for-the-badge&logo=openjdk&logoColor=b4e7d8" alt="Java"/> <img src="https://img.shields.io/badge/Spring%20Boot-1d2121?style=for-the-badge&logo=springboot&logoColor=b4e7d8" alt="Spring Boot"/> <img src="https://img.shields.io/badge/Quarkus-1d2121?style=for-the-badge&logo=quarkus&logoColor=b4e7d8" alt="Quarkus"/> <img src="https://img.shields.io/badge/Jakarta%20EE-1d2121?style=for-the-badge&logo=openjdk&logoColor=b4e7d8" alt="Jakarta EE"/> <img src="https://img.shields.io/badge/Hibernate-1d2121?style=for-the-badge&logo=hibernate&logoColor=b4e7d8" alt="Hibernate"/> <img src="https://img.shields.io/badge/FastAPI-1d2121?style=for-the-badge&logo=fastapi&logoColor=b4e7d8" alt="FastAPI"/> <img src="https://img.shields.io/badge/Flask-1d2121?style=for-the-badge&logo=flask&logoColor=b4e7d8" alt="Flask"/> <img src="https://img.shields.io/badge/C%23%20%C2%B7%20.NET-1d2121?style=for-the-badge&logo=dotnet&logoColor=b4e7d8" alt="C# · .NET"/> <img src="https://img.shields.io/badge/Firebase-1d2121?style=for-the-badge&logo=firebase&logoColor=b4e7d8" alt="Firebase"/> <img src="https://img.shields.io/badge/Supabase-1d2121?style=for-the-badge&logo=supabase&logoColor=b4e7d8" alt="Supabase"/> <img src="https://img.shields.io/badge/PocketBase-1d2121?style=for-the-badge&logo=pocketbase&logoColor=b4e7d8" alt="PocketBase"/> </p>

### Data & messaging
<p> <img src="https://img.shields.io/badge/PostgreSQL-1d2121?style=for-the-badge&logo=postgresql&logoColor=b4e7d8" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/MySQL-1d2121?style=for-the-badge&logo=mysql&logoColor=b4e7d8" alt="MySQL"/> <img src="https://img.shields.io/badge/Oracle-1d2121?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYjRlN2Q4IiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+PGVsbGlwc2UgY3g9IjEyIiBjeT0iNSIgcng9IjkiIHJ5PSIzIi8+PHBhdGggZD0iTTMgNVYxOUE5IDMgMCAwIDAgMjEgMTlWNSIvPjxwYXRoIGQ9Ik0zIDEyQTkgMyAwIDAgMCAyMSAxMiIvPjwvc3ZnPg==" alt="Oracle"/> <img src="https://img.shields.io/badge/SQL%20Server-1d2121?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYjRlN2Q4IiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+PGVsbGlwc2UgY3g9IjEyIiBjeT0iNSIgcng9IjkiIHJ5PSIzIi8+PHBhdGggZD0iTTMgNVYxOUE5IDMgMCAwIDAgMjEgMTlWNSIvPjxwYXRoIGQ9Ik0zIDEyQTkgMyAwIDAgMCAyMSAxMiIvPjwvc3ZnPg==" alt="SQL Server"/> <img src="https://img.shields.io/badge/Redis-1d2121?style=for-the-badge&logo=redis&logoColor=b4e7d8" alt="Redis"/> <img src="https://img.shields.io/badge/Neo4j-1d2121?style=for-the-badge&logo=neo4j&logoColor=b4e7d8" alt="Neo4j"/> <img src="https://img.shields.io/badge/RabbitMQ-1d2121?style=for-the-badge&logo=rabbitmq&logoColor=b4e7d8" alt="RabbitMQ"/> </p>

### Infrastructure
<p> <img src="https://img.shields.io/badge/Docker-1d2121?style=for-the-badge&logo=docker&logoColor=b4e7d8" alt="Docker"/> <img src="https://img.shields.io/badge/Kubernetes-1d2121?style=for-the-badge&logo=kubernetes&logoColor=b4e7d8" alt="Kubernetes"/> <img src="https://img.shields.io/badge/nginx-1d2121?style=for-the-badge&logo=nginx&logoColor=b4e7d8" alt="nginx"/> <img src="https://img.shields.io/badge/Caddy-1d2121?style=for-the-badge&logo=caddy&logoColor=b4e7d8" alt="Caddy"/> <img src="https://img.shields.io/badge/GitHub%20Actions-1d2121?style=for-the-badge&logo=githubactions&logoColor=b4e7d8" alt="GitHub Actions"/> <img src="https://img.shields.io/badge/Proxmox-1d2121?style=for-the-badge&logo=proxmox&logoColor=b4e7d8" alt="Proxmox"/> <img src="https://img.shields.io/badge/Tailscale-1d2121?style=for-the-badge&logo=tailscale&logoColor=b4e7d8" alt="Tailscale"/> <img src="https://img.shields.io/badge/Cloudflare-1d2121?style=for-the-badge&logo=cloudflare&logoColor=b4e7d8" alt="Cloudflare"/> <img src="https://img.shields.io/badge/Linux-1d2121?style=for-the-badge&logo=linux&logoColor=b4e7d8" alt="Linux"/> <img src="https://img.shields.io/badge/Arch%20Linux-1d2121?style=for-the-badge&logo=archlinux&logoColor=b4e7d8" alt="Arch Linux"/> <img src="https://img.shields.io/badge/Hyprland-1d2121?style=for-the-badge&logo=hyprland&logoColor=b4e7d8" alt="Hyprland"/> <img src="https://img.shields.io/badge/Bash-1d2121?style=for-the-badge&logo=gnubash&logoColor=b4e7d8" alt="Bash"/> <img src="https://img.shields.io/badge/Syncthing-1d2121?style=for-the-badge&logo=syncthing&logoColor=b4e7d8" alt="Syncthing"/> <img src="https://img.shields.io/badge/Git-1d2121?style=for-the-badge&logo=git&logoColor=b4e7d8" alt="Git"/> </p>

### Testing & quality
<p> <img src="https://img.shields.io/badge/JUnit%205-1d2121?style=for-the-badge&logo=junit5&logoColor=b4e7d8" alt="JUnit 5"/> <img src="https://img.shields.io/badge/Vitest-1d2121?style=for-the-badge&logo=vitest&logoColor=b4e7d8" alt="Vitest"/> <img src="https://img.shields.io/badge/Jest-1d2121?style=for-the-badge&logo=jest&logoColor=b4e7d8" alt="Jest"/> <img src="https://img.shields.io/badge/pytest-1d2121?style=for-the-badge&logo=pytest&logoColor=b4e7d8" alt="pytest"/> <img src="https://img.shields.io/badge/ESLint-1d2121?style=for-the-badge&logo=eslint&logoColor=b4e7d8" alt="ESLint"/> <img src="https://img.shields.io/badge/Prettier-1d2121?style=for-the-badge&logo=prettier&logoColor=b4e7d8" alt="Prettier"/> </p>

### Also
<p> <img src="https://img.shields.io/badge/C%2B%2B-1d2121?style=for-the-badge&logo=cplusplus&logoColor=b4e7d8" alt="C++"/> <img src="https://img.shields.io/badge/CMake-1d2121?style=for-the-badge&logo=cmake&logoColor=b4e7d8" alt="CMake"/> <img src="https://img.shields.io/badge/ESP32-1d2121?style=for-the-badge&logo=espressif&logoColor=b4e7d8" alt="ESP32"/> <img src="https://img.shields.io/badge/Arduino-1d2121?style=for-the-badge&logo=arduino&logoColor=b4e7d8" alt="Arduino"/> <img src="https://img.shields.io/badge/Unity-1d2121?style=for-the-badge&logo=unity&logoColor=b4e7d8" alt="Unity"/> <img src="https://img.shields.io/badge/Android-1d2121?style=for-the-badge&logo=android&logoColor=b4e7d8" alt="Android"/> <img src="https://img.shields.io/badge/Kotlin-1d2121?style=for-the-badge&logo=kotlin&logoColor=b4e7d8" alt="Kotlin"/> <img src="https://img.shields.io/badge/LaTeX-1d2121?style=for-the-badge&logo=latex&logoColor=b4e7d8" alt="LaTeX"/> <img src="https://img.shields.io/badge/Figma-1d2121?style=for-the-badge&logo=figma&logoColor=b4e7d8" alt="Figma"/> <img src="https://img.shields.io/badge/Obsidian-1d2121?style=for-the-badge&logo=obsidian&logoColor=b4e7d8" alt="Obsidian"/> <img src="https://img.shields.io/badge/Discord-1d2121?style=for-the-badge&logo=discord&logoColor=b4e7d8" alt="Discord"/> <img src="https://img.shields.io/badge/WhatsApp%20API-1d2121?style=for-the-badge&logo=whatsapp&logoColor=b4e7d8" alt="WhatsApp API"/> </p>

<br>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/whiteherobot/whiteherobot/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/whiteherobot/whiteherobot/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/whiteherobot/whiteherobot/output/github-contribution-grid-snake.svg" />
</picture>

</div>
