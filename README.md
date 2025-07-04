# FastAPI Project

A simple FastAPI project with basic setup.

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the server:
```bash
python main.py
```

Or alternatively:
```bash
uvicorn main:app --reload
```

## API Endpoints

- `GET /`: Returns a Hello World message

## Documentation

Once the server is running, you can access:
- Interactive API documentation at `/docs`
- Alternative API documentation at `/redoc`