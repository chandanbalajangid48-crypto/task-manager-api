# Task Manager API

This is a simple backend project I built to practice FastAPI and database operations. It’s a Task Manager API where you can create, view, update, and delete tasks.

## What it does
- Add new tasks
- View all tasks
- Update existing tasks
- Delete tasks
- Stores data permanently using SQLite

## Tech used
- FastAPI
- SQLAlchemy
- SQLite
- Python

## API routes
- GET /tasks
- POST /tasks
- PUT /tasks/{task_id}
- DELETE /tasks/{task_id}

## How to run it

```bash
uvicorn app.main:app --reload
