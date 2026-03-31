# Alfayez Ahmad

**CS Undergraduate, Integral University (9.55/10 CGPA) | Applied Computer Vision, Network Security & Robotics**
Building low-level systems, bridging them with machine learning, and containerizing them for edge deployment. 

---

### Featured Engineering Projects

#### [Global Graph PoC: Spherical Weather Mesh](https://github.com/alfayezahmad/neural-lam-global-graph-poc)
**Stack:** Python, PyTorch Geometric (PyG), SciPy (cKDTree)
A proof-of-concept pipeline built for my Google Summer of Code (GSoC) 2026 proposal to transition the `neural-lam` weather model to global forecasting.
- Constructs a boundary-free 3D spherical mesh using a Fibonacci lattice to eliminate the polar distortion inherent in standard latitude/longitude grids.
- Implements spatial edge routing via `cKDTree` and packages the topology into PyG `Data` objects for seamless integration with the existing ARModel message-passing layers.

#### [Ideal-Sniffle: PM2.5 Air Quality Forecasting](https://github.com/alfayezahmad/ideal-sniffle)
**Stack:** Python, Scikit-Learn, Pandas, Time-Series Analysis
A predictive machine learning engine forecasting daily PM2.5 levels.
- Engineered lag and rolling features to capture temporal patterns from Central Pollution Control Board (CPCB) data.
- Automates classification of AQI levels to provide data-driven public health advisories.

#### [Autonomous Warehouse Perception System](https://github.com/alfayezahmad/warehouse-vision-sam2)
**Stack:** Python, Meta SAM 2, OpenCV, SQLite, Docker
A containerized, hybrid computer vision pipeline integrating SAM 2 and OpenCV to handle foundation model failures.
- Built a deterministic logic layer to track distinct "islands" and maintain ID persistence when objects fragment in segmentation masks.
- Integrated an SQL telemetry backend for automated incident logging, engineered for edge-node deployment and observability.

#### [Sentinela: ML Network Intrusion Detection](https://github.com/alfayezahmad/Sentinela-AI-NIDS)
**Stack:** Python, Scapy, Scikit-Learn (Random Forest), Docker
A custom packet-sniffing engine built to categorize network traffic anomalies in real-time.
- Bridges low-level packet ingestion in promiscuous mode with a Random Forest classifier to identify normal vs. attack traffic.
- Deployed as an isolated Docker container leveraging Linux host-networking (`NET_RAW`, `NET_ADMIN`) capabilities.

#### [Quadcopter-Sim-V1: Autonomous Flight Pipeline](https://github.com/alfayezahmad/Quadcopter-Sim-V1)
**Stack:** Python, Control Theory (PID/Kalman), Docker
A 1D Digital Twin and Software-in-the-Loop (SITL) flight engine.
- Stemming from my first foundational hardware drone build in 2022, this implements a recursive Bayesian filter (Kalman) for state estimation and a custom Domain-Specific Language (DSL) parser for mission logic.
- Containerized for headless execution to support parallelized Monte Carlo testing of flight control algorithms.

---

### Publications & Research

* **IEEE IMPACT 2026:** Presented research on Reinforcement Learning for Variable Speed Limit systems (Accepted for IEEE Xplore).

---

### Technical Toolkit & R&D

**Core Technologies**
* **Languages:** Python, C/C++, Java, SQL, Bash
* **Vision & AI:** Meta SAM 2, OpenCV, Random Forest, Scikit-Learn
* **Cloud-Native & DevOps:** Docker, Linux/Unix internals, Git, SQLite
* **Robotics & Control:** ROS 2, Kalman Filters, PID, Bare-Metal C (STM32)

**Current Engineering Focus & R&D:**
* **Cloud-Native & Distributed Systems:** Transitioning standalone ML and robotics containers into distributed Kubernetes workloads (DaemonSets, Jobs) for scalable observability and Monte Carlo testing.
* **Embedded Control:** Porting software-in-the-loop flight algorithms to bare-metal C for STM32 (Cortex-M3) microcontrollers.
* **Systems Architecture & Security:** Deep-diving into OS internals, memory-optimized C data structures, and expanding real-time network packet inspection techniques via eBPF.

---

### Connect
**Reach out & Connect:**
[Email](mailto:alfayezahmad.aa@gmail.com) ｜ [LinkedIn](https://www.linkedin.com/in/alfayezahmad) ｜ [Kaggle](https://www.kaggle.com/alfayezahmad)
