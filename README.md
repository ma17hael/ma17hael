<div align="center">
  
# Ma17hae1

### Software Engineering Student · Junior Software Engineer · Systems Builder

**Designing modular software — from web platforms and infrastructure to operating systems and game engines.**

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mvinhais-chaves-vandemeulebrouck.com)

**Architecture-first · Modular by design · Built to evolve**

</div>

---

## About me

I'm **Ma17hae1**, a French software engineering student at **JUNIA ISEN Lille** and an junior software engineer at **Decathlon Digital**. I previously completed a **BTS SIO, SLAM specialization**.

I enjoy designing systems as much as implementing them. My work ranges from backend applications and reusable PHP libraries to Linux infrastructure, operating-system experiments, game-engine development and interactive worlds.

The common thread is **modularity**: clear boundaries, reusable components, explicit contracts, practical testing and architectures that can evolve without becoming unnecessarily complex.

> Understand the foundations. Design for evolution. Build with purpose.
> 
### At a glance

- **Current:** Engineering studies and software development apprenticeship (2026–present).
- **Primary interests:** Software architecture, backend engineering, systems programming and infrastructure.
- **Also exploring:** Data engineering, game development, technical education and distributed systems.
- **Approach:** Build a working foundation, validate it, then expand incrementally.

## Explore

[Skills](#technical-toolbox) · [Project families](#project-families) · [Independent](#independent-projects) · [Personal](#personal-projects) · [Academic](#academic-projects) · [Roadmap](#what-im-working-on) · [Contact](#connect)

---

## Technical toolbox

**Languages**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![C%23](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend and data**

![Composer](https://img.shields.io/badge/Composer-885630?style=flat-square&logo=composer&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Infrastructure and tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white) ![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)

**Engineering practices:** Object-oriented design · HTTP APIs · Middleware · Relational modeling · Database migrations · PHPUnit · PHPStan · PHP CS Fixer · Version control · Containerized development · Linux administration · Virtualization · SSH · Reverse proxies

> These technologies reflect a mix of hands-on experience, academic work and active learning; they do not imply the same proficiency level in every area.

---

## Project families

My projects are organized by **purpose**, not by programming language or maturity. Each family has its own presentation and each project keeps an independent development status.

| Family | Purpose | Browse |
|---|---|---|
| 🟦 **Independent projects** | Reusable software, products and solutions built for users or external adoption | [Explore](#independent-projects) |
| 🟪 **Personal projects** | Self-directed exploration, creative work and technical challenges | [Explore](#personal-projects) |
| 🟩 **Academic projects** | Coursework, practical assignments and learning outcomes | [Explore](#academic-projects) |

> **Category ≠ maturity.** A personal project can be released; an independent project can still be experimental. Professional apprenticeship work is not listed unless it is public and shareable.

---

## Independent projects

![Independent](https://img.shields.io/badge/INDEPENDENT-Products_%26_Reusable_Software-0284C7?style=for-the-badge&labelColor=0F172A)

Projects intended to provide value beyond my own learning: reusable libraries, application platforms and client-oriented solutions.

| Project | Focus | Status | Link |
|---|---|---|---|
| **Everfrost Core** | Reusable PHP foundation | Published | [Packagist](https://packagist.org/packages/everfrost/core) |
| **Everfrost Platform** | Modular web platform | In development | [Repository collection](https://github.com/orgs/Apprentissage-Cours-Stage/repositories) |
| **Everfrost Agent** | Infrastructure communication | Planned | — |
| **Amazing USA Canada** | Travel-map e-commerce | In development | [Portfolio](https://mvinhais-chaves-vandemeulebrouck.com) |
| **Multi-store platform** | Configurable e-commerce | In development / design | — |

<details>
<summary><b>Explore independent projects in detail</b></summary>
  
### Everfrost ecosystem
  
![Everfrost](https://img.shields.io/badge/EVERFROST-Modular_Software_Ecosystem-38BDF8?style=for-the-badge&labelColor=102A43)

**Everfrost** is a long-term initiative to build reusable software foundations and tools for application delivery, administration and infrastructure operations.

Its core architectural principle is to separate **what an environment can do** from **what commercial or application services require**.

```text
Infrastructure (shared hosting / VPS / other)
                     |
             Available capabilities
                     |
        Reusable contracts and modules
                     |
             Everfrost Platform
                     |
           Applications and services
```

#### Everfrost Core — published

A reusable PHP package containing shared domain concepts and foundational abstractions. Designed to remain independent of any specific client application or hosting provider.

- Capability-oriented infrastructure modeling.
- Shared contracts and domain foundations.
- Composer distribution and semantic versioning.
- Intended for reuse across multiple applications.

```bash
composer require everfrost/core
```

**Package:** [everfrost/core on Packagist](https://packagist.org/packages/everfrost/core)

#### Everfrost Platform — active development

A modular PHP application platform built incrementally around reusable application services.

**Implemented or tested foundations:** HTTP request/response abstractions, request factory, middleware pipeline, PDO-based database access, migration runner, migration version checks and automated tests.

**Application direction:** identity, project management, client administration, deployment workflows, backups, monitoring, audits and a client portal. These higher-level modules have different implementation statuses and are **not all finished**.

#### Everfrost Agent — planned

A potential infrastructure-side component for controlled communication with supported environments. Its available operations would depend on the actual capabilities and permissions of each host.

#### Architectural principles

- Prefer **capabilities over hard-coded hosting checks**.
- Keep the **Core** independent from application-specific features.
- Develop the **Platform** as a modular monolith rather than prematurely distributing everything.
- Separate domain logic, application orchestration and infrastructure adapters.
- Extend functionality through explicit contracts and testable modules.

---

#### Amazing USA Canada

A travel-map commerce platform offering different map formats, including free, classic and group-oriented roadtrip experiences. Its development has involved routing, authentication, permissions, validation, localization, file handling, catalog filtering, and Stripe/PayPal integration work.
The project helped shape the reusable application foundations later developed within Everfrost.

#### Multi-store e-commerce platform

A configurable commerce platform designed for multiple storefronts, shared application services, product discovery and store administration. Planned or developing integrations include payment providers and Mondial Relay shipping.

</details>

---
## Personal projects

![Personal](https://img.shields.io/badge/PERSONAL-Exploration_%26_Creation-7C3AED?style=for-the-badge&labelColor=0F172A)

Self-directed technical challenges, infrastructure experiments and creative projects.

| Project | Focus | Status |
|---|---|---|
| **Frosthold** | Homelab and server infrastructure | Active experimentation |
| **Northstar OS** | Custom x86-64 operating system | Early development |
| **Keystone Engine** | Modular C++ game engine | Early development |
| **Fantasy / Steampunk RPG** | Narrative and game-system design | Concept |

<details>
<summary><b>Explore personal projects in detail</b></summary>
  
### Frosthold

![Frosthold](https://img.shields.io/badge/FROSTHOLD-Infrastructure-64748B?style=for-the-badge&labelColor=0F172A)

**Frosthold** is my self-hosting and infrastructure laboratory. It combines a Proxmox-based homelab with Linux virtual machines and a remote Debian VPS.

**Practical areas:** virtualization, SSH key authentication, firewall rules, systemd services, remote access, reverse tunnels, service hosting and Minecraft server operations.

**Future direction:** centralized service visibility, monitoring, backups, deployment automation and potential integration with Everfrost.

Frosthold is both an operational environment and a place to learn by running real services.

---

### Northstar OS

![Northstar](https://img.shields.io/badge/NORTHSTAR_OS-x86--64_·_Rust-818CF8?style=for-the-badge&labelColor=111827)

**Northstar OS** is an experimental operating system developed from the ground up for **x86-64**, with Rust and low-level tools.

**Current work:** boot process, UEFI experimentation, toolchain configuration and execution/testing through QEMU. An initial boot environment has been successfully tested.

**Planned milestones:**

1. Boot and basic kernel initialization.
2. Memory management and interrupts.
3. Hardware abstractions and system interfaces.
4. Task management and increasingly capable user-facing components.

**Toolchain:** Rust · NASM · LLVM/Clang/LLD · QEMU · UEFI

**Target:** a first functional milestone during the 2026–2027 academic year. This is a development goal, not a completed release.

---

### Keystone Engine

![Keystone](https://img.shields.io/badge/KEYSTONE_ENGINE-C++_·_Graphics-F59E0B?style=for-the-badge&labelColor=1F2937)

**Keystone Engine** is a modular C++ game-engine project focused on understanding engine internals rather than depending entirely on an existing engine.

```text
Keystone
├── Foundation     Logging, assertions, result handling
├── Platform       Win32 windowing and OS integration
├── Input          Keyboard and mouse
├── Graphics       Direct3D 11 and rendering foundations
└── Future         Resources, scenes, audio, tools, physics
```

**Current progress:** foundational components, a Win32 window and basic input handling have been tested. The engine remains at an early stage.

---

### Original fantasy / steampunk RPG

An original game concept combining a Victorian-inspired world, magic, steampunk technology, player choices, branching narratives and an artificial guardian protagonist. Currently centered on worldbuilding and game-system design.

---

</details>

---

## Academic projects

![Academic](https://img.shields.io/badge/ACADEMIC-Coursework_%26_Practical_Labs-16A34A?style=for-the-badge&labelColor=0F172A)

Coursework is kept separate from independent products and personal experiments. It reflects specific learning objectives and may contain exercises rather than production-ready software.

| Program | Project types | Browse |
|---|---|---|
| **JUNIA ISEN Lille** | C programming, algorithms, engineering fundamentals and practical assignments | [Course repositories](https://github.com/orgs/Apprentissage-Cours-Stage/repositories) |
| **BTS SIO SLAM** | Application development, databases and software design | [Course repositories](https://github.com/orgs/Apprentissage-Cours-Stage/repositories) |

<details>
<summary><b>About my academic work</b></summary>
  
My academic repositories may contain programming exercises, laboratory work, course projects and experiments completed during my studies. Their scope, requirements and quality expectations differ from those of my independent software projects.
Specific assignments and repository links can be added here as they become publicly available.

</details>

---

## How I build software

```text
Problem → Requirements → Architecture → Minimal foundation
      → Tests → Incremental features → Documentation → Maintenance
```

I try to keep software architecture proportional to the problem. A reusable component should exist because it provides a useful boundary, not merely because it can be extracted.

Across projects, I prioritize:

- **Modularity:** cohesive components with clear responsibilities.
- **Reusability:** share stable foundations without coupling unrelated products.
- **Maintainability:** readable code, explicit interfaces and useful documentation.
- **Verification:** automated tests and static analysis where applicable.
- **Infrastructure awareness:** deployment choices must match actual hosting constraints.
- **Iteration:** deliver working milestones before expanding the scope.

---

## What I'm working on

| Area | Near-term direction |
|---|---|
| Everfrost | Extend Platform foundations and introduce application modules incrementally |
| Frosthold | Improve infrastructure management and service observability |
| Northstar OS | Advance from boot experiments toward core kernel functionality |
| Keystone Engine | Strengthen rendering and engine foundations |
| Professional growth | Continue engineering studies and apprenticeship experience |

**Interested in learning more about:** distributed systems, event-driven design, Kafka, CI/CD, observability, data engineering and advanced systems programming. These are exploration goals, not claims of production expertise.

---

## Beyond code

I also enjoy **teaching and explaining technical concepts**, organizing inclusive developer activities, designing game mechanics, and building fictional worlds. In the long term, I am interested in combining engineering practice with some form of computer-science education.

---

## Connect

<div align="center">
  
[![Portfolio](https://img.shields.io/badge/Portfolio-Explore-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mvinhais-chaves-vandemeulebrouck.com)
[![Everfrost Core](https://img.shields.io/badge/Everfrost_Core-Packagist-38BDF8?style=for-the-badge&logo=packagist&logoColor=white)](https://packagist.org/packages/everfrost/core)

**Software Engineering · Modular Architecture · Infrastructure · Systems Programming**

</div>
<!-- MAINTENANCE NOTES (not displayed on GitHub)
1. Replace project collection links with exact public repository URLs when confirmed.
2. Add a GitHub stats card only after confirming the correct GitHub account username.
3. Each public project should have its own README with: overview, status, architecture,
   requirements, installation, usage, testing, roadmap, license and contribution policy.
4. Update the project maturity table when a milestone is released.
5. Optional branded SVG banners can be stored in assets/ and referenced locally.
-->
