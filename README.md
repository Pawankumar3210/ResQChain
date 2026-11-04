# 🚨 ResQChain

> **AI-Powered Resilient Supply Chain for Emergency Logistics**

ResQChain helps emergency responders get critical supplies to the right place at the right time, even when roads close, routes fail or disruptions strike. It prioritizes deliveries, finds the best route, detects disruptions and predicts risks using AI.

Built for the **Build With AI – Google for Developers** hackathon.

🌐 **Live Demo:** [resqchain-omega.vercel.app](https://resqchain-omega.vercel.app)
⚙️ **Backend API:** [resqchain-production.up.railway.app](https://resqchain-production.up.railway.app)

---

## ✨ Features

- 📦 **Delivery Priority Engine** — Ranks emergency deliveries by urgency and criticality
- 🗺️ **Smart Routing** — Finds the shortest and safest path using Dijkstra's algorithm
- ⚠️ **Disruption Detection** — Detects blocked or risky routes and reroutes automatically
- 🤖 **Gemini AI Prediction** — Predicts supply chain risks and suggests actions
- 🛟 **AI Fallback Mode** — Keeps working with rule-based logic if the AI quota is exhausted
- 🖥️ **JARVIS-Style HUD Dashboard** — Dark cyan futuristic interface with boot animation, Arc Reactor and live clock
- 📜 **Audit-Style Activity Log** — Every action is logged in the sidebar

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js |
| Backend | FastAPI (Python) |
| AI | Google Gemini API |
| Routing | Dijkstra's Algorithm |
| Data | Firebase, Python ML |
| Deployment | Vercel (frontend), Railway (backend) |

---

## 📁 Project Structure

```
ResQChain/
├── backend/
│   ├── main.py
│   └── routes/
├── frontend/
│   ├── public/
│   └── src/
└── README.md
```

---

## 🚀 Getting Started

### Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

Create a `.env` file inside `backend/`:

```env
GEMINI_API_KEY=your_gemini_api_key
```

### Frontend

```bash
cd frontend
npm install --legacy-peer-deps
npm start
```

Open [http://localhost:3000](http://localhost:3000).

---

## 🌍 SDG Alignment

- **SDG 9** — Industry, Innovation and Infrastructure
- **SDG 11** — Sustainable Cities and Communities
- **SDG 13** — Climate Action

---

## 🌐 Deployment

- **Backend:** Railway (FastAPI, port 8080)
- **Frontend:** Vercel (Create React App)

---

<div align="center">
  <strong>Built to keep help moving when it matters most.</strong>
</div>
