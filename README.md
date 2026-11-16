# 🎓 Epitech Projects — Lucas Lhomme (Crabe)

> **Curated umbrella catalog of open-source computer science projects developed during my curriculum at [Epitech](https://www.epitech.eu/) (European Institute of Information Technology), organized by academic year (Tek1, Tek2, Tek3).**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Submodules](https://img.shields.io/badge/Git-Submodules-orange.svg)](#project-structure)
[![School](https://img.shields.io/badge/School-Epitech-005696.svg)](https://www.epitech.eu/)

---

## 📂 Project Structure

All projects are organized by year of study as independent Git submodules tracking their respective branches:

```text
Epitech-Projects/
├── tek1/                              # First Year — Foundations & C Systems
│   ├── 42sh/                          # Complete Unix shell in C
│   ├── Secured/                       # Hash table library in C
│   └── EpyTodo/                       # Full-stack Web Todo application
│
├── tek2/                              # Second Year — Advanced C++, DevOps, Networks & AI
│   ├── arcade/                        # Modular gaming platform with dynamic .so plugins
│   ├── nanotekspice/                  # Digital logic simulator in C++20
│   ├── raytracer/                     # 3D Ray tracing engine in C++
│   ├── myteams/                       # Client/server RFC collaborative messaging in C++
│   ├── zappy/                         # Network multiplayer game with autonomous AI & GUI
│   ├── panoramix/                     # Concurrent programming with POSIX threads & mutexes
│   ├── mymarvin/                      # CI/CD automation with Jenkins, Job DSL & Docker
│   ├── octopus/                       # Infrastructure as Code with Ansible (5-node VM cluster)
│   ├── Popeye/                        # Container orchestration with Docker Swarm
│   └── starttrek/                     # Deep Reinforcement Learning (DQN/PPO) on LunarLander
│
└── tek3/                              # Third Year — LLMs, Cloud & AI Engineering
    ├── codename/                      # LLM security & prompt injection evaluation
    └── persona/                       # Automated news aggregator with n8n & Google Gemini
```

---

## 📦 Projects Overview

### 🔹 Tek 1 (First Year)

| Project | Repository | Tech Stack | Description |
| :--- | :--- | :--- | :--- |
| **42sh** | [`tek1/42sh`](https://github.com/LucasLhomme/42sh) | C | Full-featured Unix shell implementing command execution, pipes, redirections, built-ins, and line edition. |
| **Secured** | [`tek1/Secured`](https://github.com/LucasLhomme/Secured) | C | High-performance hash table library with collision handling and custom hashing algorithms. |
| **EpyTodo** | [`tek1/EpyTodo`](https://github.com/LucasLhomme/EpyTodo) | JavaScript / Node.js / MySQL | Web API and service for task management and user authentication. |

---

### 🔹 Tek 2 (Second Year)

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
| **Popeye** | [`tek2/Popeye`](https://github.com/LucasLhomme/Popeye) | Docker / Swarm | Multi-container application orchestrator and service deployment using Docker Compose & Docker Swarm. |
| **StartTrek** | [`tek2/starttrek`](https://github.com/LucasLhomme/starttrek) | Python / PyTorch / Gym | Autonomous spaceship lander using Deep Reinforcement Learning (DQN and PPO algorithms). |

---

### 🔹 Tek 3 (Third Year)

| Project | Repository | Tech Stack | Description |
| :--- | :--- | :--- | :--- |
| **Codename** | [`tek3/codename`](https://github.com/LucasLhomme/codename) | Python / LLMs | Offensive and defensive prompt injection engineering, jailbreak testing, and safety guardrails. |
| **Persona** | [`tek3/persona`](https://github.com/LucasLhomme/persona) | n8n / Docker / PostgreSQL / Gemini | Automated personalized newsletter & news intelligence pipeline powered by Google Gemini and n8n orchestration. |

---

## 🚀 Getting Started

### 1. Clone with All Submodules

To clone this repository and download all projects with their complete source code:

```bash
git clone --recurse-submodules https://github.com/LucasLhomme/Epitech-Projects.git
cd Epitech-Projects
```

*(If you already cloned without `--recurse-submodules`, initialize all submodules by running `git submodule update --init --recursive`)*.

### 2. Fast-Forward All Projects to Latest Upstream

All submodules are configured to track their remote branches (`fix_main` for 42sh, `main` for all others). To sync all projects:

```bash
git submodule update --remote --merge
```

### 3. Work on a Specific Project

Each folder is a fully autonomous Git repository:

```bash
cd tek2/nanotekspice
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
