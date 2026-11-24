# Hi, I'm Nawfal Abdul Malick 👋

**MSc in Artificial Intelligence · Università della Svizzera italiana (USI), 2026**

I build end-to-end AI systems: from research prototypes to production deployments with real latency budgets, CI/CD and monitoring. My work spans computer vision, generative models, LLM agents and robotics policy learning. Every project here is fully reproducible and ships with tests.

Open to: ML Engineer · MLOps Engineer · Computer Vision Engineer · Data Engineering · Applied AI roles

📍 Lugano, Switzerland &nbsp;|&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/nawfal-abdul-malick) &nbsp;|&nbsp; 📧 [Gmail](mailto:nawfal1022@gmail.com)

---

## 🌱 Computer Vision

| Repository | What it is | Highlights |
|---|---|---|
| [aspilanta-fewshot-detection](https://github.com/Nawfal-AI/aspilanta-fewshot-detection) | MSc thesis: rare pest detection using synthetic data generation, YOLOv8 staged transfer learning and CLIP filter | AP@50 = 0.981 on target domain; nine ablations including three that contradicted the design |
| [yolov8-edge-distillation](https://github.com/Nawfal-AI/yolov8-edge-distillation) | YOLOv8s→YOLOv8n knowledge distillation for edge deployment | 0.9615 mAP@50 at 120.9 FPS, 3.46× smaller; PTQ + ONNX export |
| [Action-Event-Focused-Captioning](https://github.com/Nawfal-AI/Action-Event-Focused-Captioning) | BLIP / ViT-GPT2 / GIT fine-tuned for action-focused video captioning | BLEU/METEOR/ROUGE eval before & after fine-tuning; video activity timeline demo |
| [BUDDI-Reproduction](https://github.com/Nawfal-AI/BUDDI-Reproduction) | Reproducibility study of CVPR 2024 paper on 3D social pose estimation | 3-phase study; novel mechanistic probes (RQ-5, RQ-7) beyond the original paper |
| [Cat-Dog-Classification](https://github.com/Nawfal-AI/Cat-Dog-Classification) | ResNet50 transfer learning binary classifier | 99.20% val accuracy; two-phase fine-tuning (frozen → full) |

---

## 🤖 LLM & Agents

| Repository | What it is | Highlights |
|---|---|---|
| [insurance_agent](https://github.com/Nawfal-AI/insurance_agent) | Production LLM agent (RAG + tools) for Swiss public health insurance Q&A | LangGraph ReAct · FastAPI · Streamlit · MLflow · Docker · AWS ECS · CI/CD |
| [EagleSFT-Bilingual-Dataset-and-LLM-FineTuning](https://github.com/Nawfal-AI/EagleSFT-Bilingual-Dataset-and-LLM-FineTuning) | 536K-example EN-RU bilingual SFT dataset + Qwen2.5 LoRA fine-tuning | End-to-end pipeline: translation, dedup, quality filtering, categorisation |
| [DPO-Safety-Alignment-Phi3](https://github.com/Nawfal-AI/DPO-Safety-Alignment-Phi3) | Reproducible DPO + QLoRA safety alignment for Phi-3-mini on a single T4 | Toxicity rate reduced from 0.00326 → 0.000186; full eval harness + honest NOTES.md |

---

## ⚙️ MLOps & Production Engineering

| Repository | What it is | Highlights |
|---|---|---|
| [manipulation-policy-pipeline](https://github.com/Nawfal-AI/manipulation-policy-pipeline) | End-to-end ML platform for robotics policy learning: Behavioural Cloning and Diffusion Policy with full production infrastructure | MLflow experiment tracking · FP16 + ONNX inference · Kubernetes + HPA · Prometheus + Grafana · Evidently drift monitoring · Ansible deployment |

---

## 🔤 NLP & Tooling

| Repository | What it is | Highlights |
|---|---|---|
| [AI-Resume-Skill-Extractor](https://github.com/Nawfal-AI/AI-Resume-Skill-Extractor) | NLP tool that extracts skills from resume PDFs and scores them against a job description | spaCy + TF-IDF · Streamlit app · Docker · pytest + GitHub Actions CI |

---

## 🛠 Tech Stack

**Languages** &nbsp; Python · SQL · Bash  
**Deep Learning** &nbsp; PyTorch · Ultralytics YOLOv8 · HuggingFace Transformers · PEFT · TRL · Diffusers  
**LLM / Agents** &nbsp; LangChain · LangGraph · FAISS · Sentence Transformers · spaCy  
**MLOps** &nbsp; MLflow · Docker · Kubernetes · Helm · Ansible · GitHub Actions · AWS ECS  
**Inference** &nbsp; ONNX · TensorRT · ONNXRuntime · torch.compile · FP16 · INT8 PTQ  
**Monitoring** &nbsp; Prometheus · Grafana · EvidentlyAI · CloudWatch  
**APIs and Frontend** &nbsp; FastAPI · Streamlit  


