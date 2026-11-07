<div align="center">
  <!-- Replace with your org's actual logo URL -->
  <img src="https://via.placeholder.com/150" alt="D-Hack1 Logo" width="120" />

  # D-Hack1 
  **Award-Winning Hackathon Portfolio & Product Incubator**

  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
  [![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)](#)
  [![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](#)
  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](#)
</div>

---

## 🚀 About Us
D-Hack1 is a diverse portfolio of hackathon projects, Minimum Viable Products (MVPs), and technical prototypes. Our work spans multiple domains including banking security, AI/data products, renewable energy, public safety, and mobile utilities. We focus on building highly technical, problem-solving architectures—from on-device edge AI to massive gigapixel data pipelines.

## 🏆 Hall of Fame
*   🌍 **Global Nominee Award** @ NASA International Space Apps Challenge 2025 (Project: **N-Large**)
*   🥇 **Best Build Award** @ Realm Hack26 National Hackathon (Project: **KooliKanakku**)

---

## 🌟 Flagship Projects

### 1. N-Large (NASA Space Apps '25 Global Nominee)
**"Google Maps for Space" — Visualizing massive, gigapixel-scale astronomical data.**
N-Large solves the problem of rendering 500MB+ raw `.fits` or `.tif` space images in a standard web browser without crashing. It pre-processes images into a pyramid of optimized tiles and dynamically serves them based on user zoom level and coordinates.
*   **Tech Stack:** React, FastAPI, Python Data Pipeline (Pillow), Google Cloud Storage, PostgreSQL.
<details>
<summary><b>View N-Large Architecture Details</b></summary>

*   **Data Processing Pipeline:** Custom Python script (`generate_tiles.py`) chops massive images into 256x256 tiles across multiple zoom levels, overlays PostgreSQL DB labels, and uploads to GCS.
*   **Backend:** FastAPI acts as a bridge, proxying image tiles from GCS to the frontend and fetching dynamic configuration.
*   **Frontend:** React + OpenSeadragon seamlessly renders the high-res zoomable images by requesting only visible tiles as the user pans and zooms.
</details>

### 2. KooliKanakku (Realm Hack26 Best Build)
**Fair pay, worked out together. — On-device AI for home cleaning estimates.**
An offline-first Android application that helps home-cleaning workers and homeowners agree on fair pricing. Point the phone at a room; the app measures it via sensors, spots clutter/grime using on-device YOLO models, and calculates time and pay.
*   **Team:** Ebin Thomas, Aadinadhan A R, Nived Narayan, Abhinav S (Team JangoMar)
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

## 📂 Complete Project Portfolio

Beyond our flagship applications, our organization houses several robust MVPs categorized by domain:

### 🔐 Security, Identity & Public Safety
*   [**InvisiKey**](#) - A secure, scalable Flutter banking solution using rhythm-based behavioral authentication and ML for OTP-free transactions.
*   [**Sentry**](#) - A Python-based incident detection, alerting, and event processing engine.
*   [**SEE**](#) - Full-stack web platform for governance and public monitoring (SIH 2025).

### 🧬 AI, ML & Data Science
*   [**Gene-Expression-Explorer**](#) - Python web app (Streamlit/Flask) for biomedical data exploration, running automated ML analysis on public datasets.
*   [**Adobe Series (Adobe, adobe_a1, adobe_1b)**](#) - Iterative Python data processing pipelines and model experimentation suites for analytics challenges.

### ☀️ Energy & Sustainability
*   [**SolarWatts**](#) - Flutter mobile app for renewable energy monitoring and consumption optimization.
*   [**sharewatts**](#) - User-facing Dart/Flutter application for peer-to-peer solar sharing and smart-grid community engagement.

### 💻 Web Platforms & Utilities
*   [**SIGNOPSIS & SIGNOPSIS-FINAL**](#) - Front-end heavy coding/education portals ("CODE KALARI") backed by Python.
*   [**Arivu**](#) - TypeScript-based modern knowledge and education SaaS dashboard.
*   [**Canara_Backend** & **bajaj**](#) - Python backend foundations (Django/FastAPI) for financial platforms and domain-specific automation.

---
<div align="center">
  <i>Building intelligent interfaces, secure architectures, and data-driven solutions.</i>
</div>