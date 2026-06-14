# Ajith A — Portfolio Website

A professional data analyst portfolio built with Python (Flask).

## Setup & Run

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run the app
python app.py

# 3. Open in browser
http://127.0.0.1:5000
```

## Project Structure

```
portfolio/
├── app.py                  # Flask app entry point
├── requirements.txt        # Python dependencies
├── README.md
├── templates/
│   └── index.html          # Main HTML template
└── static/
    ├── css/
    │   └── style.css       # All styles
    └── js/
        └── main.js         # Scroll animations & nav
```

## Deploy to the Web (Free)

### Option 1 — Render.com (Recommended)
1. Push this folder to a GitHub repo
2. Go to render.com → New → Web Service
3. Connect your GitHub repo
4. Set Start Command: `python app.py`
5. Deploy — you get a free public URL

### Option 2 — Railway.app
1. Push to GitHub
2. Go to railway.app → New Project → Deploy from GitHub
3. It auto-detects Flask and deploys

### Option 3 — PythonAnywhere (Free tier)
1. Upload files to pythonanywhere.com
2. Create a Web App → Flask → point to app.py
3. Free subdomain: yourusername.pythonanywhere.com

## Customise

- Edit personal details in `templates/index.html`
- Change colors in `static/css/style.css` under `:root`
- Update LinkedIn URL once you have your profile URL
