# 🗣️ AI Voice Assistant (RAG Demo Project)

This project is a full-stack AI voice assistant that allows users to **speak with an AI customer service agent** about their account. The assistant uses **retrieval-augmented generation (RAG)** to give accurate, contextual answers based on your company's data.

Built as part of the [Headstarter Fellowship](https://www.headstarter.xyz), this project demonstrates voice I/O, RAG pipelines, and a basic analytics dashboard — all using **free-tier tools**.

---

## 🎯 Features

- 🎤 **Voice Input** via Deepgram STT (speech-to-text)
- 💬 **LLM-Driven Answers** using Mistral 7B (via Together.ai)
- 📄 **Context-Aware RAG** using ChromaDB + HuggingFace embeddings
- 🔊 **Natural Voice Output** via ElevenLabs TTS
- 📈 **Admin Analytics Dashboard** (call count, common topics, durations)

---

## 🧱 Stack

| Layer             | Tool                  |
|------------------|-----------------------|
| Frontend (optional) | React + Mic API (TBD) |
| Backend           | Python + FastAPI      |
| Vector DB         | ChromaDB (local)      |
| Embeddings        | `BAAI/bge-small-en` (HuggingFace) |
| LLM               | Mistral 7B via Together.ai |
| TTS               | ElevenLabs API        |
| STT               | Deepgram API          |

---

## 🛠️ Setup Instructions

1. **Clone the repo**
```bash
git clone https://github.com/annika-mcmullen/ai-voice-assistant-rag-demo.git
cd ai-voice-assistant-rag-demo
