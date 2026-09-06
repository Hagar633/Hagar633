<h1 align="center">Hi, I'm Hagar Atallah </h1>
<h3 align="center">AI Prototyping × Data Engineering × Computer Vision</h3>

<p align="center">
Building AI-powered pipelines and the data infrastructure behind them.
</p>

---

### About

I'm a Communication and Computer Engineering student at Zewail City of Science and Technology (CGPA 3.9/4.0, Fourth Year), building AI-powered pipelines, rapid prototypes, and full-stack tools that turn requirements into working products. I move across the stack: integrating LLM APIs into multimodal pipelines, building optimization and ML solvers, and working on the data infrastructure that feeds these systems — currently as a Data Engineering Intern at Orange Egypt.

- 🔭 Currently interning as a **Data Engineer at Orange Egypt**
- 🧠 Background spanning computer vision, optimization (MILP), LLM integration, and embedded AI
- 🎓 B.Sc. Communication and Computer Engineering @ Zewail City (2023–Present)

---

### Current Focus

- Data Engineering: ETL/ELT pipeline design, data warehousing, and lakehouse architectures using **Kafka, Trino, NiFi, and Spark**
- AI prototyping: LLM API integration (Gemini), multimodal pipelines, rapid POC development
- Optimization: MILP-based solvers for real-world resource allocation problems
- Computer vision pipelines for detection, segmentation, and pose estimation

---

### Experience

**Data Engineering Intern — Orange Egypt** *(Current)*
- Learning and applying the full ETL/ELT lifecycle for data pipeline design
- Working with data warehousing and lakehouse architectures
- Using **Kafka** for stream processing, **NiFi** for data flow orchestration, **Trino** for distributed querying, and **Spark** for large-scale data processing

**AI Prototyping Intern — AgriTwin Summer Internship Program** *(Jul 2026 – Aug 2026)*
- Implemented the Crop Mix Model as a working mixed-integer linear programming (MILP) optimizer in Python, translating field area, water-budget, and imagery-informed yield estimates into a crop-mix recommendation
- Designed the solver to surface a clear explanation of the binding constraint alongside its recommendation, and rendered outputs directly on the shared Farm Twin Core dashboard as a season plan rather than a standalone spreadsheet
- Collaborated across a multi-track internship program, consuming another track's water-budget output as a direct input — hands-on experience integrating components into a shared product core

**AI Engineering Intern — Plaibook-AI** *(Aug 2025 – Jan 2026)*
- Designed and implemented computer vision pipelines integrating 4 AI models for depth estimation, pose estimation, semantic segmentation, and audio transcription
- Evaluated MediaPipe and YOLO pose estimation frameworks, comparing accuracy, inference speed, and deployment efficiency to inform build-vs-buy and design trade-off decisions
- Processed 300+ video clips using DepthPro, SegFormer (ADE20K), and Decord to build efficient preprocessing and feature extraction workflows
- Documented pipeline architecture, model evaluation results, and design decisions for engineering collaboration and design review

**Junior Teaching Assistant — Digital Signal Processing** *(Feb 2026 – May 2026)*
- Guided 30+ undergraduate students in implementing and debugging signal processing algorithms in MATLAB, translating conceptual questions into working code through structured lab sessions and code reviews

**Web Development Intern — FARMAWORLD** *(Dec 2024 – Feb 2025)*
- Developed and maintained a full-stack web application integrating front-end, back-end, and database systems
- Collaborated directly with clients to gather requirements and translate them into secure, working features across multiple project modules

---

### Featured Projects

#### AgriTwin Crop Mix Optimizer & Business Planning Layer
**Technologies:** `Python` `MILP Optimization` `CVaR` `LLM Integration`

A mixed-integer linear programming optimizer that recommends land allocation per crop under real-world constraints — land availability, rotation rules, water budget, market demand, labor, and soil suitability — maximizing expected profit with a risk-adjusted (CVaR) objective variant. The solver surfaces an LLM-generated explanation of the binding constraint behind each recommendation and renders outputs as a season plan on the shared Farm Twin Core dashboard. Built out the surrounding business-planning layer on top of the optimizer: cost/revenue projection per crop per field, a multi-season crop rotation planner, side-by-side scenario comparison views, and a generated business-plan document from a live crop-mix recommendation. Developed as part of a multi-track internship program, integrating outputs from other tracks (e.g., water-budget data) as live inputs.

#### Autonomous Drone Flag Detection & Classification System
**Technologies:** `ROS2` `YOLO` `ConvNeXt` `MAVROS` `Raspberry Pi 5`

A modular ROS2 pipeline for autonomous UAV missions: streams camera data, runs YOLO for flag detection, and classifies with a ConvNeXt+MLP model trained on 12,000+ images across 249 country flags, reaching 92.55% classification accuracy. Deployed the inference pipeline on a Raspberry Pi 5 for real-time preprocessing and onboard classification, with live telemetry (GPS, altitude, battery, position) published via MAVROS.

#### Real-Time Embedded AI Bank Security System
**Technologies:** `FaceNet` `Docker` `Raspberry Pi` `Embedded Systems`

An AI-driven security system integrating 5+ hardware modules for real-time intrusion detection and automated face-recognition access control, containerized with Docker for reproducible deployment. Built a FaceNet-based recognition pipeline using facial embedding comparison, with automated response logic including door locks, intruder capture, and thermal sensing after unauthorized access.

#### Football Player Performance Analysis
**Technologies:** `OpenCV` `Pose Estimation` `Segmentation` `Gemini`

A computer vision pipeline extracting player stability, symmetry, and movement metrics from football match footage. Integrated the Gemini LLM API to generate audio transcription and narrative context, combining it with visual feature extraction into a single multimodal analysis prototype. Rapidly prototyped across multiple pose-estimation and segmentation models to land on the best accuracy-speed trade-off.

#### Smart Student Performance Prediction System
**Technologies:** `Scikit-learn` `SMOTE` `Cross-Validation`

Compared 7 machine learning models on 20,000 student records to predict scores, grades, and pass/fail outcomes. Built a full preprocessing pipeline (feature scaling, categorical encoding, outlier handling, SMOTE for class imbalance), with Linear Regression (R² ≈ 0.78) and SVR (R² ≈ 0.75) performing best under cross-validation.

---

### Technical Skills

**AI Prototyping & LLMs**
`LLM API Integration (Gemini)` `Agentic Workflows` `Rapid Prototyping` `POC Development` `Multimodal Pipelines` `MILP Optimization` `Statistics`

**Data Engineering**
`Kafka` `Trino` `NiFi` `Spark` `ETL/ELT` `Data Warehousing` `Lakehouse Architecture`

**Programming**
`Python` `C++` `MATLAB` `SQL`

**Machine Learning**
`PyTorch` `TensorFlow` `Keras` `Scikit-learn` `Transfer Learning` `Feature Engineering` `Hyperparameter Tuning` `Cross-Validation` `Model Evaluation`

**Computer Vision**
`OpenCV` `YOLO` `MediaPipe` `FaceNet` `SegFormer` `DepthPro` `Decord` `Object Detection` `Semantic Segmentation` `Pose Estimation`

**Product & Collaboration**
`Requirements Gathering` `User Research` `Cross-Functional Collaboration` `Design Review` `Technical Documentation` `Full-Stack Development (Flask, Databases)`

**Tools**
`Git` `GitHub` `Docker` `Linux` `Simulink`

---

### Education

**Zewail City of Science and Technology** — B.Sc. Communication and Computer Engineering
Sep 2023 – Present (Fourth Year) · CGPA: 3.9/4.0

**Gharbiya STEM School**
Oct 2020 – Jul 2023 · GPA: 3.9/4.0

---

### Certifications

- Machine Learning Specialization — DeepLearning.AI & Stanford University (Coursera)
- Deep Learning Specialization — DeepLearning.AI (Coursera)

---

### Contact

- 📧 s-hagar.atallah@zewailcity.edu.eg
- 🐙 [github.com/Hagar633](https://github.com/Hagar633)


