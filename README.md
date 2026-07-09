# vivi-portfolio
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Vivek%20Biju&subtitle=AI%20Engineer&fontSize=90&animation=fadeIn" alt="Header" />
</p>

# Meet the AI Engineer 🤖

<img src="YOUR_PROFILE_IMAGE_OR_ANIMATION_URL_HERE" align="right" alt="Vivek Biju" width="280" style="border-radius: 10px; margin-left: 20px;" />

I am an AI Engineer based in the United Kingdom, bridging the gap between complex algorithmic research and production-grade software engineering. I specialize in building data and container infrastructures around models rather than writing simple API wrappers. My expertise spans Enterprise GenAI/RAG pipelines, Edge optimization, Computer Vision, Deep Reinforcement Learning, and Multi-Objective Genetic Algorithms.

I focus heavily on operationalizing AI systems with production-ready architectures, ensuring low latency, high throughput, and robust reproducibility. From designing multi-agent triage frameworks to building custom simulation environments, I prioritize engineering rigor, statistically sound evaluations, and full explainability.

Driven by a passion for autonomous architectures and mathematical optimization, I continuously explore advanced paradigms like compound AI architectures and operations research to solve high-impact, enterprise-grade challenges.

---

## 🛠️ My Most Skilled Technologies

### Core Stack & Frameworks
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3A?style=for-the-badge&logo=chainlink&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)

### Machine Learning, MLOps & Infrastructure
![XGBoost](https://img.shields.io/badge/XGBoost-111111?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🔬 Featured Production-Grade AI Projects

### 1. Advanced RAG Research Assistant (Enterprise Technical QA)
A production-ready Retrieval-Augmented Generation (RAG) system engineered to solve context degradation ("lost-in-the-middle") when querying dense, technical research manuscripts.

* **The Architecture:** Built as a **"Monolith-in-a-Box"** using a Linux **Supervisor daemon** to concurrently orchestrate a FastAPI backend and a Streamlit frontend over a single cloud-ingress port (`7860`).
* **Advanced AI Engineering:** Implemented a **Two-Stage Hybrid Retrieval Pipeline** (Vector Recall via ChromaDB + Precision Reranking via local **FlashRank Cross-Encoders**). Offloaded compute-heavy Ragas evaluation loops into an asynchronous FastAPI background task queue.
* **Enterprise Observability:** Native `@traceable` distributed tracing integrated into **LangSmith** to group individual retrieval and generation spans into synchronized tree execution graphs.
* **Explore:** 💻 [Code & Deep Dive](https://github.com/vivekbiju/RAG-project) | 🚀 [Live Production App](https://huggingface.co/spaces/Vivekbiju0/RAG-Document-Analyzer) | 📊 [LangSmith Dashboard](https://aws.smith.langchain.com/o/a01e2752-b31e-4cf6-b828-f7a2634b5944/projects/p/defd6317-d455-4f33-847a-b3ff3387a35b)

### 🚀 2. Slang-Aware Sentiment Engine (Compound AI Architecture)
A high-performance dual-layer system built to decode highly informal digital consumer text, internet vernacular, and localized UK slang.

* **The Architecture:** A hybrid system balancing computational efficiency with deep cloud reasoning. Features a local, fine-tuned DistilBERT model optimized down to a **~49ms inference latency** via Hugging Face `optimum` and **ONNX Runtime quantization**, alongside a Gemini 1.5 Flash agent acting as an intelligent triage gateway to resolve contextual ambiguity.
* **Explainable AI (XAI) & Governance:** Integrated mathematical **SHAP (Shapley Additive Explanations)** heatmaps directly within the UI to track exact token-level feature attribution. Includes a comprehensive `MODEL_CARD.md` ensuring compliance with the **UK AI Regulation Framework** regarding dialect governance.
* **MLOps Pipeline:** Centrally logged model telemetry ($F1$-Score, Precision, and Recall curves) using **MLflow** to monitor highly imbalanced training datasets. Maintained cross-platform data preprocessing safety with automated `pytest` suites via GitHub Actions.
* **Explore:** 💻 [Code & Deep Dive](https://github.com/vivekbiju/Sentiment-Analysis-Model) | 🚀 [Live Production App](https://huggingface.co/spaces/Vivekbiju0/multi-agent-sentiment-analysis)

### 🩺 3. Hybrid Skin Cancer Diagnostic System (XAI-Enabled Clinical Support)
An end-to-end clinical decision support system utilizing a hybrid machine learning pipeline paired with dual-layer Explainable AI to meet strict medical algorithmic accountability standards.

* **The Architecture:** Implements a two-stage hybrid inference pipeline. A fine-tuned **ResNet50 CNN backbone** processes dermoscopic images to extract 2,048 high-dimensional spatial feature vectors, which are fed into a downstream, hyper-parameter optimized **XGBoost classifier head** to generate definitive malignancy probabilities.
* **Clinical Transparency & XAI:** Generates side-by-side diagnostic audit reports containing **Grad-CAM** (to visually map exact pixel regions prioritized during lesion analysis) and **SHAP Force Plots** (computing game-theoretic feature-level attributions).
* **System Infrastructure:** Wrapped in a high-throughput **FastAPI backend** handling asynchronous image ingestion, communicating with a clean Streamlit clinician interface. Fully containerized via multi-stage Docker builds.
* **Explore:** 💻 [Code & Deep Dive](https://github.com/vivekbiju/XAI-For-Skin-Cancer-Detection)

---

## 📁 Autonomous Systems & Mathematical Optimization

| Project & Repository | System Objective | Technical Stack | Core Engineering Metric / UI |
| --- | --- | --- | --- |
| **🤖 [Multi-Agent Path Planning](https://github.com/vivekbiju/SAC-Based-Multi-Agent-Environmental-Mapping)** | Decentralized, autonomous path planning for a fleet of mobile agents mapping environmental variables. | Python, PyTorch, **Gymnasium**, SciPy, TensorBoard | Implements **Soft Actor-Critic (SAC)** with Twin Q-Learning & Automatic Entropy Tuning. Uses `LinearNDInterpolator` to track map reconstruction accuracy. |
| **📦 [Boxes on Shelves: NSGA-II Logistics](https://github.com/vivekbiju/Boxes-on-shelves)** | Multi-objective genetic algorithm designed to solve warehouse spatial distribution challenges by balancing maximum density against physical balance constraints. | Python, Pandas, NumPy, **Plotly (3D Visuals)**, Streamlit | Implements custom Crossover, Mutation, and Non-dominated Sorting. Generates an interactive **Pareto Front Exploration Engine** rendered in a full 3D viewport. |
| **🏠 [House Price Prediction Engine](https://github.com/vivekbiju/house-price-prediction)** | Advanced regression modeling engine engineered for precision property valuation metrics. | Python, Scikit-Learn, Pandas | *Repository under active staging for pending deployment layout updates.* |

---

## 📈 Engineering Rigor & Design Standards

* 🔑 **Zero Hardcoded Secrets:** All infrastructure keys (Gemini API, LangSmith telemetry layers) are isolated via decoupled environment injections (`.env`) routed strictly out of ephemeral container configurations.
* 📦 **Deterministic Build Quality:** Explicitly locks down package versions (`requirements.txt`), guaranteeing zero regressions during deployment to cloud pods or multi-stage Docker runtimes.
* 📊 **Statistically Sound Evaluations:** Projects prioritize professional tracking metrics ($F1$-Score, $R^2$ Variance, Mean Absolute Error, Pareto-Front Dominance) rather than simple accuracy to assess model health under data imbalances.

---

<p align="center">
  <b>Let's Connect!</b><br>
  <a href="https://www.linkedin.com/in/vivek-biju-540468383/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:vivekbijubxr@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" alt="Footer" />
</p>
