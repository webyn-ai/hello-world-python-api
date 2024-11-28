# Hello World Python API

This is a simple Python API built with Flask for demonstration purposes. It has two endpoints:

- `GET /hello` - Returns `{ "message": "Hello, World!" }`
- `GET /health` - Returns `{ "status": "ok" }`

## Requirements

- Python 3.8 or later

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/webyn-ai/hello-world-python-api.git
cd hello-world-python-api
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the app
```bash
python app.py
```

4. Access the API
- [`http://localhost:3000/hello`](http://localhost:3000/hello)
- [`http://localhost:3000/health`](http://localhost:3000/health)