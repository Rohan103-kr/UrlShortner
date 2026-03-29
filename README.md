# 🔗 URL Shortener (Node.js + Express + MongoDB)

A simple and functional **URL Shortener Web Application** built using **Node.js, Express, MongoDB, and EJS**.
It allows users to generate short links from long URLs and redirects them efficiently.

---

## 🚀 Features

* 🔗 Generate short URLs from long links
* 🔁 Redirect short URLs to original URLs
* 💾 Store URLs in MongoDB
* ⚡ Fast and lightweight backend
* 🖥️ Simple UI using EJS

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose)
* **Frontend:** EJS, HTML
* **Utility:** NanoID (for generating short codes)

---

## 📂 Project Structure

```
Project_1/
│── controllers/
│   └── url.js          # Handles URL creation logic
│── models/
│   └── url.js          # MongoDB schema
│── views/
│   └── index.ejs       # Frontend UI
│── server.js           # Main server file
│── package.json
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/url-shortener.git
cd url-shortener
```

### 2. Install dependencies

```
npm install
```

### 3. Start MongoDB

Make sure MongoDB is running locally:

```
mongod
```

### 4. Run the server

```
nodemon server.js
```

### 5. Open in browser

```
http://localhost:3000
```

---

## 🔄 How It Works

1. User enters a long URL
2. Server generates a short code using NanoID
3. URL is saved in MongoDB
4. Short URL is displayed
5. On visiting short URL → user is redirected to original link

---

## 📸 Example

* Input:
  `https://www.apple.com/in/iphone/`

* Output:
  `http://localhost:3000/9rxheMKRb`

---

## ⚠️ Current Limitations

* No user authentication
* No analytics (click count not tracked yet)
* Basic UI (no styling framework used)

---

## 🚀 Future Improvements

* 📊 Click tracking & analytics
* 📋 Copy-to-clipboard feature
* 📜 Dashboard to view all URLs
* ✏️ Custom short URLs
* 🎨 UI improvement using Tailwind CSS
* 🌐 Deployment (Render / Vercel)

---

## 👨‍💻 Author

**Rohan Kumar Vaishya**
GitHub: https://github.com/Rohan103-kr

---

## 📜 License

This project is open-source and free to use.
