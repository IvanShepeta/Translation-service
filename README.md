# Translation-service

A fast, simple backend service built with **FastAPI**, which allows users to submit text for translation into multiple target languages using an LLM or translation API.

---

## 🚀 Features
- Submit text and list of target languages for translation  
- Asynchronous task handling with background processing  
- Stores tasks and translations in a SQL database (via SQLAlchemy)  
- Provides REST API endpoints for creating translation tasks and retrieving results  
- Easily switch between actual translation service (e.g., OpenAI) or a mock/fallback for testing  
