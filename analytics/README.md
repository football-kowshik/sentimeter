# Analytics


## Setup

```bash
python3 -m venv venv
source venv/bin/activate

pip install --upgrade pip
pip install -r requirements.txt

pip freeze > requirements.txt
```

### Environment variables

Create the environment variable at `sentimeter/analytics/.env` with the following keys.

```
YOUTUBE_API_KEY=
GOOGLE_GENAI_API_KEY=
```