# Eberlight Robotics

High-performance, modular automation infrastructure for synchrotron beamline sample handling and experimental robotics.

---

## 🔬 Core Platforms

### 1. TOM (Tomography Object Mounter)
* **Purpose:** Automated mobile robotic platform designed for high-throughput sample mounting, alignment, and retrieval across tomography beamlines.
* **Key Capabilities:** Asynchronous Caproto EPICS IOC integration, precise trajectory execution via `ur_rtde`, automated gripper management, and BlueSky/Ophyd framework compatibility.

### 2. CHAD (Crystallography Handler and Distributor)
* **Purpose:** Specialized robotic platform optimized for crystallography sample management and rapid sample-exchange cycles.
* **Key Capabilities:** Low-latency control loops, multi-mode beamline configuration support, integration with Arinax MD3 diffractometer, and rigorous state safety management.

---

### ⚙️ Technology Stack & Hardware

* **Control & Core Logic:** Python, `ur_rtde`, custom asynchronous state machines (`asyncio.Lock` serialization).
* **Communication & Protocols:** EPICS (Channel Access) via `caproto` and `pyepics`.
* **Automation Framework:** BlueSky & Ophyd client-side integration for data acquisition pipelines.
* **Operator Interface:** PyQt6 real-time monitoring and control dashboards.
* **Hardware — TOM System:** Universal Robots (UR5e), optical breadboards, specialized grippers/end-effectors, and custom sample adapters.
* **Hardware — CHAD System:** Universal Robots (UR5e/UR7e), Uni-Puck compatibility, specialized pin-handling end-effectors, LN2 dewar integration, and external safety interlocks. 

---

## 🔒 Access & Collaboration

Repositories under `eberlight-robotics` are private and maintained for beamline research and development. 

* **Read Access:** Granted to approved collaborators and beamline scientists.
* **Contributions:** Managed via feature branches and pull requests. For access requests or bug reports, please contact the repository administrator.
