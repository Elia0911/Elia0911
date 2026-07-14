<div align="center">

<!-- Header banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=180&section=header&text=Eli%20OUN&fontSize=52&fontColor=ffffff&animation=fadeIn&desc=Data%20Scientist%20%C2%B7%20Computer%20Vision%20%C2%B7%20AI%20Engineering&descSize=18&descAlignY=70" width="100%"/>

MSc Data Science and Artificial Intelligence, Université Côte d'Azur — Nice, France

[![LinkedIn](https://img.shields.io/badge/LinkedIn-eliaoun0911-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eliaoun0911)
[![Email](https://img.shields.io/badge/Email-eli.nedal.oun%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:eli.nedal.oun@gmail.com)

</div>

---

## About

I am a computer engineer specializing in **computer vision** and **applied machine learning**, with a background spanning industrial AI systems, LLM-based applications, and data analytics. My work sits at the intersection of research and production: I have deployed deep learning models for automotive manufacturing, built retrieval-augmented generation pipelines for commercial products, and co-authored research in surgical video understanding and multimodal speech recognition.

I hold a Bachelor's degree in Computer Engineering and Automatic Control from Tishreen University and am currently completing my MSc in Data Science and Artificial Intelligence at Université Côte d'Azur. I work in English, French, Spanish, and Arabic.

## Areas of Expertise

**Computer Vision.** My core specialty. I have engineered vision systems across markedly different domains: fine-grained surgical action segmentation on robotic surgery video (VideoMAE, ASFormer, MS-TCN), automated quality control and defect detection on automotive assembly lines, object detection and OCR pipelines for historical document analysis (YOLOv8, Tesseract, EasyOCR), and real-time augmented reality applications combining OpenCV with Unity 3D. My experience covers the full lifecycle — dataset construction, model training and evaluation, and deployment under real-world constraints.

**AI/ML Engineering — LLMs & RAG.** I design and operate LLM-based systems in production settings: intent extraction and semantic parsing for user-facing applications, retrieval-augmented generation pipelines grounded in business knowledge, and automated deployment and evaluation of AI agents with measurable accuracy and satisfaction metrics. Toolchain: LangChain, LangSmith, vLLM, OpenAI APIs, Hugging Face Transformers.

**Data Science & Analytics.** Large-scale exploratory data analysis (including driver behavior data informing ADAS feature development), predictive maintenance modeling with deep learning, and executive-facing BI dashboards for manufacturing KPIs and supply chain optimization (Power BI).

**Cybersecurity.** IBM-certified Cybersecurity Analyst with hands-on penetration testing experience — a perspective I bring to building AI systems that are robust as well as accurate.

## Research

### Toward Fine-Grained Surgical Action Segmentation: A Comparative Study of Visual Features and Temporal Models
*I. Alsaïdi, **E. Oun**, E. S. Ekmekci — Université Côte d'Azur & INRIA (Epione)*

A controlled, visual-only benchmark of fine-grained surgical action segmentation on the **SAR-RARP50** robotic surgery dataset. The study systematically compares visual feature extractors (ResNet50, VideoMAE) with temporal architectures of increasing sophistication (MLP, BiGRU, TCN, MS-TCN, ASFormer) under a unified, reproducible operation-level evaluation pipeline. The retained **ASFormer + VideoMAE** configuration reaches **0.871 F1@10** in grouped validation and **0.825 F1@10** on the official test set — exceeding the best previously reported per-video F1@10 on several test operations.

`ASFormer` `VideoMAE` `MS-TCN` `Temporal Action Segmentation` `Surgical Data Science` `Optuna`

### Advancing Speech Recognition for the Hearing Impaired: A Multimodal Radar Approach in Healthcare
*with the James Watt School of Engineering, University of Glasgow*

Radar-enhanced multimodal speech recognition combining radar, audio, and visual inputs to substantially improve recognition for individuals with hearing impairments in challenging healthcare environments.

## Honors & Awards

- 🏆 **EFELIA Côte d'Azur Excellence Scholarship** — awarded two consecutive years (Université Côte d'Azur)
- 🥈 **Second Place — AI for Social Good Hackathon**, Université Côte d'Azur — team solutions addressing health & well-being, gender equality, and climate action, presented before a panel of expert judges, with mentorship from industry experts including a keynote on open-source responsible AI by Hugging Face's María Grandury
- 🥇 **First Place — Ada Lovelace Hackathon** (as team lead, AI Club MENA × Teens In AI)
- 🏅 **Best AI Ethics Award — Girls in AI Hackathon**

## Professional Experience

**AI Systems & Analytics Intern — Stellantis Auto SAS** · Montbéliard, France · 2026
Developed deep learning models for predictive maintenance to reduce vehicle downtime and component failure; engineered computer vision algorithms for automated assembly line quality control and defect detection; built interactive BI dashboards for manufacturing KPIs and supply chain decisions; conducted large-scale EDA on driver behavior data to support ADAS feature development.

**AI Engineering Intern — Smart Goldfish** · Nice, France · 2025
Built intent extraction and semantic parsing models using LLMs for cruise-related user queries; designed RAG pipelines to keep responses accurate and aligned with business knowledge; automated deployment and evaluation of AI agents, improving accuracy and user satisfaction metrics.

**Odoo Developer — Full Circle** · Remote (Oman) · 2023–2024
Developed Python-based solutions to integrate and automate business processes; implemented machine learning for predictive analytics within the Odoo platform; processed large datasets to generate actionable insights; produced technical documentation supporting scalable, maintainable systems.

**Earlier roles** — Chief Operating Officer & Lead Organizer, AI Club MENA; AI Instructor, SCS-Latakia; Robotics Club President, Tishreen University (spearheaded **RCC V1**, Syria's first national robot competition); Computer Vision Mentor, Tishreen University.

## Selected Projects

### Fine-Grained Surgical Action Segmentation — Université Côte d'Azur & INRIA (2026)
Built a full reproducible pipeline for frame-wise gesture recognition on robotic surgery video: unified 10 Hz timeline construction, operation-level sequence reconstruction, grouped cross-validation, and Optuna-based hyperparameter optimization across 162,705 labeled timesteps. Benchmarked 5 temporal architectures × 2 visual backbones. *(See Research above.)*
`PyTorch` `VideoMAE` `ASFormer` `Optuna`

### Metadata Extraction from Historical Documents — Sorbonne University (2025)
Designed dual pipelines to extract structured metadata (monarch names, places, dates) from 18th-century French royal ordinances. Combined an unsupervised OpenCV processing approach with supervised YOLOv8 object detection, and benchmarked OCR engines (Tesseract vs. EasyOCR). Achieved **87% precision** and a **17.3% word error rate** on degraded historical print.
`YOLOv8` `OpenCV` `Tesseract` `EasyOCR`

### Cyber-Bullying Detection on Social Media (2022)
A comparative study of supervised learning approaches for hate speech detection, with a focus on the harder problem of distinguishing genuine hate speech from general profanity — a common failure mode of naive classifiers.
`NLP` `Supervised Learning` `Python`

### Augmented Reality Maze Solver (2021)
A modern take on the classic Labyrinth game: the player holds a physical maze board under a webcam, and a vision pipeline detects the board, computes the solution path in real time, and renders it back through a Unity 3D interface.
`OpenCV` `Unity 3D` `Pathfinding`

## Technical Skills

<div align="center">
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,cpp,fastapi,django,docker,aws,gcp,azure,postgres,mongodb,sklearn,raspberrypi,ros&perline=8" alt="Core technologies" />
</div>

| Domain | Tools & Technologies |
|---|---|
| **Computer Vision** | OpenCV, YOLO, VideoMAE, ASFormer, MS-TCN, OCR (Tesseract, EasyOCR) |
| **Deep Learning** | PyTorch, TensorFlow, Keras, Hugging Face Transformers, Optuna |
| **LLM Engineering** | LangChain, LangSmith, vLLM, RAG, OpenAI APIs |
| **Languages & Backend** | Python, C++, SQL, FastAPI, Django |
| **Data & BI** | Power BI, data mining, Matlab, web scraping (Selenium) |
| **Cloud & DevOps** | AWS, GCP, Azure, Docker, CI/CD |
| **Databases** | PostgreSQL, MongoDB |
| **Robotics & Embedded** | ROS, Raspberry Pi |

## Certifications

- **IBM** — Cybersecurity Analyst Professional Certificate
- **IBM** — Machine Learning with Python
- **DeepLearning.AI** — AI for Medicine Specialization
- **DeepLearning.AI** — Natural Language Processing Specialization

## GitHub Activity

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Elia0911&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub statistics" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Elia0911&layout=compact&theme=default&hide_border=true" alt="Most used languages" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Elia0911&theme=default&hide_border=true" alt="Contribution streak" />

</div>

---

<div align="center">
<sub>📍 Nice, France · English · Français · Español · العربية</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>
</div>
