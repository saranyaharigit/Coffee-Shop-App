# Coffee App

Small example coffee shop app with two interfaces:
- Terminal (Python) version: main.py / Untitled-1.py
- Web (HTML/JS) version: index.html

## Files
- main.py (or Untitled-1.py) — CLI Python app (order, view, checkout)
- index.html — Web UI (menu, cart, checkout)
- README.md — this file

## Features
- Browse menu, add items to cart
- View order summary and total
- Clear cart and checkout

## Requirements
- Python 3.8+ (for serving the web UI with a simple HTTP server)
- Modern web browser for index.html

## Run — Python CLI
1. Open PowerShell in project folder:
   cd "c:\Users\harisaranya\Downloads\coffee app"
2. Run:
   & C:/Users/harisaranya/AppData/Local/Programs/Python/Python313/python.exe "c:\Users\harisaranya\Downloads\coffee app\main.py"
   or simply:
   python main.py

## Run — Web UI (two options)
Option A — Open file directly:
- Double-click index.html or open it in the browser.

Option B — Serve with a local HTTP server (recommended):
1. In PowerShell, run:
   cd "c:\Users\harisaranya\Downloads\coffee app"
   python -m http.server 8000
2. Open: http://localhost:8000/index.html

Note: If you get 404 for `index%20.%20html`, rename the file to remove spaces:
```powershell
Rename-Item "index . html" "index.html"
```

## Quick usage
- Add items from menu → they appear in the order
