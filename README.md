
# Quotenator API

Quotenator API is a simple RESTful API that serves random quotes.  
Ideal for apps, websites, or extensions that want to deliver inspiring or fun quotes to users.  
Lightweight, fast, and easy to extend.

## Features

- Get a random quote with a single request
- Easily extendable with more quotes or categories
- CORS-enabled — ready for frontend apps or browser extensions
- Built with Python (FastAPI) for speed and simplicity

## Tech Stack

- Python 3.9+
- FastAPI
- Uvicorn

## Live Demo

Example live URL:  
https://quotenatorapi.onrender.com/randomQuote

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/QuotenatorAPI.git
cd QuotenatorAPI
```

### 2. Create a virtual environment

#### On macOS/Linux:

```bash
python -m venv venv
source venv/bin/activate
```

#### On Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

## Running the API

Start the server using Uvicorn:

```bash
uvicorn main:app --reload
```

The API will be live at:  
http://127.0.0.1:8000

API docs will be available at:  
http://127.0.0.1:8000/docs

## API Endpoints

### Get a Random Quote

**Request:**

```
GET /randomQuote
```

**Response:**

```json
{
  "quote": "The only way to do great work is to love what you do.",
  "author": "Steve Jobs"
}
```

## Example Use Cases

- Chrome extensions (e.g., show a random quote on every new tab)
- Daily quote widgets in mobile apps
- Personal dashboards or productivity tools

## Contributing

Want to add more quotes or suggest features?  
Feel free to fork this repo and open a pull request.

## License

This project is licensed under the MIT License.
