<<<<<<< HEAD
# StudyBud

A Django-based web application for finding study partners, creating rooms, and collaborating on learning topics.

## Features
- User registration and authentication
- Create, update, and delete study rooms
- Join rooms and participate in conversations
- Browse topics and recent activities
- User profile with bio and avatar
- REST API endpoints for rooms

## Setup Instructions

### 1. Clone the repository
```
git clone <your-repo-url>
cd studybud
```

### 2. Create and activate a virtual environment
```
python -m venv env
env\Scripts\activate  # On Windows
```

### 3. Install dependencies
```
pip install -r requirements.txt
```

### 4. Apply migrations
```
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the development server
```
python manage.py runserver
```

### 6. Access the app
Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Project Structure
- `base/` - Main Django app (models, views, templates)
- `static/` - Static files (CSS, JS, images)
- `templates/` - Base HTML templates
- `env/` - Virtual environment
- `db.sqlite3` - SQLite database

## API Endpoints
- `/api/rooms/` - List all rooms (GET)
- `/api/rooms/<id>/` - Get room details (GET)

## License
MIT
=======
# Studybud
>>>>>>> fdc4e7cec4548e4e7cffb71ff607d976575f89fe
