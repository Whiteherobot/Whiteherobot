<div align="center">

<img width="100%" alt="Michael Lata banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1120,100:134E4A&height=220&section=header&text=MICHAEL%20LATA&fontColor=FBBF24&fontSize=52&fontAlignY=38&animation=fadeIn&desc=freelance%20engineer%20%C2%B7%20computer%20vision%20%C2%B7%20edge%20AI&descAlignY=58&descSize=16&descColor=94A3B8" />

# Hi, I'm Michael (Michi)

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=FBBF24&center=true&vCenter=true&width=680&lines=Freelance+Software+Engineer;Computer+Vision+%26+Edge+AI;Full-stack+web+and+real-time+apps;Distributed+systems+%26+self-hosting;PyTorch+-+OpenCV+-+CUDA+-+TFLite" alt="Typing SVG" />

<a href="mailto:mlata6235@gmail.com"><img src="https://img.shields.io/badge/Email-0B1120?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email"/></a>
<img src="https://hits.sh/github.com/Whiteherobot.svg?style=for-the-badge&label=Profile%20views&color=134E4A&labelColor=0B1120" alt="Profile views"/>

</div>

<br>

I'm a freelance software engineer from Ecuador (Computer Science, Universidad Politécnica Salesiana). I build
**computer vision and edge AI** systems, and the software around them: **full-stack web apps**, **distributed
back-ends** and **desktop business apps**, with tests and CI from the first commit.

Open to freelance work on computer vision, AI-backed products and business applications. Reach me by email.

### What I'm working on

- **Thesis — pictogram recognition on the edge.** A MobileNetV3-Small quantized to INT8 recognizes 20 AAC
  pictograms (ARASAAC) directly on an Arduino UNO Q, with no cloud: 92.5 % accuracy at **29.8 ms per image**
  in 51 MB of RAM. Co-authored with Jordy Romero; the repository is private for now.
- **Pliego — a collaborative LaTeX editor.** An Overleaf-style editor I built for writing the thesis together:
  real-time editing with CRDTs (Yjs + CodeMirror 6), a visual mode with KaTeX, live PDF with SyncTeX, comments,
  a self-hosted spell checker, multiple projects from templates and automatic git backups. It runs on my own
  homelab (Proxmox, LXC, Tailscale).
- **Homelab.** A Proxmox server at home running a network print and scan service, a game server and Pliego,
  plus a few private MCP servers that let an assistant reach my notes, lights and cameras.

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
| [agente-pedidos-neo4j](https://github.com/Whiteherobot/agente-pedidos-neo4j) | Ordering agent over a Neo4j catalog: similarity routing, LangGraph and FastAPI. |
| [crypto-trading-bot](https://github.com/Whiteherobot/crypto-trading-bot) | Algorithmic trading bot on the Binance testnet: three strategies, backtesting, risk management and a dashboard. |

**Distributed systems**

| Project | What it is |
|---|---|
| [microservicios-ordenes](https://github.com/Whiteherobot/microservicios-ordenes) | Purchase orders across Spring Boot, Quarkus and FastAPI microservices behind an nginx gateway, with fault tolerance and idempotency. |
| [reservas-tolerancia-fallos](https://github.com/Whiteherobot/reservas-tolerancia-fallos) | Ticket sales with Node.js microservices: circuit breaker, timeouts with reconciliation, rate limiting, bulkheads and atomic seat allocation in Redis. |
| [k8s-redis-sensores](https://github.com/Whiteherobot/k8s-redis-sensores) | Robot sensors publishing to Redis on Kubernetes with Secrets, PVCs and real probes, verified in kind. |
| [websocket-eleccion-lider](https://github.com/Whiteherobot/websocket-eleccion-lider) | Chang–Roberts leader election over WebSockets with five containers; the ring repairs itself when the leader dies. |

**Desktop & business apps**

| Project | What it is |
|---|---|
| [csharp-centro-medico](https://github.com/Whiteherobot/csharp-centro-medico) | Desktop app for a medical clinic: patients, appointments and invoicing. C#, WPF on .NET 10, MVVM and Oracle. |
| [jakarta-postulantes-api](https://github.com/Whiteherobot/jakarta-postulantes-api) | REST API in Jakarta EE 10 (JAX-RS, CDI, JPA) on WildFly, with an end-to-end test in CI and an Angular client. |
| [java-simulador-banco](https://github.com/Whiteherobot/java-simulador-banco) | Animated discrete-event simulation of a bank queue, checked against queueing theory (M/M/c, Erlang C). |

All of them include tests and CI; the READMEs (in Spanish) explain where each project came from.

<br>

### Computer Vision & AI
<p> <img src="https://img.shields.io/badge/Python-0B1120?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python"/> <img src="https://img.shields.io/badge/PyTorch-0B1120?style=for-the-badge&logo=pytorch&logoColor=EE4C2C" alt="PyTorch"/> <img src="https://img.shields.io/badge/TensorFlow%20Lite-0B1120?style=for-the-badge&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow Lite"/> <img src="https://img.shields.io/badge/OpenCV-0B1120?style=for-the-badge&logo=opencv&logoColor=5C3EE8" alt="OpenCV"/> <img src="https://img.shields.io/badge/CUDA-0B1120?style=for-the-badge&logo=nvidia&logoColor=76B900" alt="CUDA"/> <img src="https://img.shields.io/badge/YOLO-0B1120?style=for-the-badge&logo=ultralytics&logoColor=6C8EFF" alt="YOLO"/> <img src="https://img.shields.io/badge/scikit--learn-0B1120?style=for-the-badge&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn"/> <img src="https://img.shields.io/badge/Keras-0B1120?style=for-the-badge&logo=keras&logoColor=D00000" alt="Keras"/> <img src="https://img.shields.io/badge/Jupyter-0B1120?style=for-the-badge&logo=jupyter&logoColor=F37626" alt="Jupyter"/> <img src="https://img.shields.io/badge/LangGraph-0B1120?style=for-the-badge&logo=langchain&logoColor=7FD1C7" alt="LangGraph"/> <img src="https://img.shields.io/badge/ESP32-0B1120?style=for-the-badge&logo=espressif&logoColor=E7352C" alt="ESP32"/> <img src="https://img.shields.io/badge/Arduino-0B1120?style=for-the-badge&logo=arduino&logoColor=00979D" alt="Arduino"/> </p>

### Web & Product
<p> <img src="https://img.shields.io/badge/TypeScript-0B1120?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript"/> <img src="https://img.shields.io/badge/JavaScript-0B1120?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript"/> <img src="https://img.shields.io/badge/Angular-0B1120?style=for-the-badge&logo=angular&logoColor=DD0031" alt="Angular"/> <img src="https://img.shields.io/badge/React-0B1120?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/> <img src="https://img.shields.io/badge/Vue.js-0B1120?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" alt="Vue.js"/> <img src="https://img.shields.io/badge/Next.js-0B1120?style=for-the-badge&logo=nextdotjs&logoColor=FFFFFF" alt="Next.js"/> <img src="https://img.shields.io/badge/Node.js-0B1120?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E" alt="Node.js"/> <img src="https://img.shields.io/badge/Express-0B1120?style=for-the-badge&logo=express&logoColor=FFFFFF" alt="Express"/> <img src="https://img.shields.io/badge/Tailwind%20CSS-0B1120?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS"/> <img src="https://img.shields.io/badge/Firebase-0B1120?style=for-the-badge&logo=firebase&logoColor=FFCA28" alt="Firebase"/> <img src="https://img.shields.io/badge/FastAPI-0B1120?style=for-the-badge&logo=fastapi&logoColor=009688" alt="FastAPI"/> <img src="https://img.shields.io/badge/Flask-0B1120?style=for-the-badge&logo=flask&logoColor=FFFFFF" alt="Flask"/> </p>

### Backend & Data
<p> <img src="https://img.shields.io/badge/Java-0B1120?style=for-the-badge&logo=openjdk&logoColor=ED8B00" alt="Java"/> <img src="https://img.shields.io/badge/Spring%20Boot-0B1120?style=for-the-badge&logo=springboot&logoColor=6DB33F" alt="Spring Boot"/> <img src="https://img.shields.io/badge/Quarkus-0B1120?style=for-the-badge&logo=quarkus&logoColor=4695EB" alt="Quarkus"/> <img src="https://img.shields.io/badge/C%23-0B1120?style=for-the-badge&logo=dotnet&logoColor=9B4F96" alt="C#"/> <img src="https://img.shields.io/badge/PostgreSQL-0B1120?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Oracle-0B1120?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjRjgwMDAwIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+PGVsbGlwc2UgY3g9IjEyIiBjeT0iNSIgcng9IjkiIHJ5PSIzIi8+PHBhdGggZD0iTTMgNVYxOUE5IDMgMCAwIDAgMjEgMTlWNSIvPjxwYXRoIGQ9Ik0zIDEyQTkgMyAwIDAgMCAyMSAxMiIvPjwvc3ZnPg==" alt="Oracle"/> <img src="https://img.shields.io/badge/SQL%20Server-0B1120?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjQ0MyOTI3IiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+PGVsbGlwc2UgY3g9IjEyIiBjeT0iNSIgcng9IjkiIHJ5PSIzIi8+PHBhdGggZD0iTTMgNVYxOUE5IDMgMCAwIDAgMjEgMTlWNSIvPjxwYXRoIGQ9Ik0zIDEyQTkgMyAwIDAgMCAyMSAxMiIvPjwvc3ZnPg==" alt="SQL Server"/> <img src="https://img.shields.io/badge/MySQL-0B1120?style=for-the-badge&logo=mysql&logoColor=4479A1" alt="MySQL"/> <img src="https://img.shields.io/badge/Redis-0B1120?style=for-the-badge&logo=redis&logoColor=FF4438" alt="Redis"/> <img src="https://img.shields.io/badge/Neo4j-0B1120?style=for-the-badge&logo=neo4j&logoColor=4581C3" alt="Neo4j"/> <img src="https://img.shields.io/badge/RabbitMQ-0B1120?style=for-the-badge&logo=rabbitmq&logoColor=FF6600" alt="RabbitMQ"/> <img src="https://img.shields.io/badge/PocketBase-0B1120?style=for-the-badge&logo=pocketbase&logoColor=B8DBE4" alt="PocketBase"/> </p>

### Infrastructure & Tools
<p> <img src="https://img.shields.io/badge/Docker-0B1120?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker"/> <img src="https://img.shields.io/badge/Kubernetes-0B1120?style=for-the-badge&logo=kubernetes&logoColor=326CE5" alt="Kubernetes"/> <img src="https://img.shields.io/badge/nginx-0B1120?style=for-the-badge&logo=nginx&logoColor=009639" alt="nginx"/> <img src="https://img.shields.io/badge/GitHub%20Actions-0B1120?style=for-the-badge&logo=githubactions&logoColor=2088FF" alt="GitHub Actions"/> <img src="https://img.shields.io/badge/Proxmox-0B1120?style=for-the-badge&logo=proxmox&logoColor=E57000" alt="Proxmox"/> <img src="https://img.shields.io/badge/Tailscale-0B1120?style=for-the-badge&logo=tailscale&logoColor=FFFFFF" alt="Tailscale"/> <img src="https://img.shields.io/badge/Cloudflare-0B1120?style=for-the-badge&logo=cloudflare&logoColor=F38020" alt="Cloudflare"/> <img src="https://img.shields.io/badge/Arch%20Linux-0B1120?style=for-the-badge&logo=archlinux&logoColor=1793D1" alt="Arch Linux"/> <img src="https://img.shields.io/badge/Git-0B1120?style=for-the-badge&logo=git&logoColor=F05032" alt="Git"/> <img src="https://img.shields.io/badge/LaTeX-0B1120?style=for-the-badge&logo=latex&logoColor=008080" alt="LaTeX"/> <img src="https://img.shields.io/badge/Unity-0B1120?style=for-the-badge&logo=unity&logoColor=FFFFFF" alt="Unity"/> <img src="https://img.shields.io/badge/Android-0B1120?style=for-the-badge&logo=android&logoColor=3DDC84" alt="Android"/> <img src="https://img.shields.io/badge/C%2B%2B-0B1120?style=for-the-badge&logo=cplusplus&logoColor=00599C" alt="C++"/> </p>

<br>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/whiteherobot/whiteherobot/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/whiteherobot/whiteherobot/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/whiteherobot/whiteherobot/output/github-contribution-grid-snake.svg" />
</picture>

</div>
