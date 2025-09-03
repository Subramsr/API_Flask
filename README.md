# Public Flask API Example

This is a simple public Flask API application, ready to be containerized with Docker and pushed to GitHub.

## Features
- One endpoint: `/api/hello` (GET) returns a JSON hello message.
- Dockerfile for easy containerization.

## Getting Started

### Local Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Start the app:
   ```bash
   python app.py
   ```
3. Visit [http://localhost:5000/api/hello](http://localhost:5000/api/hello)

### Docker Run
1. Build the image:
   ```bash
   docker build -t flask-api-demo .
   ```
2. Run the container:
   ```bash
   docker run -p 5000:5000 flask-api-demo
   ```
3. Visit [http://localhost:5000/api/hello](http://localhost:5000/api/hello)

---

You can now push this project to your GitHub repository and start experimenting!
