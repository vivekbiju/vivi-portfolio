<h2 align="center">🔬 Featured Production-Grade AI Systems</h2>

<table style="width: 100%; border-collapse: separate; border-spacing: 15px; margin-top: 20px;">
<tr>
<td style="width: 50%; vertical-align: top; border: 1px solid #e1e4e8; border-radius: 8px; padding: 20px; background: #ffffff; text-align: left;">
<h3 align="center" style="color: #0077B5; margin-top: 0; margin-bottom: 8px;">🚀 AgenticOps</h3>
<p align="center" style="margin-top: 0; margin-bottom: 10px;">
<strong>Autonomous B2B SaaS Incident Remediation & Control Center</strong>
</p>
<p align="center" style="margin-bottom: 15px;">
<a href="https://agenticops-hazel.vercel.app"><img src="https://img.shields.io/badge/Status-LIVE_DEMO-green.svg?style=flat-square" alt="Live Demo" /></a>
</p>
<p style="font-size: 0.92em; line-height: 1.5;">
An enterprise-grade, stateful platform designed to transform raw incident logs into audited, actionable customer remediation playbooks. Key architecture highlights:
</p>
<ul style="font-size: 0.9em; line-height: 1.6; padding-left: 18px;">
<li><strong>Stateful Cyclical Orchestration:</strong> Utilizes LangGraph multi-agent state machines (Classifier, Researcher, Risk Analyst, Auditor) with append_reducer tracers and MemorySaver checkpointers for reliable execution.</li>
<li><strong>Autonomous Stream Governance:</strong> Implements thread-isolated Human-in-the-Loop (HITL) approval gates to intercept dangerous or high-risk incident commands before deployment.</li>
<li><strong>Hybrid Matryoshka Search:</strong> Leverage Elasticsearch (Basic Tier: BM25 + Cosine KNN) with 768d Matryoshka compressed embeddings to achieve high-performance recall without expensive vector licenses.</li>
<li><strong>Observability & Deployment:</strong> Traceable execution via LangSmith wrapper hooks and IaC provisioning via Terraform to run the full containerized microservices stack on AWS EC2.</li>
</ul>
<p align="center" style="margin-bottom: 0; margin-top: 20px;">
<a href="https://github.com/vivekbiju/AgenticOps"><img src="https://img.shields.io/badge/%20VIEW_PROJECT-000000?style=for-the-badge&logo=github&logoColor=white" alt="View Project" /></a>
</p>
</td>

<td style="width: 50%; vertical-align: top; border: 1px solid #e1e4e8; border-radius: 8px; padding: 20px; background: #ffffff; text-align: left;">
<h3 align="center" style="color: #0077B5; margin-top: 0; margin-bottom: 8px;">🩺 Advanced RAG Research Assistant</h3>
<p align="center" style="margin-top: 0; margin-bottom: 10px;">
<strong>Enterprise Technical QA Microservice with Decoupled Architecture</strong>
</p>
<p align="center" style="margin-bottom: 15px;">
<a href="https://huggingface.co/spaces/Vivekbiju0/RAG-Document-Analyzer"><img src="https://img.shields.io/badge/Status-LIVE_PRODUCTION_APP-green.svg?style=flat-square" alt="Live Production App" /></a>
</p>
<p style="font-size: 0.92em; line-height: 1.5;">
A resilient AI microservice optimized for low-latency retrieval and context degradation mitigation in complex technical manuscripts. Engineering details:
</p>
<ul style="font-size: 0.9em; line-height: 1.6; padding-left: 18px;">
<li><strong>Decoupled Microservice:</strong> Uses FastAPI REST API and Streamlit with a self-healing process monitor to dynamically spawn the backend and mount vector pipelines upon first file upload.</li>
<li><strong>Two-Stage Retrieval & Reranking:</strong> Vector Recall via ChromaDB (gemini-embedding-001) + Precision Reranking via local FlashRank Cross-Encoders.</li>
<li><strong>Observability & DevOps:</strong> Mapped complete end-to-end execution spans with LangSmith `@traceable` decorators, containerized via multi-stage Docker builds, and automated deployments to HF Spaces via GitHub Actions.</li>
<li><strong>Faithfulness:</strong> Achieved a persistent 100% RAGAS Faithfulness score, guaranteeing zero unverified hallucinations across dense PDF/TXT datasets.</li>
</ul>
<p align="center" style="margin-bottom: 0; margin-top: 20px;">
<a href="https://github.com/vivekbiju/RAG-project"><img src="https://img.shields.io/badge/%20VIEW_PROJECT-000000?style=for-the-badge&logo=github&logoColor=white" alt="View Project" /></a>
</p>
</td>
</tr>

<tr>
<td style="width: 50%; vertical-align: top; border: 1px solid #e1e4e8; border-radius: 8px; padding: 20px; background: #ffffff; text-align: left;">
<h3 align="center" style="color: #0077B5; margin-top: 0; margin-bottom: 8px;">🚀 Slang-Aware Sentiment Engine</h3>
<p align="center" style="margin-top: 0; margin-bottom: 10px;">
<strong>Compound AI Architecture with Edge Optimization & Triage</strong>
</p>
<p align="center" style="margin-bottom: 15px;">
<a href="https://huggingface.co/spaces/Vivekbiju0/multi-agent-sentiment-analysis"><img src="https://img.shields.io/badge/Status-LIVE_PRODUCTION_APP-green.svg?style=flat-square" alt="Live Production App" /></a>
</p>
<p style="font-size: 0.92em; line-height: 1.5;">
A high-performance dual-layer system engineered to decode highly informal digital consumer text and UK slang. Design highlights:
</p>
<ul style="font-size: 0.9em; line-height: 1.6; padding-left: 18px;">
<li><strong>Layer 1 (Local):</strong> Fine-tuned DistilBERT optimized to ~49ms inference latency via Hugging Face `optimum` and ONNX Runtime quantization.</li>
<li><strong>Layer 2 (Triage):</strong> Gemini 1.5 Flash agent functions as an intelligent triage gateway to resolve contextual ambiguity or visually ironic memes.</li>
<li><strong>Explainable AI (XAI):</strong> Built-in mathematical SHAP token-feature attribution heatmaps directly inside the Streamlit UI.</li>
<li><strong>MLOps Tracking:</strong> MLflow logs full model telemetry ($F1$, Precision, and Recall curves) to monitor training imbalanced slang datasets.</li>
</ul>
<p align="center" style="margin-bottom: 0; margin-top: 20px;">
<a href="https://github.com/vivekbiju/Sentiment-Analysis-Model"><img src="https://img.shields.io/badge/%20VIEW_PROJECT-000000?style=for-the-badge&logo=github&logoColor=white" alt="View Project" /></a>
</p>
</td>

<td style="width: 50%; vertical-align: top; border: 1px solid #e1e4e8; border-radius: 8px; padding: 20px; background: #f9f9f9; text-align: left;">
<h3 align="center" style="color: #0077B5; margin-top: 0; margin-bottom: 8px;">🩺 Hybrid Skin Cancer Diagnostic System</h3>
<p align="center" style="margin-top: 0; margin-bottom: 10px;">
<strong>Master’s in AI Final Semester Project (University of Plymouth)</strong>
</p>
<p align="center" style="margin-bottom: 15px;">
<img src="https://img.shields.io/badge/MSc_Final_Project-Plymouth_Uni-red.svg?style=flat-square" alt="Plymouth Uni MSc Final Project" />
</p>
<p style="font-size: 0.92em; line-height: 1.5;">
An end-to-end clinical decision support system utilizing a hybrid machine learning pipeline paired with dual-layer Explainable AI. Project highlights:
</p>
<ul style="font-size: 0.9em; line-height: 1.6; padding-left: 18px;">
<li><strong>Hybrid Inference Pipeline:</strong> A fine-tuned ResNet50 CNN backbone processes images to extract 2,048 feature vectors, which are fed into a downstream, hyperparameter-optimized XGBoost classifier head.</li>
<li><strong>Dual-Layer XAI:</strong> Generates automated diagnostic audit reports containing Grad-CAM (spatial pixel attention) and SHAP Force Plots (feature-level attribution) to meet medical accountability standards.</li>
<li><strong>Deployment & API:</strong> Fully containerized via multi-stage Docker builds and exposed via a high-throughput FastAPI backend handling asynchronous image ingestion.</li>
</ul>
<p align="center" style="margin-bottom: 0; margin-top: 20px;">
<a href="https://github.com/vivekbiju/XAI-For-Skin-Cancer-Detection"><img src="https://img.shields.io/badge/%20VIEW_PROJECT-000000?style=for-the-badge&logo=github&logoColor=white" alt="View Project" /></a>
</p>
</td>
</tr>
</table>
