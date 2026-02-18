# Faez Barghasa

**CTO · Embedded Systems Architect · Rust Engineer**

> *Building reliable, high-performance systems from bare silicon to cloud — solo or at scale.*

---

## About Me

I'm a self-directed systems engineer based in **Karaj, Iran**, currently serving as **CTO at Micromed** — where I own the full technical stack: schematic design, PCB layout, bare-metal firmware, embedded Linux, backend services, and desktop UI.

My core belief: **performance and correctness are not tradeoffs** — Rust proves it every day.

I've spent 5+ years going deep on the Rust ecosystem, from `no_std` bare-metal firmware on STM32 and ESP32, to async networked services with `actix-web`, to studying the internals of the [Redox OS](https://www.redox-os.org/) microkernel — kernel, `relibc`, `redoxfs`, `netstack`, `ion`, `init`, `ipcd`, `zerod`, and the full driver model.

When I'm not building, I'm teaching — Rust programming, computer architecture, and low-level systems to students and professionals.

---

## 🛠 Technical Stack

### Languages

![Rust](https://img.shields.io/badge/Rust-Expert%205%2B%20yrs-000000?style=flat&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-Embedded-00599C?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-ML%20%26%20Tooling-3776AB?style=flat&logo=python&logoColor=white)

### Embedded & Hardware

![Embassy](https://img.shields.io/badge/Embassy-Async%20Embedded-6B3FA0?style=flat)
![embedded-hal](https://img.shields.io/badge/embedded--hal-Driver%20Dev-orange?style=flat)
![STM32](https://img.shields.io/badge/STM32-Bare%20Metal-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-WiFi%20%2F%20MQTT-E7352C?style=flat&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi%205-Embedded%20Linux-A22846?style=flat&logo=raspberrypi&logoColor=white)
![Altium](https://img.shields.io/badge/Altium%20Designer-PCB%20Design-A5915F?style=flat)

### Networking & Protocols

![MQTT](https://img.shields.io/badge/MQTT%20v5-Async%20%2F%20no__std-660066?style=flat)
![smoltcp](https://img.shields.io/badge/smoltcp-Userspace%20TCP%2FIP-005f87?style=flat)

### Backend & UI

![actix-web](https://img.shields.io/badge/actix--web-Rust%20Backend-orange?style=flat)
![SurrealDB](https://img.shields.io/badge/SurrealDB-Database-FF00A0?style=flat&logo=surrealdb&logoColor=white)
![Slint](https://img.shields.io/badge/Slint-Embedded%20UI%2060fps-2379F4?style=flat)
![Tauri](https://img.shields.io/badge/Tauri-Desktop%20Apps-FFC131?style=flat&logo=tauri&logoColor=black)

### AI / ML

![Deep Learning](https://img.shields.io/badge/Deep%20Learning-RNN%20%2F%20DeepAR-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-LLM%20Tooling-412991?style=flat&logo=openai&logoColor=white)

---

## 🚀 Current & Featured Projects

### [`mqtt-async-embedded`](https://github.com/FaezBarghasa/mqtt-async-embedded)

A `no_std` asynchronous MQTT v5 client for embedded Rust — fully heap-free, built on stack-based state machines. Designed for bare-metal STM32 and ESP32 deployments where reliability and low memory footprint are non-negotiable.

### Thermal Controller Board *(Micromed — Commercial)*

Safety-critical temperature controller for medical and laboratory equipment: ovens, incubators, bain-marie, and autoclaves. Custom PID/IMC control loop in Rust on STM32 with WiFi/MQTT telemetry. Full multi-layer PCB designed in Altium Designer.

### CO₂ Incubator HMI *(Micromed — Deployed in Clinical Lab)*

Production-deployed HMI for a CO₂ laboratory incubator. Single Rust + Slint codebase targeting both Raspberry Pi 5 (Embedded Linux) and ESP32 with LCD — achieving stable 60FPS on constrained hardware. Currently live in a clinical research environment.

### Online Data Logger *(Micromed — Commercial)*

Full-stack IoT pipeline: ESP32 firmware → Rust/actix-web cloud backend → Android app. Real-time sensor data ingestion, storage with SurrealDB, and mobile dashboard — designed and shipped solo.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=FaezBarghasa&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&title_color=1B4F72&icon_color=2E86C1&text_color=4A4A4A&bg_color=F8FBFF" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FaezBarghasa&layout=compact&hide_border=true&title_color=1B4F72&text_color=4A4A4A&bg_color=F8FBFF&langs_count=6" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=FaezBarghasa&hide_border=true&ring=1B4F72&fire=2E86C1&currStreakLabel=1B4F72&sideLabels=4A4A4A&dates=888888" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=FaezBarghasa&theme=flat&no-frame=true&column=6&margin-w=8" />
</p>

---

## 🔬 OS Internals Study — Redox OS

I've done a deep independent study of the [Redox OS](https://gitlab.redox-os.org/redox-os) codebase — a microkernel OS written entirely in Rust. Subsystems covered:

| Subsystem | Focus Area |
|---|---|
| `kernel` | Microkernel architecture, paging, syscalls, process scheduling |
| `redox-rmm` | Physical memory manager, x86_64 page table structures |
| `relibc` | POSIX C standard library in Rust — fork, exec, signals |
| `redoxfs` | Filesystem implementation |
| `netstack` | Userspace network stack |
| `ion` | Shell and scripting language implementation |
| `init` / `ipcd` / `zerod` | System init, IPC daemon, zero-copy service patterns |
| `drivers` / `cookbook` | Driver model and package build system |

---

## 📚 Teaching & Mentorship

I've taught the following to students and professionals:

- **Rust Programming** — from fundamentals to systems-level development
- **Computer Architecture & Low-Level Programming** — memory models, instruction sets, hardware-software interface
- **Computer Basics** — fundamentals for teenage learners
- **Prompt Engineering** — LLM tooling, multi-step chain design, structured output engineering

I believe the best way to deeply understand a system is to explain it to someone else.

---

## 🎓 Background

- **Data Science & Deep Learning** — Coursera / DeepLearning.AI (2018–2021)
  - Neural Networks, CNNs, RNNs, Sequence Models
  - Applied: DeepAR probabilistic forecasting for time-series volatility modeling
- **Self-directed systems engineering** — ongoing since 2018
  - Kernel internals, embedded systems, hardware design, Rust ecosystem

---

## � Open To

### Engineering Roles

- **Senior / Lead embedded systems roles** in Tehran (on-site)
- **Remote-first engineering or technical leadership** roles globally
- **Technical co-founder** conversations for hardware+software product startups
- Consulting on **embedded Rust**, **PCB design**, or **IoT system architecture**

### Teaching & Training

- **Rust Programming** — from fundamentals to advanced systems-level Rust, for individuals or teams
- **Embedded Rust** — bare-metal, Embassy async, embedded-hal, no_std — from first blink to production firmware
- **Embedded Project Development** — full lifecycle: concept → schematic → PCB → firmware → deployment
- **R&D & Research Guidance** — technical direction for hardware/software research projects
- **Product & Market Positioning** — bridging the gap between embedded R&D and real-world product/market fit

Available for **workshops, bootcamps, one-on-one mentorship, or team training programs** — online or in-person (Tehran / Karaj area).

📧 <faez.barghasa.org@gmail.com>
📱 +98 935 508 5393

---

*"The goal is not to write code that works. The goal is to write code that cannot fail."*
