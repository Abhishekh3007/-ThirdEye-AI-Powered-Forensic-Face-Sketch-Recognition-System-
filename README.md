# 🧿 ThirdEye  
### AI-Powered Forensic Face Sketch & Recognition System  
**(Supabase + React + Python ML)**

---

## 🚨 Project Overview

**ThirdEye** is an AI-driven forensic system that allows users to **create facial sketches digitally** and **match them against a face database** using deep learning — all through a modern web interface.

This project replaces traditional manual forensic sketching and manual face comparison with a **sketch-to-face recognition pipeline**.

---

## ✨ Key Features

- 🎨 Canvas-based facial sketch editor  
- 🧠 AI-powered face recognition & matching  
- 🔐 Secure authentication (Supabase Auth)  
- 🗃️ Cloud database & storage (Supabase)  
- ⚡ Fast vector search using embeddings  
- 👤 Role-based access (user / admin)

---

## 🏗️ System Architecture

```
React Frontend
 ├─ Sketch Editor (Canvas)
 ├─ Auth & Dashboard UI
 └─ Search Results UI
        │
        ▼
Supabase Cloud
 ├─ Auth & JWT
 ├─ PostgreSQL (pgvector)
 ├─ Storage (images)
 └─ Edge Functions
        │
        ▼
Python ML Microservice
 ├─ Face Embedding Extraction
 └─ Similarity Matching
```

---

## 🧩 Tech Stack

**Frontend**
- React 18 + TypeScript  
- Konva.js / Fabric.js  
- Vite  

**Backend**
- Supabase (PostgreSQL, Auth, Storage)
- Supabase Edge Functions  

**AI / ML**
- Python 3.10+
- FastAPI
- FaceNet / ArcFace / InsightFace

---

## 🔁 Core Workflow

1. User creates face sketch  
2. Sketch exported as PNG  
3. Image uploaded to Supabase Storage  
4. AI generates face embedding  
5. Vector similarity search performed  
6. Matches displayed with confidence score  

---

## 📂 Repository Structure

```
thirdeye/
├── frontend/
├── ml-service/
├── supabase/
├── docs/
└── README.md
```

---

## 🚀 Getting Started

```bash
npm install
npm run dev
```

For ML service:
```bash
pip install -r requirements.txt
uvicorn app:app --port 5000
```

---

## 🎯 Use Cases

- Forensic investigations
- Law enforcement support
- Academic AI research
- Digital face identification systems

---

## 📌 Disclaimer

This project is for **educational and research purposes only**.

---

## 👨‍💻 Author

**Abhishekh Wali**  
 | Full-Stack Developer | AI Enthusiast  

⭐ Star this repository if you find it useful!
