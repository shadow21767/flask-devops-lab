# Flask DevOps Lab

A diagnostic Flask application used to practice Git, GitHub, Docker, and Docker Compose workflows.

## Usage

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

## API Endpoints

- `/api/health` returns the application health status.
- `/api/config` returns the application configuration.
- `/api/report` returns hostname, Python version, and uptime information.
