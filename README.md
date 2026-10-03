<!-- HEADER -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=230&section=header&text=Hagar%20Atallah&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=AI%20Prototyping%20%C2%B7%20Data%20Engineering%20%C2%B7%20Computer%20Vision&descSize=18&descAlignY=60" alt="header" width="100%"/>

**I build AI-powered pipelines, and the data infrastructure behind them.**

<a href="mailto:s-hagar.atallah@zewailcity.edu.eg"><img src="https://img.shields.io/badge/-Email-14B8A6?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/-LinkedIn-7C3AED?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/Hagar633"><img src="https://img.shields.io/badge/-GitHub-1F2937?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=Hagar633&label=Profile+views&color=7C3AED&style=flat-square"/>

</div>

<br/>

<!-- AT A GLANCE -->
<table align="center">
  <tr>
    <td align="center"><b>3.9 / 4.0</b><br/><sub>CGPA, Zewail City</sub></td>
    <td align="center"><b>92.55%</b><br/><sub>flag classification accuracy</sub></td>
    <td align="center"><b>12,000+</b><br/><sub>images, 249 classes</sub></td>
    <td align="center"><b>300+</b><br/><sub>video clips processed</sub></td>
    <td align="center"><b>30+</b><br/><sub>students mentored</sub></td>
  </tr>
</table>

<br/>

## `whoami`

```python
class Hagar:
    studying  = "B.Sc. Communication & Computer Engineering @ Zewail City (2023 - present, 4th year)"
    right_now = "Data Engineering Intern @ Orange Egypt"
    recently  = "MILP crop-mix optimizer for the AgriTwin internship program"
    stack     = ["Kafka", "Spark", "Trino", "NiFi", "PyTorch", "OpenCV", "Gemini API"]
    focus     = ["ETL/ELT & lakehouse design", "MILP optimization", "multimodal LLM pipelines", "computer vision"]

    def mission(self):
        return "turn requirements into working products"
```

<br/>

## Experience

| | Role | When |
|---|---|---|
| 🟠 | **Data Engineering Intern**, Orange Egypt | Current |
| 🌱 | **AI Prototyping Intern**, AgriTwin Summer Internship Program | Jul – Aug 2026 |
| 🎓 | **Junior Teaching Assistant**, Digital Signal Processing | Feb – May 2026 |
| 👁️ | **AI Engineering Intern**, Plaibook-AI | Aug 2025 – Jan 2026 |
| 🌐 | **Web Development Intern**, FARMAWORLD | Dec 2024 – Feb 2025 |

<details>
<summary><b>Orange Egypt</b> · Data Engineering Intern</summary>
<br/>

- Learning and applying the full ETL/ELT lifecycle for data pipeline design
- Working with data warehousing and lakehouse architectures
- Using **Kafka** for stream processing, **NiFi** for data flow orchestration, **Trino** for distributed querying, and **Spark** for large-scale data processing

</details>

<details>
<summary><b>AgriTwin</b> · AI Prototyping Intern</summary>
<br/>

- Implemented the Crop Mix Model as a working **MILP optimizer in Python**, translating field area, water-budget, and imagery-informed yield estimates into a crop-mix recommendation
- Designed the solver to explain its binding constraint alongside each recommendation, and rendered outputs on the shared **Farm Twin Core** dashboard as a season plan rather than a standalone spreadsheet
- Consumed another track's water-budget output as a direct input, integrating components into a shared product core

</details>

<details>
<summary><b>Plaibook-AI</b> · AI Engineering Intern</summary>
<br/>

- Designed and implemented computer vision pipelines integrating **4 AI models** for depth estimation, pose estimation, semantic segmentation, and audio transcription
- Evaluated MediaPipe and YOLO pose estimation, comparing accuracy, inference speed, and deployment efficiency to inform build-vs-buy decisions
- Processed **300+ video clips** using DepthPro, SegFormer (ADE20K), and Decord
- Documented pipeline architecture, model evaluation results, and design decisions for design review

</details>

<details>
<summary><b>Zewail City</b> · Junior Teaching Assistant, DSP</summary>
<br/>

- Guided **30+ undergraduate students** in implementing and debugging signal processing algorithms in MATLAB, through structured lab sessions and code reviews

</details>

<details>
<summary><b>FARMAWORLD</b> · Web Development Intern</summary>
<br/>

- Developed and maintained a full-stack web application integrating front-end, back-end, and database systems
- Worked directly with clients to turn requirements into secure, working features across multiple modules

</details>

<br/>

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌾 AgriTwin Crop Mix Optimizer
MILP land-allocation optimizer under land, rotation, water, demand, labor and soil constraints, with a **CVaR** risk-adjusted variant. Explains the binding constraint behind every recommendation and renders a season plan on the Farm Twin Core dashboard. Includes cost/revenue projection, multi-season rotation planning, scenario comparison, and a generated business-plan document.

`Python` `MILP` `CVaR` `LLM Integration`

</td>
<td width="50%" valign="top">

### 🚁 Drone Flag Detection & Classification
Modular **ROS2** pipeline for autonomous UAV missions. YOLO detects flags, a ConvNeXt+MLP classifies them (**92.55%** accuracy on 12,000+ images, 249 countries). Runs onboard a Raspberry Pi 5 with live GPS, altitude, battery and position telemetry via MAVROS.

`ROS2` `YOLO` `ConvNeXt` `MAVROS` `Raspberry Pi 5`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏦 Embedded AI Bank Security System
Real-time intrusion detection and face-recognition access control across **5+ hardware modules**, containerized with Docker. FaceNet embedding comparison drives automated responses: door locks, intruder capture, and thermal sensing.

`FaceNet` `Docker` `Raspberry Pi` `Embedded Systems`

</td>
<td width="50%" valign="top">

### ⚽ Football Player Performance Analysis
Computer vision pipeline extracting stability, symmetry and movement metrics from match footage. Gemini adds audio transcription and narrative context, fused with visual features into one multimodal prototype, after benchmarking several pose and segmentation models for the best speed-accuracy trade-off.

`OpenCV` `Pose Estimation` `Segmentation` `Gemini`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🎓 Smart Student Performance Prediction
Compared **7 ML models** on **20,000 student records** to predict scores, grades and pass/fail. Full preprocessing pipeline (scaling, encoding, outlier handling, SMOTE). Linear Regression (R² ≈ 0.78) and SVR (R² ≈ 0.75) performed best under cross-validation.

`Scikit-learn` `SMOTE` `Cross-Validation`

</td>
</tr>
</table>

<sub>🔗 Repos: add links to each project here, e.g. `[AgriTwin](https://github.com/Hagar633/REPO-NAME)`</sub>

<br/>

## Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=py,cpp,matlab,postgres,pytorch,tensorflow,keras,sklearn,opencv,ros&perline=10" /><br/>
<img src="https://skillicons.dev/icons?i=kafka,spark,flask,docker,linux,git,github,raspberrypi&perline=10" />

</div>

| Area | Skills |
|---|---|
| **Data Engineering** | Kafka · Trino · NiFi · Spark · ETL/ELT · Data Warehousing · Lakehouse Architecture |
| **AI & LLMs** | Gemini API integration · Agentic Workflows · Multimodal Pipelines · Rapid Prototyping · POC Development · MILP Optimization · Statistics |
| **Computer Vision** | OpenCV · YOLO · MediaPipe · FaceNet · SegFormer · DepthPro · Decord · Detection · Segmentation · Pose Estimation |
| **Machine Learning** | PyTorch · TensorFlow · Keras · Scikit-learn · Transfer Learning · Feature Engineering · Hyperparameter Tuning · Cross-Validation |
| **Product & Collaboration** | Requirements Gathering · User Research · Cross-Functional Collaboration · Design Review · Technical Documentation · Full-Stack (Flask, Databases) |
| **Also** | Simulink · Git · Docker · Linux |

<br/>

## Education & Certifications

- **Zewail City of Science and Technology**, B.Sc. Communication and Computer Engineering · Sep 2023 – Present · CGPA 3.9/4.0
- **Gharbiya STEM School** · Oct 2020 – Jul 2023 · GPA 3.9/4.0
- Machine Learning Specialization, DeepLearning.AI & Stanford (Coursera)
- Deep Learning Specialization, DeepLearning.AI (Coursera)

<br/>

## Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Hagar633&show_icons=true&theme=radical&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Hagar633&theme=radical&hide_border=true" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=110&section=footer" width="100%"/>
