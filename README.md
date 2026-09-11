<div align="center">

<!-- ANIMATED HEADER BANNER -->
<img src="https://raw.githubusercontent.com/khushbooshaurya5/khushbooshaurya5/main/header.svg" width="100%" alt="Khushboo Kumari"/>

<!-- OPEN TO WORK BANNER -->
![Open To Work](https://img.shields.io/badge/🎯_OPEN_TO_WORK-ML_Engineer_|_Computer_Vision_|_AI_Research-brightgreen?style=for-the-badge)

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-khushbooshaurya5.github.io-4A90D9?style=for-the-badge)](https://khushbooshaurya5.github.io/khushboo-portfolio-projects/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/khushboo-kumari-5053a9b7/)
[![Email](https://img.shields.io/badge/Email-khushbooshaurya@gmail.com-EA4335?style=for-the-badge&logo=gmail)](mailto:khushbooshaurya@gmail.com)
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://multi-agent-research-assistant-vcuv5hqygtp74djpycnk8a.streamlit.app)

![Profile Views](https://komarev.com/ghpvc/?username=khushbooshaurya5&color=brightgreen&style=for-the-badge)

</div>

---

## 🧠 About Me

Machine Learning Engineer and **M.Sc. Machine Learning & Data Analytics** student at Hochschule Aalen, Germany (B.Tech. Computer Science, top of class). My path spans ~3 years of production software engineering at **HighRadius** (Fortune 2000 fintech SaaS), industrial ML & computer vision at **Carl Zeiss SMT** and **Matworks**, and research ML at the **Max Planck Institute for Astronomy**. I build PyTorch training/evaluation pipelines, curate and preprocess datasets, deploy computer-vision models on live hardware, and work with LLMs, retrieval-augmented generation (RAG), tool calling and multi-agent systems.


---

## 🏆 Key Achievements

<div align="center">

| 🎯 Metric | 📈 Result | 🏢 Company |
|-----------|-----------|-----------|
| Manual analysis reduced (bondpad detection, 1,000+ inspections) | **~70%** | Matworks GmbH |
| Manual workflow reduction (automation) | **~30%** | HighRadius |
| UAT target completion | **108%** | HighRadius |

</div>

---

## 💼 Experience Highlights

| Role | Company | Focus / Impact |
|------|---------|----------------|
| 🔭 Student Research Assistant | **Max Planck Institute for Astronomy** | Semi-supervised gravitational-lens detection in JWST NIRCam imaging (EfficientNet-B0); fixed a data-leakage bug via systematic audit |
| 🔬 ML Intern | **Carl Zeiss SMT GmbH** | Defect-correlation pipeline (WLI roughness ↔ HDF5 imagery), CV pixel-mapping & polar-to-pixel algorithms, modular Tkinter frontend |
| 🤖 Working Student, ML | **Matworks GmbH** | YOLOv9c → ONNX on live hardware for bondpad detection (~70% less manual work); 50+ band hyperspectral fusion + drift detection |
| 🎓 Research Assistant (HiWi) | **Hochschule Aalen** | Kolmogorov-Arnold Networks (B-spline / Cheby / FasterKAN) in PyTorch for gene-expression; explainable-AI tooling |
| 🏎️ Formula Student (AD) | **Hochschule Aalen** | Autonomous-driving simulation in Unreal Engine 4 + CARLA with camera-based perception |
| 💡 Software / Team Lead | **HighRadius Technologies** | Python cloud products for Fortune 2000 clients; ~30% less manual workflow; 108% target completion (promoted across 4 roles, ~3 yrs) |

---

## 🚀 Featured Projects

### 🔬 [Multi-Agent Research Assistant](https://multi-agent-research-assistant-vcuv5hqygtp74djpycnk8a.streamlit.app)
> Multi-agent LLM system with A2A communication, tool calling, and RAG for automated research workflows; analysed failure modes to improve reliability
> `LangChain` `FAISS` `RAG` `Streamlit` `Tavily`

### 🧩 Multimodal RAG Assistant with Tool-Calling Agent *(building, 2026)*
> Text / image / audio queries through a tool-calling agent (Qwen-VL, Whisper) with FAISS retrieval and an evaluation setup for retrieval quality and tool-call success
> `Qwen-VL` `Whisper` `FAISS` `RAG`

### 📈 Foundation-Model Forecasting Agents — [sktime](https://github.com/sktime/sktime) *(open source, merged)*
> Designed an interface for LLM-based time-series forecasting agents and merged it through maintainer review
> `Python` `sktime` `Open Source`

---

## 🚗 3D Perception & Autonomous Driving

Five from-scratch **PyTorch** projects spanning the core 3D scene-understanding stack for self-driving. Each ships with a real dataset loader, training / evaluation / visualization scripts, a synthetic **CPU smoke test that runs end-to-end without any dataset download**, and GitHub Actions CI.

Every one now has an **interactive browser demo** — click ▶ to try it live.

| Project | What it does | Stack | Live demo |
|---------|--------------|-------|-----------|
| [**LiDAR Semantic Segmentation**](https://github.com/khushbooshaurya5/lidar-semantic-segmentation) | Point-wise segmentation on SemanticKITTI via a spherical range-image projection + SalsaNet-style U-Net (cross-entropy + Lovász-Softmax, streaming mIoU) | `PyTorch` · `SemanticKITTI` · `mIoU` | [▶ viewer](https://khushbooshaurya5.github.io/lidar-pointcloud-viewer/) |
| [**Camera + LiDAR Fusion**](https://github.com/khushbooshaurya5/camera-lidar-fusion) | Two-stream RGB + projected-LiDAR fusion for dense segmentation on KITTI, with a built-in `fusion / rgb / lidar` sensor ablation | `PyTorch` · `KITTI` · `Sensor Fusion` | [▶ demo](https://khushbooshaurya5.github.io/khushboo-portfolio-projects/demos/camera-lidar-fusion/) |
| [**Monocular Depth Estimation**](https://github.com/khushbooshaurya5/monocular-depth-estimation) | Self-supervised depth + ego-motion from video (Monodepth2-style photometric loss, auto-masking) — no depth labels | `PyTorch` · `KITTI` · `Self-Supervised` | [▶ playground](https://khushbooshaurya5.github.io/depth-playground/) |
| [**PointPillars 3D Detection**](https://github.com/khushbooshaurya5/pointpillars-3d-detection) | LiDAR 3D object detection: pillars → BEV pseudo-image → SSD head with anchors, focal + smooth-L1 loss, BEV-NMS | `PyTorch` · `KITTI` · `3D Detection` | [▶ demo](https://khushbooshaurya5.github.io/khushboo-portfolio-projects/demos/pointpillars/) |
| [**BEV Map Segmentation**](https://github.com/khushbooshaurya5/bev-map-segmentation) | Lift-Splat-Shoot: surround-view cameras → depth-lift → splat into a BEV grid → top-down semantic map | `PyTorch` · `nuScenes` · `BEV` | [▶ demo](https://khushbooshaurya5.github.io/khushboo-portfolio-projects/demos/bev-map-segmentation/) |

---

## 🕹️ Interactive Demos

Open-source demos that make the work above **clickable** — the first two run **entirely in the browser** (no server); the RAG assistant is a **full-stack Next.js app** on Vercel.

| Demo | What it does | Live | Code |
|------|--------------|------|------|
| **LiDAR Point-Cloud Viewer** | Load KITTI `.bin` / `.pcd`, color by height / intensity / **SemanticKITTI class**, BEV toggle | [▶ open](https://khushbooshaurya5.github.io/lidar-pointcloud-viewer/) | [repo](https://github.com/khushbooshaurya5/lidar-pointcloud-viewer) |
| **Depth Playground** | Upload a photo → in-browser monocular **depth map** + an orbitable **3D point cloud** | [▶ open](https://khushbooshaurya5.github.io/depth-playground/) | [repo](https://github.com/khushbooshaurya5/depth-playground) |
| **Multimodal RAG Assistant** | Chat with your PDFs — grounded answers with page citations *(Vercel + Supabase + Gemini)* | [▶ open](https://rag-doc-assistant-chi.vercel.app) | [repo](https://github.com/khushbooshaurya5/rag-doc-assistant) |

> Built with React + TypeScript + three.js / transformers.js. The LiDAR viewer is a live companion to my segmentation repo; the depth demo mirrors my monocular-depth repo.

---

## 🧩 Skills & Expertise


**Machine & Deep Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02A651?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Computer Vision**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![EfficientNet](https://img.shields.io/badge/EfficientNet-6A1B9A?style=for-the-badge)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)

**LLMs & Agentic AI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-8E44AD?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Tavily](https://img.shields.io/badge/Tavily_Search-00BCD4?style=for-the-badge)

**Data & Engineering**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📊 Skill Proficiency

```
Python          ████████████████████  95%
Computer Vision ██████████████████░░  90%
PyTorch         █████████████████░░░  85%
ML / scikit     ██████████████████░░  88%
LangChain / RAG ████████████████░░░░  80%
SQL             ███████████████░░░░░  75%
German          ████████░░░░░░░░░░░░  40%
```

---

## 🎯 Currently Learning

![Transformer Architecture](https://img.shields.io/badge/🔥_Transformer_Architecture-Deepening-FF6B35?style=for-the-badge)
![Agentic AI](https://img.shields.io/badge/🤖_Agentic_AI_Systems-Exploring-9C27B0?style=for-the-badge)
![German B1](https://img.shields.io/badge/🇩🇪_German_B1-In_Progress-009688?style=for-the-badge)
![MLOps](https://img.shields.io/badge/⚙️_MLOps_&_Deployment-Learning-1565C0?style=for-the-badge)

---

## 📝 Research Interests

- 🚗 **3D Perception for Autonomous Driving** — LiDAR/camera segmentation, depth, 3D detection, BEV
- 🧬 **Explainable AI (XAI)** — Interpretable neural networks for critical systems
- 🔬 **Industrial Computer Vision** — Defect detection in semiconductor manufacturing
- 🧠 **Neuro-Symbolic AI** — Bridging neural networks with symbolic reasoning
- 🏥 **Biomedical ML** — Cancer gene prediction using KAN networks
- 🤖 **Multi-Agent Systems** — A2A communication and agentic workflows

---

## 🌍 Languages

🇮🇳 Hindi (Native) &nbsp;|&nbsp; 🇬🇧 English (Fluent, B2 certified) &nbsp;|&nbsp; 🇩🇪 German (Basic, actively improving)

---

<div align="center">

*📍 Aalen, Germany &nbsp;|&nbsp; 🎓 M.Sc. Machine Learning — Hochschule Aalen*

**💼 Open to ML Engineering, Computer Vision & AI Research roles!**

⭐ *If you find my work interesting, consider giving a star!* ⭐

</div>
