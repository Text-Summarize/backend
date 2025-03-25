# 📝 Text Summarization API

This FastAPI-based application uses a **T5 transformer model** to generate text summaries. It supports summarizing text inputs and stores previous summaries in a MongoDB collection.

## 🚀 Features

- Summarize text using a **T5-small** transformer model.
- Store and retrieve previous summaries from **MongoDB**.
- Supports GPU acceleration (if available).
- RESTful API with FastAPI.

---

## 📚 Prerequisites

Ensure you have the following installed:

- Python 3.10+
- MongoDB (running instance)
- Git
- (Optional) CUDA for GPU acceleration

---


### 1. Clone the Repository

```bash
git clone https://github.com/Text-Summarize/backend.git
cd backend

### Run the Application
--- uvicorn app:app --reload
API will be available at: http://localhost:8000


