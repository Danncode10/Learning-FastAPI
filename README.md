## 📘 Learning FastAPI: Full-Stack AI-Ready Web Development

Welcome to my personal learning journey into **FastAPI**, where I build a full-stack web application with a **React frontend**, a **FastAPI backend**, and integrate **AI models using Hugging Face**.

This course is designed to go from **absolute backend beginner** to deploying a full-stack app with **modern tools** and **real-world API practices**.

---

### 🚀 Tech Stack

* **Backend:** [FastAPI](https://fastapi.tiangolo.com/), Uvicorn, Pydantic
* **Frontend:** React, JavaScript/TypeScript *(later in the course)*
* **AI Models:** Hugging Face Transformers *(later in the course)*
* **Database:** SQLite (starter), PostgreSQL *(optional)*
* **Auth:** Clerk *(planned)*
* **Dev Tools:** VSCode, REST Client, Git, GitHub

---

### 📁 Project Structure

```bash
Learning-FastAPI/
├── backend/        # FastAPI app
│   ├── main.py
│   └── app/
│       ├── routers/
│       ├── models/
│       ├── database.py
│       └── ...
├── frontend/       # React app (later)
├── lessons/        # Course notes (Markdown format)
├── .gitignore
├── README.md
└── requirements.txt
```

---

### 📦 Setup Instructions

1. **Clone the repo:**

   ```bash
   git clone https://github.com/Danncode10/Learning-FastAPI.git
   cd Learning-FastAPI
   ```

2. **Create and activate virtual environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the FastAPI app:**

   ```bash
   uvicorn backend.main:app --reload
   ```

5. **Open your browser:**

   ```
   http://localhost:8000
   ```

   * Docs: [http://localhost:8000/docs](http://localhost:8000/docs)
   * ReDoc: [http://localhost:8000/redoc](http://localhost:8000/redoc)

---

### ✍️ Lessons

> See the `lessons/` folder for step-by-step Markdown notes and guides.

---

### 💡 License

MIT License – feel free to fork, clone, or remix for your own learning.