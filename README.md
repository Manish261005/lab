# Fullstack Project

Minimal scaffold for a front-end + back-end demo.

Repository layout
- frontend/ - static frontend (index.html)
- backend/ - minimal Flask backend (app.py)

Quick start (local)

1. Backend
   - Option A: using system Python
     - python -m venv venv
     - source venv/bin/activate  (or venv\Scripts\activate on Windows)
     - pip install flask
     - python backend/app.py
     - Backend API will be available at http://localhost:5000/api/hello

2. Frontend
   - Option A: open frontend/index.html directly in the browser
   - Option B: serve with a simple static server
     - python -m http.server 3000 --directory frontend
     - Open http://localhost:3000

Notes
- This is a minimal scaffold meant for demos and learning. For production, use proper packaging, dependency management, and a production-ready server for the backend (e.g., gunicorn, uvicorn) and a build tool for the frontend.
