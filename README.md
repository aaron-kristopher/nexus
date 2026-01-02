# ⚡ Nexus

**Nexus** is a zero-dependency local infrastructure CLI written in **Pure Bash**.
This project is primarily for **learning and exploration** — digging into Linux kernel metrics, process management, and building interactive Terminal User Interfaces (TUI) without external libraries.

---

## ✨ Features Implemented

* ✅ **Interactive System Dashboard** (`nexus status`)
* Real-time RAM and Disk usage visualization
* Docker container status tracking
* CPU Load Average parsing directly from `/proc/loadavg`


* ✅ **Service Controller** (`nexus service`)
* Hardware-level toggle for Bluetooth (Systemd + RFKill integration)
* Service management for Docker and other daemons
* **MVC Architecture** (Model-View-Controller) implementation in Bash



---

## 📝 Roadmap / TODO

* [ ] **Asset Pipeline** (`nexus compress`) - Image optimization wrapper around FFmpeg
* [ ] **Port Manager** (`nexus free`) - Identify and kill zombie processes on specific ports
* [ ] **HTTP Server** (`nexus serve`) - Pure Bash web server using `/dev/tcp`
* [ ] **Project Scaffolder** (`nexus new`) - Automate Python/Bash project setup

---

## ⚙️ Tech Stack

* **Language:** Bash (Shell Scripting)
* **Core Utils:** `awk`, `sed`, `grep`, `systemctl`, `rfkill`
* **UI Library:** `tput` (Native terminal capabilities)

```bash
bash --version
GNU bash, version 5.0.17(1)-release (x86_64-pc-linux-gnu)

```

---

## 🚀 Build & Run

Clone and make the script executable:

```bash
git clone https://github.com/yourusername/nexus.git
cd nexus
chmod +x nexus
./nexus status

```

**Usage:**

```bash
nexus status              # Open the TUI Dashboard
nexus service [bt|docker] # Open the TUI Service Controller
nexus help                # Show help menu

```

---

## 📚 Learning Goals

Nexus is not just a script — it’s a journey into:

* The design of **Linux Systems Engineering** (Signals, Filesystems, Processes)
* How to parse **Kernel Metrics** manually without heavy monitoring agents
* Building **MVC patterns** and complex logic in Shell scripting
* Practicing **SRE (Site Reliability Engineering)** workflows ✨

---

## 🏗️ Project Status

Nexus is currently in **active development** — the focus is on expanding the modular "driver" system and implementing the asset optimization pipeline.
