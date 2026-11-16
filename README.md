# 🎓 Epitech Projects — Lucas Lhomme (Crabe)

> **Curated umbrella catalog of 42 open-source computer science projects developed during my curriculum at [Epitech](https://www.epitech.eu/) (European Institute of Information Technology), organized by academic year (Tek1, Tek2, Tek3).**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Submodules](https://img.shields.io/badge/Git-Submodules-orange.svg)](#project-structure)
[![Projects](https://img.shields.io/badge/Projects-42%20Repositories-brightgreen.svg)](#projects-overview)
[![School](https://img.shields.io/badge/School-Epitech-005696.svg)](https://www.epitech.eu/)

---

## 📂 Project Structure

All projects are organized by academic year as independent Git submodules tracking their respective branches:

```text
Epitech-Projects/
├── tek1/                              # First Year — C Programming, Algorithms, Systems & DevOps (27 projects)
│   ├── 42sh/                          # Complete Unix shell in C (fix_main)
│   ├── Secured/                       # High-performance hash table library in C
│   ├── EpyTodo/                       # Full-stack Web Todo application (Node.js/MySQL)
│   ├── Popeye/                        # Container orchestration with Docker Swarm
│   ├── amazed/                        # Graph pathfinding & maze flow solver in C
│   ├── corewar/                       # Virtual Machine & arena for concurrent champion bytecode
│   ├── robotfactory/                  # Corewar assembler compiling .s into .cor bytecode
│   ├── cworkshoplib/                  # Foundational C library (Piscine / C Workshop)
│   ├── countisland/                   # Connected-component labeling on 2D grids in C
│   ├── star/                          # Procedural geometric ASCII star generator
│   ├── rush1/                         # Geometric ASCII pattern & frame renderer
│   ├── rush2/                         # Natural language detection via letter frequency analysis
│   ├── miniprintf/                    # Lightweight formatted output printer
│   ├── myprintf/                      # Full-featured printf formatting engine in C
│   ├── settingup/                     # Maximal obstacle-free square solver (Dynamic Programming)
│   ├── organized/                     # Hardware inventory manager using doubly linked lists
│   ├── myls/                          # Unix directory listing utility (ls) in C
│   ├── mysudo/                        # Unix privilege escalation tool (sudo) in C
│   ├── mytop/                         # Interactive system monitor in C with NCurses
│   ├── minishell1/                    # Unix command shell with environment & built-ins
│   ├── minishell2/                    # Unix shell with pipelines (|) and file redirections (<, >, >>)
│   ├── myhunter/                      # 2D arcade shooting game in C using CSFML
│   ├── myradar/                       # 2D air traffic control radar & collision simulator in CSFML
│   ├── burp/                          # Web penetration testing & vulnerability assessment lab
│   ├── pipeto/                        # Binary exploitation & security auditing challenges
│   ├── cuddle/                        # Tabular CSV manipulation library (Pandas-like) in C
│   └── chocolatine/                   # Automated CI/CD pipeline workflow with GitHub Actions
│
├── tek2/                              # Second Year — Advanced C++, DevOps, Networks & AI (11 projects)
│   ├── arcade/                        # Modular gaming platform with dynamic .so plugins
│   ├── nanotekspice/                  # Digital logic simulator in C++20
│   ├── raytracer/                     # 3D Ray tracing engine in C++20
│   ├── myteams/                       # Client/server RFC collaborative messaging in C++
│   ├── zappy/                         # Network multiplayer game with autonomous AI & GUI
│   ├── panoramix/                     # Concurrent programming with POSIX threads & mutexes
│   ├── mymarvin/                      # CI/CD automation with Jenkins, Job DSL & Docker
│   ├── octopus/                       # Infrastructure as Code with Ansible (5-node VM cluster)
│   ├── starttrek/                     # Deep Reinforcement Learning (DQN/PPO) on LunarLander
│   ├── codename/                      # LLM security & prompt injection evaluation
│   └── persona/                       # Automated news aggregator with n8n & Google Gemini
│
└── tek3/                              # Third Year — Advanced AI, Kubernetes & Cloud Systems (4 projects)
    ├── mytorch/                       # Neural Network from scratch in Python (NumPy only)
    ├── sensai/                        # Agentic AI assistant & tactical simulation engine
    ├── bernstein/                     # Kubernetes orchestration with HPA & Zero-Downtime updates
    └── dashboard/                     # INTER-NET: Modular distributed dashboard with microservices
```

---

## 📦 Projects Overview

### 🔹 Tek 1 (First Year — 27 Projects)

| Project | Repository | Tech Stack | Description |
| :--- | :--- | :--- | :--- |
| **42sh** | [`tek1/42sh`](https://github.com/LucasLhomme/42sh) | C | Full-featured Unix shell implementing command execution, pipes, redirections, built-ins, and line edition. |
| **Secured** | [`tek1/Secured`](https://github.com/LucasLhomme/Secured) | C | High-performance hash table library with collision handling and custom hashing algorithms. |
| **EpyTodo** | [`tek1/EpyTodo`](https://github.com/LucasLhomme/EpyTodo) | Node.js / MySQL | Web API and service for task management and user authentication. |
| **Popeye** | [`tek1/Popeye`](https://github.com/LucasLhomme/Popeye) | Docker / Swarm | Multi-container application orchestrator and service deployment using Docker Compose & Docker Swarm. |
| **Amazed** | [`tek1/amazed`](https://github.com/LucasLhomme/amazed) | C | Graph pathfinding & network flow simulation moving robotic avatars through mazes with optimal paths. |
| **Corewar** | [`tek1/corewar`](https://github.com/LucasLhomme/corewar) | C | Circular memory virtual machine arena where concurrent bytecode champions compete for execution space. |
| **Robot Factory** | [`tek1/robotfactory`](https://github.com/LucasLhomme/robotfactory) | C | Assembler compiler encoding `.s` assembly source code into `.cor` Corewar bytecode binaries. |
| **CWorkshopLib** | [`tek1/cworkshoplib`](https://github.com/LucasLhomme/cworkshoplib) | C | Foundational standard C library replicating essential POSIX and libc routines. |
| **Count Island** | [`tek1/countisland`](https://github.com/LucasLhomme/countisland) | C | Connected-component labeling algorithm identifying and counting contiguous landmasses on 2D maps. |
| **Star** | [`tek1/star`](https://github.com/LucasLhomme/star) | C | Geometric ASCII star pattern generator rendering a symmetric 6-pointed star. |
| **Rush 1** | [`tek1/rush1`](https://github.com/LucasLhomme/rush1) | C | Procedural 2D ASCII box and frame renderer with configurable borders. |
| **Rush 2** | [`tek1/rush2`](https://github.com/LucasLhomme/rush2) | C | Natural language prediction algorithm using letter frequency cryptanalysis. |
| **MiniPrintf** | [`tek1/miniprintf`](https://github.com/LucasLhomme/miniprintf) | C | Minimalist formatted string output printer using `stdarg.h` variadic arguments. |
| **MyPrintf** | [`tek1/myprintf`](https://github.com/LucasLhomme/myprintf) | C | Complete formatted printing engine supporting flags, field width, precision, and all standard format specifiers. |
| **Setting Up** | [`tek1/settingup`](https://github.com/LucasLhomme/settingup) | C | Dynamic programming algorithm solving the maximal obstacle-free square on 2D grids. |
| **Organized** | [`tek1/organized`](https://github.com/LucasLhomme/organized) | C | Hardware inventory manager implementing sorted linked lists and dynamic element manipulation. |
| **MyLS** | [`tek1/myls`](https://github.com/LucasLhomme/myls) | C | Reimplementation of the Unix `ls` command with `-l`, `-a`, `-R`, `-d`, `-r`, `-t` flags. |
| **MySudo** | [`tek1/mysudo`](https://github.com/LucasLhomme/mysudo) | C | Unix privilege escalation tool validating credentials and executing commands under elevated privileges. |
| **MyTop** | [`tek1/mytop`](https://github.com/LucasLhomme/mytop) | C / NCurses | Terminal process monitor parsing Linux `/proc` to display real-time CPU, RAM, and task statistics. |
| **Minishell 1** | [`tek1/minishell1`](https://github.com/LucasLhomme/minishell1) | C | Unix command shell implementing process execution via `execve`, PATH resolution, and built-ins. |
| **Minishell 2** | [`tek1/minishell2`](https://github.com/LucasLhomme/minishell2) | C | Extended Unix shell adding inter-process pipelines (`|`) and file redirections (`<`, `>`, `>>`). |
| **MyHunter** | [`tek1/myhunter`](https://github.com/LucasLhomme/myhunter) | C / CSFML | 2D target shooting arcade game inspired by Duck Hunt with animated sprites and custom crosshair. |
| **MyRadar** | [`tek1/myradar`](https://github.com/LucasLhomme/myradar) | C / CSFML | 2D air traffic control radar and aircraft collision simulation with control tower safety zones. |
| **Burp** | [`tek1/burp`](https://github.com/LucasLhomme/burp) | Security / Web | Practical penetration testing workshop using Burp Suite to audit OWASP Top 10 vulnerabilities. |
| **Pipeto** | [`tek1/pipeto`](https://github.com/LucasLhomme/pipeto) | C / Security | Binary exploitation and pipeline security challenge evaluating vulnerable inputs and protections. |
| **Cuddle** | [`tek1/cuddle`](https://github.com/LucasLhomme/cuddle) | C | Tabular data and CSV manipulation library providing Pandas-like DataFrame routines. |
| **Chocolatine** | [`tek1/chocolatine`](https://github.com/LucasLhomme/chocolatine) | GitHub Actions | Automated CI/CD pipeline running coding-style validation, compilation tests, and mirror deployment. |

---

### 🔹 Tek 2 (Second Year — 11 Projects)

| Project | Repository | Tech Stack | Description |
| :--- | :--- | :--- | :--- |
| **Arcade** | [`tek2/arcade`](https://github.com/LucasLhomme/arcade) | C++17 | Modular gaming platform featuring hot-swappable graphic libraries (`SFML`, `SDL2`, `ncurses`) and interchangeable games. |
| **NanoTekSpice** | [`tek2/nanotekspice`](https://github.com/LucasLhomme/nanotekspice) | C++20 | Digital logic simulator modelling 4000-series CMOS chips, tri-state logic, and component graphs. |
| **Raytracer** | [`tek2/raytracer`](https://github.com/LucasLhomme/raytracer) | C++20 | 3D Ray tracing rendering engine supporting mathematical primitives, materials, lighting, and dynamic plugins. |
| **MyTeams** | [`tek2/myteams`](https://github.com/LucasLhomme/myteams) | C++ | Collaborative communication protocol & multi-client server implementing teams, channels, private messages, and persistence. |
| **Zappy** | [`tek2/zappy`](https://github.com/LucasLhomme/zappy) | C / Python / SFML | End-of-year multi-system project: TCP server in C, autonomous AI agents in Python, and graphical spectator client. |
| **Panoramix** | [`tek2/panoramix`](https://github.com/LucasLhomme/panoramix) | C | Multi-threaded synchronization solver (producers/consumers, sleeping villagers) using POSIX threads and semaphores. |
| **MyMarvin** | [`tek2/mymarvin`](https://github.com/LucasLhomme/mymarvin) | Jenkins / Groovy / Docker | Automated CI/CD pipeline generated using Jenkins Job DSL for automated linting, unit testing, and compilation. |
| **Octopus** | [`tek2/octopus`](https://github.com/LucasLhomme/octopus) | Ansible / Linux | Multi-tier infrastructure deployment across a cluster of 5 virtual machines using Ansible playbooks. |
| **StartTrek** | [`tek2/starttrek`](https://github.com/LucasLhomme/starttrek) | Python / PyTorch / Gym | Autonomous spaceship lander using Deep Reinforcement Learning (DQN and PPO algorithms). |
| **Codename** | [`tek2/codename`](https://github.com/LucasLhomme/codename) | Python / LLMs | Offensive and defensive prompt injection engineering, jailbreak testing, and safety guardrails. |
| **Persona** | [`tek2/persona`](https://github.com/LucasLhomme/persona) | n8n / Docker / PostgreSQL / Gemini | Automated personalized newsletter & news intelligence pipeline powered by Google Gemini and n8n orchestration. |

---

### 🔹 Tek 3 (Third Year — 4 Projects)

| Project | Repository | Tech Stack | Description |
| :--- | :--- | :--- | :--- |
| **MyTorch** | [`tek3/mytorch`](https://github.com/LucasLhomme/mytorch) | Python / NumPy | Deep learning & neural network implementation built from scratch without high-level ML frameworks to classify chess FEN positions into check/checkmate states. |
| **SensAI** | [`tek3/sensai`](https://github.com/LucasLhomme/sensai) | Python / FastAPI / React / SQLite | Modular agentic AI assistant & tactical simulation engine in ancient China with RAG, semantic caching, and human-in-the-loop validation. |
| **Bernstein** | [`tek3/bernstein`](https://github.com/LucasLhomme/bernstein) | Kubernetes / Docker / Redis / Postgres | Production-grade Kubernetes orchestration of a distributed voting application featuring HPA autoscaling, zero-downtime rolling updates, and PodDisruptionBudgets. |
| **Dashboard** | [`tek3/dashboard`](https://github.com/LucasLhomme/dashboard) | FastAPI / React 19 / Redis / MySQL / Docker | INTER-NET: Modular distributed dashboard with microservices architecture, multi-service OAuth2 widgets, and real-time data refreshing. |

---

## 🚀 Getting Started

### 1. Clone with All Submodules

To clone this repository and download all 42 projects with their complete source code:

```bash
git clone --recurse-submodules https://github.com/LucasLhomme/Epitech-Projects.git
cd Epitech-Projects
```

*(If you already cloned without `--recurse-submodules`, initialize all submodules by running `git submodule update --init --recursive`)*.

### 2. Fast-Forward All Projects to Latest Upstream

All submodules are configured to track their remote branches (`fix_main` for 42sh, `master` for myhunter, `main` for all others). To sync all projects:

```bash
git submodule update --remote --merge
```

### 3. Work on a Specific Project

Each folder is a fully autonomous Git repository:

```bash
cd tek1/myprintf
git checkout main
# Build or run tests directly inside the project
```

---

## 🔄 Automated Submodule Sync

This repository features a scheduled [GitHub Action](.github/workflows/update-submodules.yml) running daily to automatically detect upstream commits on all projects and fast-forward submodule references.

---

## 📜 License & Academic Integrity

- **License:** All repositories are open-source under the **MIT License with mandatory attribution**.
- **Attribution:** If you reference or utilize any code, you must include explicit credit to **Lucas Lhomme (Crabe)**.
- **Academic Disclaimer:** This repository is intended for educational and archival purposes. Epitech students must abide by the school's **Code of Conduct and Anti-Plagiarism Policy**. Do not submit this code as your own coursework.
