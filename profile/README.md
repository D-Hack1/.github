<div align="center">
  <img src="assets/dhack-logo.png" alt="D-Hack1 Logo" width="140" />
  <br/><br/>

  # D-HACK1

  **Award-Winning Hackathon Portfolio & Product Incubator**

  [![Org](https://img.shields.io/badge/GitHub-Org-181717?style=for-the-badge&logo=github)](https://github.com/D-Hack1)
  [![Hackathons Won](https://img.shields.io/badge/Hackathons%20Won-2-C62828?style=for-the-badge)](#-hall-of-fame)
  [![Flagship Projects](https://img.shields.io/badge/Flagship%20Projects-3-1a3a6b?style=for-the-badge)](#-flagship-projects)
  [![Team Members](https://img.shields.io/badge/Team%20Members-10-2e7d32?style=for-the-badge)](#-team)

  <br/>

  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
  [![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)](#)
  [![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](#)
  [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](#)
  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](#)
  [![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](#)
  [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](#)
  [![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#)
  [![TensorFlow Lite](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](#)
  [![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](#)
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

Beyond our flagship applications, our organization houses several robust MVPs, grouped by domain:

<table width="100%">
<tr>
<td width="50%" valign="top">

[![Security, Identity & Public Safety](https://img.shields.io/badge/-Security,%20Identity%20%26%20Public%20Safety-C62828?style=for-the-badge)](#)

*   [**InvisiKey**](#) — Flutter banking solution using rhythm-based behavioral authentication and ML for OTP-free transactions.
*   [**Sentry**](#) — Python-based incident detection, alerting, and event processing engine.
*   [**SEE**](#) — Full-stack web platform for governance and public monitoring (SIH 2025).

</td>
<td width="50%" valign="top">

[![AI, ML & Data Science](https://img.shields.io/badge/-AI,%20ML%20%26%20Data%20Science-6A1B9A?style=for-the-badge)](#)

*   [**Gene-Expression-Explorer**](#) — Streamlit/Flask web app for biomedical data exploration with automated ML analysis on public datasets.
*   [**Adobe Series**](#) *(Adobe, adobe_a1, adobe_1b)* — Iterative Python data pipelines and model experimentation suites for analytics challenges.

</td>
</tr>
<tr><td colspan="2"><br/></td></tr>
<tr>
<td width="50%" valign="top">

[![Energy & Sustainability](https://img.shields.io/badge/-Energy%20%26%20Sustainability-2E7D32?style=for-the-badge)](#)

*   [**SolarWatts**](#) — Flutter mobile app for renewable energy monitoring and consumption optimization.
*   [**sharewatts**](#) — Dart/Flutter application for peer-to-peer solar sharing and smart-grid community engagement.

</td>
<td width="50%" valign="top">

[![Web Platforms & Utilities](https://img.shields.io/badge/-Web%20Platforms%20%26%20Utilities-1565C0?style=for-the-badge)](#)

*   [**SIGNOPSIS & SIGNOPSIS-FINAL**](#) — Front-end heavy coding/education portals ("CODE KALARI") backed by Python.
*   [**Arivu**](#) — TypeScript-based knowledge and education SaaS dashboard.
*   [**Canara_Backend** & **bajaj**](#) — Django/FastAPI backend foundations for financial platforms and domain-specific automation.

</td>
</tr>
</table>

---
<div align="center">
  <i>Building intelligent interfaces, secure architectures, and data-driven solutions.</i>
</div>
