# Hi, I'm Sahil Rana 👋
### Senior Machine Learning Engineer | Generative AI Architect

I am a **Senior MLE** specializing in building **production-grade Generative AI systems**. My focus is on **Low-Latency Inference**, **Cost Optimization**, and **Agentic Workflows**. I bridge the gap between "Research" and "Reliable Production Systems."

- 🔭 **Currently working on:** Real-time Voice AI Agents with <500ms latency.
- 💡 **Core Expertise:** Quantization (QLoRA), RAG Systems, and High-Throughput Inference (vLLM/Groq).
- ⚡ **Impact:** Reduced cloud inference costs by **40%** by migrating GPT-4 workloads to optimized Llama-3 models.

---

🚀 Featured Projects🎙️ [Eva - Real-Time Multimodal Voice Agent]<500ms latency voice agent capable of full-duplex conversations and sentiment-driven UI modulation.Architecture: Llama-3 (70B) on Groq LPU for ultra-low latency inference, paired with Deepgram (Nova-2/Aura) for STT/TTS.Engineering: Engineered a non-blocking streaming audio pipeline using FastAPI and WebSockets.Key Feature: Dynamically modulates system responses and frontend themes based on real-time user sentiment analysis (TextBlob).

🧠 [DocuMind Pro - Enterprise Agentic RAG]Containerized Multi-Modal workspace with autonomous routing between document retrieval, web search, and vision analysis.Architecture: Orchestrated via LangChain, utilizing Llama-3.2-Vision (Groq) and ChromaDB.Pipeline: Implements an Agent Router to dynamically seamlessly shift between semantic PDF search, live DuckDuckGo web scraping, and computer vision analysis (chart/image interpretation).Ops: Production-ready; strictly containerized using a slim Docker environment with non-root security policies, deployed via Streamlit.

📈 [WallStreet LLM - Domain-Specific Fine-Tuning & ReAct Agent]End-to-end ML optimization pipeline featuring parameter-efficient fine-tuning (PEFT), data deduplication, and high-throughput inference.Optimization: Leveraged Unsloth and 4-bit Quantization (QLoRA) to fine-tune Llama-3 8B on consumer GPUs while avoiding memory bottlenecks.Data Engineering: Implemented MinHash LSH (datasketch) for $O(1)$ duplicate detection, cutting noise and accelerating training convergence by 2x.Serving: Features a custom ReAct (Reason + Act) routing heuristic and is packaged with a FastAPI/vLLM deployment template sustaining 50 tokens/sec.

## 🛠️ Technical Arsenal

| Domain | Technologies |
| :--- | :--- |
| **Generative AI** | **Llama-3**, **RAG**, **LangChain**, **vLLM**, **Groq**, HuggingFace |
| **Deep Learning** | **PyTorch**, Transformers, NumPy, Pandas |
| **Model Optimization** | **QLoRA**, **PEFT**, **Unsloth**, Quantization (GGUF/AWQ) |
| **Vector Search** | **ChromaDB**, **FAISS**, Hybrid Search |
| **Deployment & Ops** | **AWS (EC2/ECS)**, **Docker**, **FastAPI**, **WebSockets**, GitHub Actions |
| **Languages** | Python (3.11+), SQL, Bash |

---
