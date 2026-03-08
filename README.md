# Simple FastAPI Hello API

## Requirements
- Python 3.10+
- `pip`

## Setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run the server
```bash
uvicorn main:app --reload
```

The API will be available at `http://127.0.0.1:8000`.

## Endpoint
- `GET /hello` → `{"message":"hello"}`
