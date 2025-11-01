# Phishing Detection Backend API

Flask-based backend for phishing URL detection using machine learning.

## Deployment

This backend is deployed on Railway.

## API Endpoints

- `GET /` - API information
- `GET /health` - Health check
- `GET /metrics` - Model performance metrics
- `POST /predict` - Predict if URL is phishing

## Local Development

```bash
pip install -r requirements.txt
python app.py
```

Server runs on http://localhost:5000
