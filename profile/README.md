<div align="center">
  <img src="assets/dhack-logo.png" alt="D-Hack1 Logo" width="140" />

  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:C62828,100:1a1a1a&height=120&section=header&text=D-HACK1&fontSize=56&fontColor=ffffff&fontAlignY=62&desc=Award-Winning%20Hackathon%20Portfolio%20%26%20Product%20Incubator&descAlignY=85&descSize=16" width="100%" alt="D-Hack1" />

  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
  [![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)](#)
  [![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](#)
  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](#)

  [![Static Badge](https://img.shields.io/badge/GitHub-Org-181717?style=for-the-badge&logo=github)](https://github.com/D-Hack1)
</div>

---

### ▸ About Us
D-Hack1 is a diverse portfolio of hackathon projects, Minimum Viable Products (MVPs), and technical prototypes. Our work spans multiple domains including banking security, AI/data products, renewable energy, public safety, and mobile utilities. We focus on building highly technical, problem-solving architectures — from on-device edge AI to massive gigapixel data pipelines.

---

### ▸ Hall of Fame

<table width="100%">
<tr>
<td align="center" width="240"><img src="assets/nasa-space-apps-2025.png" alt="NASA Space Apps 2025 Global Nominee" width="220" /></td>
<td valign="middle" style="padding-left:24px">

<br/>

[![Global Nominee Award](https://img.shields.io/badge/NASA%20International%20Space%20Apps%20Challenge%202025-Global%20Nominee-1a3a6b?style=for-the-badge)](#)

<br/><br/>

**Project:** [N-Large](https://github.com/D-Hack1/Nlarge)

<br/>

**Team:** [ebinthomas06](https://github.com/ebinthomas06) · [AadiBolics](https://github.com/AadiBolics) · [nivednarayan](https://github.com/nivednarayan) · [sanjay-was-taken](https://github.com/sanjay-was-taken) · [jaith-krishh](https://github.com/jaith-krishh) · [JXTDEVELOPER](https://github.com/JXTDEVELOPER)

<br/><br/>

</td>
</tr>
<tr><td colspan="2"><br/></td></tr>
<tr>
<td align="center" width="240"><img src="assets/realmhack26-best-build.png" alt="Realm Hack '26 Best Build Certificate" width="220" /></td>
<td valign="middle" style="padding-left:24px">

<br/>

[![Best Build Award](https://img.shields.io/badge/Realm%20Hack%20'26%20National%20Hackathon-Best%20Build-C62828?style=for-the-badge)](#)

<br/><br/>

**Project:** [KooliKanakku](https://github.com/D-Hack1/KooliKanakku)

<br/>

**Team (JangoMaar):** [ebinthomas06](https://github.com/ebinthomas06) · [AadiBolics](https://github.com/AadiBolics) · [nivednarayan](https://github.com/nivednarayan) · [AbhiKamp](https://github.com/AbhiKamp)

<br/><br/>

</td>
</tr>
</table>

---

### ▸ Flagship Projects

### 1. [N-Large](https://github.com/D-Hack1/Nlarge) (NASA Space Apps '25 Global Nominee)
**"Google Maps for Space" — Visualizing massive, gigapixel-scale astronomical data.**
N-Large solves the problem of rendering 500MB+ raw `.fits` or `.tif` space images in a standard web browser without crashing. It pre-processes images into a pyramid of optimized tiles and dynamically serves them based on user zoom level and coordinates.
*   **Tech Stack:** React, FastAPI, Python Data Pipeline (Pillow), Google Cloud Storage, PostgreSQL.
*   **Team:** [ebinthomas06](https://github.com/ebinthomas06) · [AadiBolics](https://github.com/AadiBolics) · [nivednarayan](https://github.com/nivednarayan) · [sanjay-was-taken](https://github.com/sanjay-was-taken) · [jaith-krishh](https://github.com/jaith-krishh) · [JXTDEVELOPER](https://github.com/JXTDEVELOPER)
<details>
<summary><b>View N-Large Architecture Details</b></summary>

*   **Data Processing Pipeline:** Custom Python script (`generate_tiles.py`) chops massive images into 256x256 tiles across multiple zoom levels, overlays PostgreSQL DB labels, and uploads to GCS.
*   **Backend:** FastAPI acts as a bridge, proxying image tiles from GCS to the frontend and fetching dynamic configuration.
*   **Frontend:** React + OpenSeadragon seamlessly renders the high-res zoomable images by requesting only visible tiles as the user pans and zooms.
</details>

### 2. [KooliKanakku](https://github.com/D-Hack1/KooliKanakku) (Realm Hack '26 Best Build)
**Fair pay, worked out together. — On-device AI for home cleaning estimates.**
An offline-first Android application that helps home-cleaning workers and homeowners agree on fair pricing. Point the phone at a room; the app measures it via sensors, spots clutter/grime using on-device YOLO models, and calculates time and pay.
*   **Team (JangoMaar):** [ebinthomas06](https://github.com/ebinthomas06) (Ebin Thomas) · [AadiBolics](https://github.com/AadiBolics) (Aadinadhan A R) · [nivednarayan](https://github.com/nivednarayan) (Nived Narayan) · [AbhiKamp](https://github.com/AbhiKamp) (Abhinav S)
*   **Tech Stack:** Kotlin, Jetpack Compose, CameraX, LiteRT (TFLite) YOLO detectors.
<details>
<summary><b>View KooliKanakku Architecture Details</b></summary>

*   **Pipeline:** Camera/Sensors -> YOLO Object Detection -> Stain Analysis -> Task Mapper -> Pricing Engine -> PDF Export.
*   **Privacy-First:** The estimate and evidence engine runs fully on-device. No network code is required for the core app (works in Airplane Mode).
*   **Features:** Tamper-evident evidence hashing, English/Malayalam UI, and an optional Supabase-powered "Find a worker" layer.
</details>

### 3. Aegis (SIH 2026)
**Passive AI/ML Network Threat Detection.**
A highly complex, passive network monitoring platform that combines network telemetry, machine learning, and real-time streaming to detect threats without introducing an active control path.
*   **Tech Stack:** Python, Zeek, Kafka, XGBoost, Isolation Forest, FastAPI, Elasticsearch, React.
<details>
<summary><b>View Aegis Architecture Details</b></summary>

*   **Pipeline:** Zeek Telemetry -> Feature Engineering -> Kafka Staging -> ML Inference (XGBoost/Isolation Forest) -> Elasticsearch -> React Dashboard.
*   **Capabilities:** Detects SYN/UDP floods, C2 beaconing, DGA, and exfiltration. Uses SHAP for explainable detection (converting features into human-readable evidence).
*   **Data Flow:** Designed for isolated Docker environments simulating real attack and benign traffic scenarios.
</details>

---

### ▸ Complete Project Portfolio

Beyond our flagship applications, our organization houses several robust MVPs categorized by domain:

**Security, Identity & Public Safety**
*   [**InvisiKey**](#) - A secure, scalable Flutter banking solution using rhythm-based behavioral authentication and ML for OTP-free transactions.
*   [**Sentry**](#) - A Python-based incident detection, alerting, and event processing engine.
*   [**SEE**](#) - Full-stack web platform for governance and public monitoring (SIH 2025).

**AI, ML & Data Science**
*   [**Gene-Expression-Explorer**](#) - Python web app (Streamlit/Flask) for biomedical data exploration, running automated ML analysis on public datasets.
*   [**Adobe Series (Adobe, adobe_a1, adobe_1b)**](#) - Iterative Python data processing pipelines and model experimentation suites for analytics challenges.

**Energy & Sustainability**
*   [**SolarWatts**](#) - Flutter mobile app for renewable energy monitoring and consumption optimization.
*   [**sharewatts**](#) - User-facing Dart/Flutter application for peer-to-peer solar sharing and smart-grid community engagement.

**Web Platforms & Utilities**
*   [**SIGNOPSIS & SIGNOPSIS-FINAL**](#) - Front-end heavy coding/education portals ("CODE KALARI") backed by Python.
*   [**Arivu**](#) - TypeScript-based modern knowledge and education SaaS dashboard.
*   [**Canara_Backend** & **bajaj**](#) - Python backend foundations (Django/FastAPI) for financial platforms and domain-specific automation.

---
<div align="center">
  <i>Building intelligent interfaces, secure architectures, and data-driven solutions.</i>
</div>
