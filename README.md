# 🎓 Attendance-AI

### AI-powered Face Recognition Attendance System

An intelligent attendance management system that uses **InsightFace**, **OpenCV**, **Streamlit**, and **Supabase** to automatically recognize students from classroom videos and generate attendance reports in real time.

---

## 🚀 Features

- 👤 AI-based Student Registration
- 🎥 Face Recognition Attendance from Video
- 🧠 InsightFace Embedding Generation
- 📊 Attendance Dashboard & Reports
- 👥 Student Management System
- ⚠️ Unknown Face Conflict Resolver
- ☁️ Supabase Database Integration
- 📥 Attendance Report Export (CSV)
- 🌙 Modern Streamlit User Interface

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Frontend | Streamlit |
| Computer Vision | OpenCV, InsightFace |
| Face Recognition | Buffalo_L Model |
| Database | Supabase |
| Image Processing | NumPy, Pillow |
| Backend | Python |
| Deployment | Streamlit |

---

## 🔄 Project Workflow

1. Register a student with their face photo.
2. Generate a unique facial embedding using InsightFace.
3. Store student details and embedding in Supabase.
4. Start a lecture session.
5. Upload the classroom video.
6. Detect faces frame-by-frame.
7. Match detected faces with registered students.
8. Mark attendance automatically.
9. Resolve unknown faces manually if required.
10. Download the final attendance report as a CSV file.

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/Aman-shr2004/Attendance-AI.git
cd Attendance-AI
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

**Windows**

```bash
.venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Supabase

Create a file:

```
.streamlit/secrets.toml
```

Add:

```toml
SUPABASE_URL = "YOUR_SUPABASE_URL"
SUPABASE_KEY = "YOUR_SUPABASE_KEY"
```

### Run the Project

```bash
streamlit run app.py
```

---

## 📂 Project Structure

```text
Attendance-AI/
│── app.py                 # Main Streamlit application
│── database.py            # Supabase database operations
│── aligner.py             # Face alignment utilities
│── requirements.txt       # Python dependencies
│── ARCHITECTURE.md        # Project architecture
│── context.txt            # Project context
│── .streamlit/
│   └── config.toml
│── .gitignore
└── README.md
```

---

## 👨‍💻 Author

**Aman Sharma**

- 🎓 B.Tech Computer Science Engineering
- 💼 Aspiring AI & Python Developer
- 🌐 GitHub: https://github.com/Aman-shr2004

---

⭐ If you found this project useful, consider giving it a star!

---

