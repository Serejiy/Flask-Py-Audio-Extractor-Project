# 🎵 Audio Extractor

A web application that extracts audio tracks from video files, built with Python and Flask.

## Features

- Upload video files via browser interface
- Extract audio from uploaded videos
- Download extracted audio directly from the browser
- User data managed with a database (SQLAlchemy)

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python 3, Flask |
| Database | SQLAlchemy (SQLite) |
| Frontend | HTML, CSS |
| Version Control | Git |

## Project Structure

```
Audio-Extractor-Project/
├── app/               # Application logic
├── migrations/        # Database migrations (Flask-Migrate)
├── config.py          # App configuration
├── run.py             # Entry point
└── requirements.txt   # Dependencies
```

## Getting Started

### Prerequisites
- Python 3.8+
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/Serejiy/Audio-Extractor-Project.git
cd Audio-Extractor-Project

# Install dependencies
pip install -r requirements.txt

# Run the application
flask run
```

Open your browser and go to `http://localhost:5000`

## What I Learned

- Building web applications with Flask
- Working with databases using SQLAlchemy and Flask-Migrate
- Handling file uploads and processing in Python
- Structuring a multi-file Python project
