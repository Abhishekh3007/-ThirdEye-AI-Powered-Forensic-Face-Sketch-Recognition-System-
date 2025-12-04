# 🧿 ThirdEye  
### AI-Powered Forensic Face Sketch & Recognition System  
**(Supabase + React + Python ML)**

---

## 🚨 Project Overview

**ThirdEye** is an AI-driven forensic system that allows users to **create facial sketches digitally** and **match them against a face database** using deep learning — all through a modern web interface.

This project replaces traditional manual forensic sketching and manual face comparison with a **sketch-to-face recognition pipeline** built using:

- 🎨 Interactive canvas-based sketch editor  
- 🧠 Deep-learning-based face embeddings  
- 🗃️ Secure cloud database & storage  
- ⚡ Fast, scalable architecture  

---

## ✨ Key Features

✅ Digital facial sketch editor (drag, drop, scale, rotate facial elements)  
✅ Export sketches as PNG images  
✅ Secure authentication (email/password)  
✅ Store sketches with metadata & layer information  
✅ Index faces using AI embeddings  
✅ Search & match faces by similarity score  
✅ Role-based access (user / admin)  
✅ Audit trail for searches & matches  

---

## 🏗️ System Architecture (Option A – Supabase Cloud)

```text
React Frontend
 ├─ Sketch Editor (Canvas)
 ├─ Auth & Dashboard UI
 └─ Search Results UI
        │
        ▼
Supabase Cloud
 ├─ Auth (JWT, sessions)
 ├─ PostgreSQL (sketches, faces, matches)
 ├─ Storage (sketch & face images)
 └─ Edge Functions (secure ML orchestration)
        │
        ▼
Python ML Microservice
 ├─ Face Embedding Extraction
 └─ Face Similarity Search
