# 📝 Text Summarization API

This FastAPI-based application uses a **T5 transformer model** to generate text summaries. It supports summarizing text inputs and stores previous summaries in a MongoDB collection.

## 🚀 Features

- Summarize text using a **T5-small** transformer model.
- Store and retrieve previous summaries from **MongoDB**.
- Supports GPU acceleration (if available).
- RESTful API with FastAPI.

---


---

## 📚 Prerequisites

Ensure you have the following installed:

| Tool                      | Purpose                         | Installation Command                            |
|---------------------------|----------------------------------|-----------------------------------------------|
| **Python 3.10+**          | Required to run FastAPI & model  | [Download Python](https://www.python.org)    |
| **MongoDB**               | Stores summaries                | [MongoDB Installation Guide](https://www.mongodb.com/docs/manual/installation/) |
| **Git**                   | Version control                 | [Download Git](https://git-scm.com/)         |
| **CUDA (Optional)**       | GPU Acceleration for Torch       | [Install CUDA](https://developer.nvidia.com/cuda-downloads) |
| **Uvicorn**               | FastAPI ASGI server              | `pip install uvicorn`                        |
| **Transformers**          | Hugging Face transformer models  | `pip install transformers`                   |
| **Torch**                 | Deep learning framework          | `pip install torch`                          |
| **python-dotenv**         | Manage environment variables     | `pip install python-dotenv`                  |

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Text-Summarize/backend-app.git
cd backend-app



### 1. Clone the Repository

```bash
git clone https://github.com/Text-Summarize/backend.git
cd backend

### Run the Application
--- uvicorn app:app --reload
API will be available at: http://localhost:8000


