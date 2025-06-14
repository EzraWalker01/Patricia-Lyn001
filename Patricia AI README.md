# Patricia-Lyn001: A Sophisticated AI Chatbot

Patricia-Lyn001 is a simple AI-powered chatbot written in Python. It uses `scikit-learn` and `nltk` to classify user intents and provide context-aware responses.

## Features

- Intent recognition using a logistic regression model.
- Easily editable intent-response list via `data/intents.json`.
- Modular and understandable codebase.

## Project Structure
├── app.py
├── chatbot/
│ ├── init.py
│ ├── core.py
│ ├── model.py
│ └── utils.py
├── data/
│ └── intents.json
├── requirements.txt
## Setup

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
pip install -r requirements.txt
python app.py
