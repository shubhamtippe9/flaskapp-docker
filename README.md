# 🚀 Flask App with Docker

A simple **Flask web application** containerized using **Docker**, demonstrating how to build, run, and deploy a Python app in a containerized environment.

---

## 📌 Project Overview

This project shows how to:

- Build a Flask application 🐍
- Containerize it using Docker 🐳
- Run the app inside a container
- Expose the app via a browser

---

## 🏗️ Project Structure

```
flaskapp-docker/
│── app.py
│── requirements.txt
│── Dockerfile
│── README.md
```

---

## ⚙️ Prerequisites

Make sure you have installed:

- Python (3.x)
- Docker

---

## ▶️ Run Locally (Without Docker)

1. Clone the repository:
```bash
git clone https://github.com/shubhamtippe9/flaskapp-docker.git
cd flaskapp-docker
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Flask app:
```bash
python app.py
```

4. Open in browser:
```
http://localhost:32768
```

---

## 🐳 Run Using Docker

### 1. Build Docker Image
```bash
docker build -t flask-app .
```

### 2. Run Docker Container
```bash
docker run -d -P flask-app
```

### 3. Access Application
```
http://localhost:32768
```

---

## 📦 Dockerfile Explanation

- Uses Python base image
- Sets working directory
- Copies application files
- Installs dependencies
- Runs Flask app

---

## 📡 Features

- Simple Flask web server
- Lightweight and fast
- Easy Docker integration

---

## 🔧 Useful Docker Commands

```bash
docker ps
docker ps -a
docker stop <container_id>
docker rm <container_id>
docker images
```

---

## 🌐 Future Improvements

- Add REST APIs
- Integrate database (MySQL / MongoDB)
- Deploy on AWS (EC2 / ECS)
- Add CI/CD pipeline

---

## 👨‍💻 Author

**Shubham Tippe**  
Cloud & DevOps Learner 

🔗 GitHub: https://github.com/shubhamtippe9  
💼 LinkedIn: https://www.linkedin.com/in/shubhamtippe9/  
📧 Email: shubhamtippe9@gmail.com  

---

## 📜 License

This project is for educational and learning purposes.

## ⭐ Support

If you like this project:

- ⭐ Star this repo  
- 🍴 Fork it  
- 🛠️ Contribute  
