# HeatCode.io

> **Status:** 🚧 Work in Progress (started September 2025)  
> **Goal:** A web application with a ChatGPT-like interface that helps college students master **Data Structures & Algorithms** and **LeetCode-style** problems.

---

## 📜 Overview
HeatCode.io is an upcoming **DSA/LeetCode tutor** built around the [DeepSeek API](https://deepseek.com/) acting as an intelligent agent.  
The app aims to provide:
- **Conversational learning** – ask questions just like you would with ChatGPT.
- **Step-by-step guidance** – hints and explanations instead of instant full solutions.
- **Topic coverage** – from arrays and trees to advanced graph algorithms.
- **LeetCode-style practice** – designed to help students prepare for coding interviews.

This project is at a **very early stage**. Core features, UI/UX, and deployment details will evolve rapidly.

---

## 🏗️ Tech Stack (planned)
| Layer | Tools |
|-------|-------|
| Frontend | Next.js / React (TBD) |
| Backend | Django + Django REST Framework |
| AI Agent | DeepSeek API |
| Database | PostgreSQL (planned) |
| Hosting | TBD (e.g., Vercel + Railway) |

> *Note:* The stack may change as development progresses.

---

## 🚀 Local Development (initial skeleton)
```bash
# Clone the repo
git clone https://github.com/gkuchar/HeatCode.git
cd HeatCode/backend

# Create and activate a virtual environment
python -m venv env
.\env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply database migrations (once Django is wired up)
python manage.py migrate

# Run the development server
python manage.py runserver
