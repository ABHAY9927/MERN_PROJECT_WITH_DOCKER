# 🚀 MERN Project with Docker

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) application fully containerized using Docker and Docker Compose.

---

## 📌 Features

* Full-stack MERN application
* Dockerized frontend and backend
* MongoDB container integration
* One-command setup using Docker Compose
* Production-ready structure

---

## 🛠️ Tech Stack

* Frontend: React.js
* Backend: Node.js, Express.js
* Database: MongoDB
* DevOps: Docker, Docker Compose

---

## 📂 Project Structure

```
proshop_mern/
│── backend/
│── frontend/
│── docker-compose.yml
│── README.md
```

---

## 🐳 Docker Setup

### 🔧 Prerequisites

Make sure Docker and Docker Compose are installed on your system.

---

### ▶️ Run the Application

```bash
docker-compose up -d
```

This will:

* Pull required images (if not available)
* Build containers (if needed)
* Start frontend, backend, and MongoDB services

---

### 🛑 Stop the Application

```bash
docker-compose down
```

---

## 🌐 Application URLs

* Frontend: http://localhost:3000
* Backend API: http://localhost:5000

---

## 📦 Docker Images

The application uses the following Docker images:

* Frontend Image: `abhaylove/mern-frontend`
* Backend Image: `abhaylove/mern-backend`
* Database Image: `mongo` (official image from Docker Hub)

---

## 🔗 How It Works

* Frontend communicates with backend using API calls
* Backend connects to MongoDB using Docker network
* All services are managed via Docker Compose
* No need for manual setup or dependency installation

---

## 🚀 Deployment

1. Clone the repository:

```bash
git clone https://github.com/ABHAY9927/MERN_PROJECT_WITH_DOCKER.git
```

2. Navigate to project folder:

```bash
cd MERN_PROJECT_WITH_DOCKER
```

3. Run the project:

```bash
docker-compose up -d
```

4. Open in browser:

```
http://localhost:3000
```

---

## ⚠️ Notes

* Ensure ports 3000, 5000, and 27017 are free
* `.env` files are not included for security reasons
* MongoDB runs inside a Docker container

---

## 👨‍💻 Author

**Abhay Kumar**

---

## ⭐ Acknowledgement

This project is based on learning and implementation of MERN stack and Docker containerization.
