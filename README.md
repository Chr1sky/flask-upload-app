# Installation

```
python -m venv venv
source venv/bin/activate  # na systemie Windows użyj: venv\Scripts\activate
pip install -r requirements.txt
```

## Run app

```
python run.py
```

## Using Docker

Build image

```
docker build -t flask-upload-app .
```

Run container

```
docker run -d -p 5000:5000 flask-upload-app
```