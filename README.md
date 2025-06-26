
# 🩺 Diabetes Tracker CLI

A simple, extensible command-line app to help diabetics log and view their blood sugar levels. Built with Python, Typer, and SQLite. Designed to grow into a full web app later.

---

## 🔧 Features

✅ Add blood sugar logs via CLI  
✅ View recent glucose readings  
✅ Automatically timestamps entries  
✅ Simple and fast – no setup required beyond Python  
⬜️ Upcoming: insulin logs, meal tracking, stats, CSV export  
⬜️ Future: FastAPI-based web interface with charts

---

## 📦 Tech Stack

- Python 3.10+
- [Typer](https://typer.tiangolo.com/) (CLI framework by FastAPI creator)
- SQLite (local storage)
- SQLAlchemy (ORM)
- Tabulate (for pretty CLI tables)

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/diabetes-tracker-cli.git
cd diabetes-tracker-cli
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 🩺 How to Use

### ➕ Add a New Blood Sugar Log
```bash
python cli.py add-glucose --level 120 --context "fasting"
```

### 📋 View Recent Logs
```bash
python cli.py show-logs --limit 5
```

---

## 📁 Project Structure

```
diabetes_cli/
├── cli.py          # CLI entry point using Typer
├── database.py     # SQLite DB setup
├── models.py       # SQLAlchemy models
├── crud.py         # Functions to add/view data
├── requirements.txt
```

---

## 📈 Roadmap

### ✅ MVP 1 – CLI App
- [x] Blood sugar log + view
- [ ] Insulin log
- [ ] Meal log
- [ ] Stats command (avg, min, max)
- [ ] Export logs to CSV

### 🚧 MVP 2 – Web API
- [ ] FastAPI-based backend
- [ ] Add users & auth
- [ ] View logs via browser
- [ ] Chart.js or Plotly graphs

---

## 🤓 Learning Goals

This project is also built as a learning experience to explore:
- CLI development with Typer
- Data modeling with SQLAlchemy
- Transitioning from CLI → API
- Deployment and database design

---

## 📃 License

MIT License © 2025 [Aimen Aberra]

---

## 💬 Feedback

Have suggestions or want to contribute? Open an issue or submit a PR!
