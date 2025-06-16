# testssl-web

**TestSSL Web** is a web-based tool built with Flask to perform SSL analysis and testing based on Spanish' methodologies. It provides a simple interface to run checks and display results in the browser.

**User Disclaimer**: The results are automatically filtered by CCN-STIC-807 and CCN-STIC-221.

## Features

- Web interface for running SSL tests
- Built with Python and Flask
- Simple frontend using HTML and CSS
- Designed for local use or cloud deployment

## Requirements

- Python 3.8+
- pip
- testssl.sh
- Ubuntu / Linux environment

## Installation for instant deployment

Clone the repository:

```bash
git clone https://github.com/pr3y3s/testssl-web.git
cd testssl-web
```

Runing the App locally
```bash
python3 app.py
```
⚠️ Note: The file "requirements.txt" is not mandatory to follow with the execution. If any of the previous steps throws an error or the app does not work, please, install the requirements:
```bash
python -m venv venv
```
```bash
source venv/bin/activate
```
```bash
pip install requirements.txt
```
```bash
python3 app.py
```

Then open your browser at http://localhost:5000 and type the URL to be analyzed!

⚠️ Note: This tool has some sensitive to the input URL. Please, note that the URL must be introduced without "https://" or withouth any slash (/) at the end of the chaintext.

## LICENSE
This project is for educational and personal use. Not intended for commercial deployment :D.
