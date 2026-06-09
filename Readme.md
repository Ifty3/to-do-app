To-Do Application (Node.js + Docker)






🚀 Project Overview

This is a simple To-Do Application built using Node.js (Express) and containerized using Docker.
The app allows users to:

➕ Add tasks
👀 View tasks
❌ Delete tasks

The entire application is packaged inside a Docker image so it can run on any system without manual setup.

🧱 Tech Stack
🟢 Node.js
⚡ Express.js
🌐 HTML, CSS, JavaScript
🐳 Docker
📁 Project Structure
todo-app/
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── server.js
├── package.json
└── Dockerfile

⚙️ Setup & Run (Local)
1️⃣ Install dependencies
npm install
2️⃣ Run application
node server.js

👉 Open in browser:

http://localhost:3000


🐳 Run with Docker
1️⃣ Build image
docker build -t todo-app .
2️⃣ Run container
docker run -p 3000:3000 todo-app

☁️ Docker Hub Deployment
🔐 Login
docker login
🏷️ Tag image
docker tag todo-app sufian87/todo-app
🚀 Push image
docker push sufian87/todo-app

📥 Pull & Run
docker pull yourusername/todo-app
docker run -p 3000:3000 yourusername/todo-app

🧩 Docker Commands Used
docker build → Create image
docker run → Run container
docker ps → Check running containers
docker stop → Stop container
docker login → Login to Docker Hub
docker push → Upload image
docker pull → Download image


🌟 Features

✔ Add tasks
✔ View tasks
✔ Delete tasks
✔ Fully containerized
✔ Portable across systems

🖼️ Concept

Application + Dependencies + Runtime → Docker Image → Run Anywhere 🌍
