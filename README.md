# Legal AI Coach

Empowering self-represented litigants in dependency and family law with AI-powered case management, document handling, goal tracking, evidence upload, chat history, and personalized legal insights.

---

## Project Overview

Legal AI Coach is a modular web application with:
- **Frontend:** React (dashboard, goals, timeline, documents, chats, evidence)
- **Backend:** FastAPI (Python; API endpoints for all features, AI agent integration, authentication, database management)
- **AI Integrations:** Gemini 2.0 (initial), Lexis+, Harvey (future)
- **File/Data Storage:** Local/cloud options for documents and evidence

---

## Folder Structure

```plaintext
frontend/
├── src/
│   ├── components/
│   │   ├── Goals/
│   │   ├── Timeline/
│   │   ├── Documents/
│   │   ├── Evidence/
│   │   ├── Chats/
│   │   └── Layout/
│   ├── pages/
│   ├── hooks/
│   ├── context/
│   ├── styles/
│   ├── App.jsx
│   ├── index.js
├── public/
│   └── index.html
├── package.json
└── README.md

backend/
├── app.py
├── models.py
├── schemas.py
├── crud.py
├── ai/
│   ├── agent.py
│   ├── prompts.py
├── api/
│   ├── auth.py
│   ├── goals.py
│   ├── timeline.py
│   ├── documents.py
│   ├── chats.py
│   ├── evidence.py
│   └── ai.py
├── database.py
├── config.py
├── requirements.txt
└── README.md
```

---

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/legal-ai-coach.git
   cd legal-ai-coach
   ```

2. **Set up the backend**
   - Install Python dependencies:
     ```bash
     cd backend
     pip install -r requirements.txt
     ```
   - Run the FastAPI server:
     ```bash
     uvicorn app:app --reload
     ```
   - Test at [http://localhost:8000/docs](http://localhost:8000/docs)

3. **Set up the frontend**
   - Install Node dependencies:
     ```bash
     cd frontend
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```

---

## Support & Learning Resources

- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [React Documentation](https://react.dev/)
- [GitHub Docs](https://docs.github.com/en)
- [VS Code for Beginners](https://www.youtube.com/watch?v=VqCgcpAypFQ)
- [Stack Overflow](https://stackoverflow.com/)

---

## Contributing

Open to collaboration and improvements. Please open issues or PRs for feature requests, bug fixes, or suggestions!

---
