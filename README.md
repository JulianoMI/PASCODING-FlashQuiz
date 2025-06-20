PREVIEW OF WEBSITE
![Screenshot 2025-05-30 151345](https://github.com/user-attachments/assets/998cfed4-1fe0-4032-af4f-8c1b1a3cdac5)

# FlashQuiz

FlashQuiz is a web-based flashcard application that helps users learn and memorize information through interactive flashcards. It supports both learners and content creators, allowing creators to make custom flashcard decks and learners to study them.

## Features

- User authentication (login/register)
- Create, edit, and delete flashcard decks
- Interactive flashcard study sessions
- Progress tracking for learners
- Analytics for content creators
- Explore public flashcard decks

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Git

## Installation

1. Clone the repository:
```bash
git clone https://github.com/JulianoMI/PASCODING-FlashQuiz.git
cd PASCODING-FlashQuiz
```

2. Create a virtual environment:
```bash
python -m venv .venv
```

3. Activate the virtual environment:
- On Windows:
```bash
source .venv/Scripts/activate
```
- On macOS/Linux:
```bash
source .venv/bin/activate
```

4. Install the required packages:
```bash
pip install -r requirements.txt
```

## Configuration

1. Create a `.env` file in the project root with the following content:
```
FLASK_APP=run.py
FLASK_ENV=development
SECRET_KEY=your-secret-key-here
DATABASE_URL=sqlite:///instance/flashquiz.db
```

Replace `your-secret-key-here` with a secure secret key.

## Running the Application

1. Make sure your virtual environment is activated
2. Run the development server:
```bash
flask run
```
3. Open your web browser and navigate to `http://localhost:5000`

## User Roles

The application supports two types of users:
- **Learners**: Can study flashcard decks and track their progress
- **Creators**: Can create and manage flashcard decks, view analytics

