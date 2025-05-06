# 🏍️ Bikers Network

Developed a bike service web application with modules for user sign-up and login, booking services, and contacting support,and also prefer sloting prefernce using React, Vite, Express.js, and MongoDB.

---

## 🚀 Features

- 🧾 Add, view, and update bike services
- 📅 Users can book bike services
- 💳 View all payments and booking details
- 📬 Contact message handling
- 🧭 React Router for navigation
- 🌐 RESTful API using Express and MongoDB
- 🐳 Docker support for both frontend and backend

---

---

## ⚙️ Tech Stack

| Frontend | Backend | Database | Deployment |
|----------|---------|----------|------------|
| React    | Express | MongoDB  | Docker     |
| Tailwind | Node.js | Mongoose | Docker-Compose |

---

## 🐳 Docker Setup

Ensure you have Docker installed. Then:

# Clone the repo

```
git clone git@github.com:MAVeny426/The-Bikers-Network.git
```

```
cd UI
```
## Setup Backend (Express)

```
cd server
```

```
npm install
```

## Create .env file in server

```
PORT=5000
MONGO_URI=mongodb://mongo:27017/bikersdb
```
## Setup frontend

```
cd frontend
```


```
npm install
```

# Start containers

```
docker-compose up --build
```
