# 🧮 Web-Based Calculator – `web-calci`

This is a simple web-based calculator application built using **Python** and **Flask**. The app supports basic arithmetic operations — addition, subtraction, multiplication, and division — with a clean web UI. It is containerized using **Docker** for easy deployment.

---

## 🚀 Features

- Web UI for basic calculations
- Addition, Subtraction, Multiplication, Division
- Python Flask backend
- Containerized with Docker
- Lightweight and easy to deploy

---

## 📸 Demo

![Calculator UI Screenshot](docs/demo.png) <!-- Add a screenshot here later if desired -->

---

## 🛠️ Tech Stack

- **Backend:** Python 3, Flask
- **Frontend:** HTML5, CSS3
- **Containerization:** Docker

---

## 🧑‍💻 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/gksankili/web-calci.git
cd web-calci
```
### 2. Run Locally (without Docker)
```bash
python3 -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```
🐳 Run with Docker
### 3. Build the Docker Image
```bash
docker build -t web-calci .
```
### 4. Run the Docker Container
```bash
docker run -d -p 5000:5000 --name web-calci-app web-calci
```
Open http://localhost:5000 in your browser.

🐳 Docker Commands
```bash
| Task             | Command                                                                  |
|------------------|--------------------------------------------------------------------------|
| Build image      | `docker build -t web-calci .`                                            |
| Run container    | `docker run -d -p 5000:5000 --name web-calci-app web-calci`              |
| Stop container   | `docker stop web-calci-app`                                              |
| Start container  | `docker start web-calci-app`                                             |
| Remove container | `docker rm -f web-calci-app`                                             |
| View containers  | `docker ps`                                                              |
```

📁 Project Structure
```bash
web-calci/
├── app.py                 # Flask application logic
├── requirements.txt       # Python dependencies
├── Dockerfile             # Docker build config
├── .gitignore             # Ignored files and folders
├── README.md              # Project documentation
└── templates/
    └── index.html         # Frontend HTML template
```

📝 License
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
This project is open source and available under the MIT License.

🙋‍♂️ Author
gksankili


