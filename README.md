# Flask Hello World App

A simple Hello World application built with Flask.

## Setup

1. Create a virtual environment:
```bash
python3 -m venv venv
```

2. Activate the virtual environment:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the App

```bash
python app.py
```

The app will be available at:
- Main page: http://localhost:5000/
- API endpoint: http://localhost:5000/api/hello

## Docker Setup

1. Build the Docker image:
```bash
docker build -t flask-hello-world .
```

2. Run the container:
```bash
docker run -p 5001:5001 flask-hello-world
```

The app will be available at http://localhost:5001/

## Requirements
- Python 3.7+
- Flask 3.0.0
- Docker (for containerized deployment)
