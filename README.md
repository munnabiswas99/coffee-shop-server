# ☕ Coffee Shop Server

Backend API for Coffee Shop application built with **Node.js, Express, and MongoDB**.

---

## 🚀 Live API

🔗 https://coffee-store-server-rho-navy.vercel.app

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB Atlas
* CORS
* dotenv
* Vercel (Deployment)

---

## 📌 API Endpoints

### ☕ Coffee Routes

| Method | Endpoint     | Description       |
| ------ | ------------ | ----------------- |
| GET    | /coffees     | Get all coffees   |
| GET    | /coffees/:id | Get single coffee |
| POST   | /coffees     | Add coffee        |
| PUT    | /coffees/:id | Update coffee     |
| DELETE | /coffees/:id | Delete coffee     |

---

### 👤 User Routes

| Method | Endpoint   | Description |
| ------ | ---------- | ----------- |
| POST   | /users     | Create user |
| GET    | /users     | Get users   |
| DELETE | /users/:id | Delete user |

---

## 📦 Installation

Clone repository:

```
git clone https://github.com/munnabiswas99/coffee-shop-server.git
```

Go to project folder:

```
cd coffee-shop-server
```

Install dependencies:

```
npm install
```

Run server:

```
node index.js
```

---

## 🔐 Environment Variables

Create `.env` file:

```
DB_USER=your_mongodb_username
DB_PASS=your_mongodb_password
```

---

## 🌍 CORS Configuration

```
app.use(cors());
```

---

## 🗄️ Database

* MongoDB Atlas
* Database Name: `coffeeDB`
* Collections:

  * coffees
  * users

---

## 🚀 Deployment

* Hosted on Vercel
* Uses Serverless Functions

---

## 👨‍💻 Author

Munna Biswas

---

## 📜 License

This project is open-source and free to use.
