🐱 Cat Facts FastAPI Project

A simple FastAPI project that serves a profile endpoint and fetches a random cat fact dynamically from an external API.
This project demonstrates RESTful API design, JSON response formatting, and integration with third-party APIs.

🚀 Features

Returns your personal profile information (name, email, stack, etc.)

Fetches a random cat fact from an external API

Formats data into a structured JSON response

Handles errors gracefully

Ready for deployment on Fly.io, Railway, or Render

🧩 Project Structure
cat_facts_api/
│
├── main.py                # Entry point of the FastAPI app
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── __pycache__/           # Auto-generated cache files

⚙️ Setup Instructions
1. Clone the repository
git clone <your-repo-url>
cd cat_facts_api

2. Create and activate a virtual environment
# Install virtualenv if not installed
pip install virtualenv

# Create environment
python -m venv venv

# Activate environment
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Run the application
uvicorn main:app --host 0.0.0.0 --port 8000


Then visit:
👉 http://127.0.0.1:8000
 or http://0.0.0.0:8000
