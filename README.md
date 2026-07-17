<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=280&section=header&text=Abdelrhman&fontSize=70&fontColor=C9A9FF&animation=fadeIn&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20Backend%20Developer%20(.NET)&descAlignY=55&descSize=20" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Explainable+AI+%2F+Deep+Learning+Engineer;.NET+Backend+Developer;Computer+Vision+%26+Medical+Imaging;Building+Production-Grade+ML+Systems" alt="Typing SVG" />
</a>

<br/>

![Helwan University](https://img.shields.io/badge/Helwan_University-CS_%26_AI-6D28D9?style=flat-square&labelColor=1a1a2e)
![DEPI](https://img.shields.io/badge/DEPI-ML_Program_Graduate-7C3AED?style=flat-square&labelColor=1a1a2e)
![Location](https://img.shields.io/badge/📍_Location-Cairo,_Egypt-4C1D95?style=flat-square&labelColor=1a1a2e)

<br/>

<a href="https://your-portfolio-url.com"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-4C1D95?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/your-username"><img src="https://img.shields.io/badge/GitHub-1a1a2e?style=for-the-badge&logo=github&logoColor=A78BFA" /></a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=your-username&color=7c3aed&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/your-username?color=7c3aed&style=flat-square&label=Followers)
![Stars](https://img.shields.io/github/stars/your-username?color=7c3aed&style=flat-square&label=Stars)

</div>

---

### 🧠 About Me

```txt
I am a Computer Science undergraduate specializing in Artificial Intelligence at Helwan
University, with a strong foundation in explainable deep learning, computer vision, and
production-grade software engineering.

I engineer end-to-end AI systems — from model architecture and interpretability (Grad-CAM,
multi-label classification) to deployment-ready interfaces — while maintaining a solid
backend engineering foundation in .NET, built through hands-on internship experience.

My focus is on building systems that are not just accurate, but explainable, reliable,
and production-ready — bridging the gap between research-grade AI and real-world software.
```

**🎯 Open To:** Junior Backend Developer (.NET) · Software Engineer · AI / ML Engineer roles across the Egyptian & Saudi markets

---

### 🛠️ Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=python,cs,java,cpp,js,html,css&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,html,css,js,tailwind&theme=dark" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=dotnet,cs,nodejs,postgres,mysql,sqlite&theme=dark" />

**AI / ML & Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,git,github,docker,vscode,postman&theme=dark" />

---

### 🤖 AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|:---:|---|
| **Deep Learning** | ⭐⭐⭐⭐☆ | CNN architectures (DenseNet121), transfer learning, multi-label classification |
| **Computer Vision** | ⭐⭐⭐⭐☆ | Medical imaging, object detection & tracking (YOLOv10/v11, ByteTrack) |
| **Explainable AI** | ⭐⭐⭐⭐⭐ | Grad-CAM interpretability pipelines for clinical-grade trust |
| **NLP / Seq2Seq** | ⭐⭐⭐☆☆ | Neural machine translation, attention mechanisms, embeddings |
| **MLOps** | ⭐⭐⭐☆☆ | MLflow experiment tracking, evaluation pipelines, reproducibility |
| **LLM Integration** | ⭐⭐⭐☆☆ | Google Gemini API integration for AI-assisted reporting |

</div>

---

### 🚀 Featured Projects

<details>
<summary><b>🩻 Sunu AI — Explainable Chest X-Ray Disease Detection</b></summary>
<br/>

Multi-label chest disease classification system built on a CheXNet/DenseNet121 architecture, engineered for both diagnostic accuracy and clinical interpretability through Grad-CAM visual explanations and an integrated LLM-powered reporting assistant.

| Category | Details |
|---|---|
| **Stack** | Python · PyTorch · DenseNet121 · Grad-CAM · Streamlit · Google Gemini 2.5 Flash · MLflow |
| **Scale** | Trained & evaluated on NIH ChestX-ray14 — 112,120 images |
| **Performance** | Mean AUROC 0.8176 across all classes (best: Pleural Other 0.916) |
| **Security** | Patient-aware data splitting to prevent patient-level data leakage |
| **Impact** | Explainable diagnostic support tool with human-readable AI-generated reports |
| **Repository** | [github.com/your-username/sunu-ai](https://github.com/your-username/sunu-ai) |

Architected as a modular pipeline (`model.py`, `gradcam.py`, `evaluate.py`, `chatbot.py`, `report.py`, `app.py`), the system combines a CheXpert-pretrained DenseNet121 backbone with `BCEWithLogitsLoss` for multi-label learning, Grad-CAM for per-pathology visual explanation, and a Gemini-powered chatbot layer that translates model outputs into clinician-readable reports — all tracked and reproducible via MLflow.

</details>

<details>
<summary><b>🎯 YOLOv10n vs YOLOv11n — Object Tracking Benchmark</b></summary>
<br/>

A rigorous, apples-to-apples benchmarking notebook comparing two generations of the YOLO object detection family under a unified real-time tracking pipeline.

| Category | Details |
|---|---|
| **Stack** | Python · YOLOv10n · YOLOv11n · ByteTrack · Google Colab |
| **Scale** | Full inference benchmark suite across both model generations |
| **Performance** | GPU warm-up protocol with P95 latency measurement for fair comparison |
| **Security** | Deterministic, reproducible evaluation environment |
| **Impact** | Data-driven model selection guidance for real-time tracking workloads |
| **Repository** | [github.com/your-username/yolo-tracking-benchmark](https://github.com/your-username/yolo-tracking-benchmark) |

Designed with methodological rigor in mind — including GPU warm-up cycles, P95 latency reporting, and six structured output artifacts — the benchmark provides a clean, reproducible comparison of YOLOv10n and YOLOv11n integrated with ByteTrack for multi-object tracking.

</details>

<details>
<summary><b>🌐 Neural Machine Translation — English → German</b></summary>
<br/>

A complete sequence-to-sequence neural machine translation system built from the ground up, comparing embedding strategies for translation quality.

| Category | Details |
|---|---|
| **Stack** | Python · PyTorch · Seq2Seq · Bahdanau Attention · CBOW · FastText |
| **Scale** | Trained on the Multi30k English–German parallel corpus |
| **Performance** | Comparative evaluation of CBOW vs FastText embeddings |
| **Security** | N/A — research/portfolio project |
| **Impact** | Demonstrated attention-based NMT fundamentals for portfolio depth |
| **Repository** | [github.com/your-username/nmt-en-de](https://github.com/your-username/nmt-en-de) |

Built with an encoder-decoder
