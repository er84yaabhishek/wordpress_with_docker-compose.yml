# WordPress with Docker Compose

This project sets up a **WordPress + MySQL + phpMyAdmin** environment using **Docker Compose**.
No custom Dockerfile is required — official images are used.

---

## 📁 Project Structure

```text
wordpress-project/
├── docker-compose.yml
├── .env
├── wordpress/
│   └── wp-content/
│       ├── plugins/
│       ├── themes/
│       └── uploads/
├── mysql/
│   └── data/
└── README.md

🚀 Getting Started
1️⃣ Start the containers
docker-compose up -d

2️⃣ Access services
Service	URL
WordPress	http://localhost:8080

🔐 phpMyAdmin Login Details
Server: mysql
Username: root
Password: rootpass

🛑 Stop & Restart Containers

Stop containers:

docker-compose down

Start again:

docker-compose up -d













phpMyAdmin	http://localhost:8081
