# Hi, I'm Sahil Rana 👋

**Junior Machine Learning Engineer | GenAI Builder**

I am a Machine Learning Engineer specializing in building robust, high-performance Generative AI applications. My focus is on applied AI—bridging the gap between theoretical research and deployable, real-world systems through Low-Latency Inference, Agentic Workflows, and Model Optimization.

* 🔭 **Currently working on:** Real-time Voice AI Agents with <500ms latency.
* 💡 **Core Expertise:** Vector Search (RAG), Quantization (QLoRA), and High-Throughput Inference architectures (vLLM/Groq/FastAPI).
* 🚀 **Mission:** Transitioning my deep, self-directed engineering experience into a high-impact ML role to build scalable, production-ready AI products.

---

### 🚀 Featured Projects

#### 🎙️ [Eva - Real-Time Multimodal Voice Agent](https://github.com/sasy2901/eva-ai-voice-assistant)
<500ms latency voice agent capable of full-duplex conversations and sentiment-driven UI modulation.
* **Architecture:** Llama-3 (70B) on Groq LPU for ultra-low latency inference, paired with Deepgram (Nova-2/Aura) for STT/TTS.
* **Engineering:** Engineered a non-blocking streaming audio pipeline using FastAPI and WebSockets.
* **Key Feature:** Dynamically modulates system responses and frontend themes based on real-time user sentiment analysis (TextBlob).

#### 🧠 [DocuMind Pro - Enterprise Agentic RAG](https://github.com/sasy2901/DocuMind_Pro)
Containerized Multi-Modal workspace with autonomous routing between document retrieval, web search, and vision analysis.
* **Architecture:** Orchestrated via LangChain, utilizing Llama-3.2-Vision (Groq) and ChromaDB.
* **Pipeline:** Implements an Agent Router to dynamically shift between semantic PDF search, live DuckDuckGo web scraping, and computer vision analysis (chart/image interpretation).
* **Ops:** Production-ready; strictly containerized using a slim Docker environment with non-root security policies, deployed via Streamlit.

#### 📈 [WallStreet LLM - Domain-Specific Fine-Tuning & ReAct Agent](https://github.com/sasy2901/WallStreet_Financial_Agent)
End-to-end ML optimization pipeline featuring parameter-efficient fine-tuning (PEFT), data deduplication, and high-throughput inference.
* **Optimization:** Leveraged Unsloth and 4-bit Quantization (QLoRA) to fine-tune Llama-3 8B on consumer GPUs while avoiding memory bottlenecks.
* **Data Engineering:** Implemented MinHash LSH (datasketch) for O(1) duplicate detection, cutting noise and accelerating training convergence by 2x.
* **Serving:** Features a custom ReAct (Reason + Act) routing heuristic and is packaged with a FastAPI/vLLM deployment template sustaining 50 tokens/sec.

---

### 🛠️ Technical Arsenal

| Domain | Technologies |
|---|---|
| **Generative AI** | Llama-3, RAG, LangChain, vLLM, Groq, HuggingFace |
| **Deep Learning** | PyTorch, Transformers, NumPy, Pandas |
| **Model Optimization** | QLoRA, PEFT, Unsloth, Quantization (GGUF/AWQ) |
| **Vector Search** | ChromaDB, FAISS, Hybrid Search |
| **Deployment & Ops** | AWS (EC2/ECS), Docker, FastAPI, WebSockets, GitHub Actions |
| **Languages** | Python (3.11+), SQL, Bash |
