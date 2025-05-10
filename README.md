📚 Quotenator API
Quotenator API is a simple RESTful API that serves random quotes. Ideal for apps, websites, or extensions that want to deliver inspiring, thoughtful, or fun quotes to users. Lightweight, fast, and easy to extend!

🚀 Features
Get a random quote with a single request

Easily extendable with more quotes or categories

CORS-enabled — ready to be used in frontend apps or browser extensions

Built with Python (FastAPI) for speed and simplicity

🛠️ Tech Stack
Python 3.9+

FastAPI

Uvicorn (for running the server)

📦 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/quotenator-api.git
cd quotenator-api
Create a virtual environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
▶️ Running the API
Use Uvicorn to start the server:

bash
Copy
Edit
uvicorn main:app --reload
The API will be live at:
http://127.0.0.1:8000

📚 API Endpoints
✅ Get a Random Quote
pgsql
Copy
Edit
GET /quote
Response:

json
Copy
Edit
{
  "quote": "The only way to do great work is to love what you do.",
  "author": "Steve Jobs"
}
💡 Example Use Cases
Chrome extensions (e.g., show a random quote on every new tab)

Daily quote widgets in mobile apps

Motivation or learning platforms

Personal dashboards

🤝 Contributing
Got more quotes to add? Ideas for features like categories or tags? Contributions are welcome! Feel free to fork this repo and send a pull request.

📄 License
This project is licensed under the MIT License.

🌐 Live Demo
You can try the live API here:
(https://quotenatorapi.onrender.com/randomQuote) <!-- Remove if you don’t have this yet -->
