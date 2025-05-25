## 📝 **README.md for Blogger Website Using MERN**

````markdown
# 📝 Blogger Website Using MERN Stack

This is a full-stack blogging web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The platform allows users to **create, post, edit, and manage blogs** with the option to upload images using **Multer**. It also includes user **registration/login**, and a **contact page** for user interaction.

---

## 🌐 Features

- 🔐 **User Registration & Login**  
  Secure user authentication with session or token handling.

- ✍️ **Create and Post Blogs**  
  Users can create a new blog with a title, content, and an optional image.

- 🖼️ **Image Upload**  
  Blog posts support uploading images via **Multer**.

- 🛠️ **Edit and Delete Blogs**  
  Users can edit existing blog content or delete posts they’ve created.

- 📄 **Contact Page**  
  Dedicated contact form for user messages or queries.

- 📚 **Responsive Frontend UI**  
  Built using **React**, styled using **CSS/Bootstrap**.

---

## ⚙️ Technologies Used

### Frontend:
- ⚛️ React.js
- CSS3
- Bootstrap

### Backend:
- 🟢 Node.js
- 🌐 Express.js
- ☁️ Multer (for file/image upload)

### Database:
- 🍃 MongoDB (NoSQL)

---

## 📁 Project Structure

```bash
blogger-website/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── uploads/               # Stores uploaded images
│   ├── .env
│   ├── server.js              # Entry point for Express app
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.jsx
│   │   │   ├── BlogForm.jsx
│   │   │   ├── BlogList.jsx
│   │   │   ├── Contact.jsx
│   │   │   ├── Register.jsx
│   │   │   └── Login.jsx
│   │   ├── App.js
│   │   ├── index.js
│
├── package.json               # Node dependencies
└── README.md
````

---

## 🚀 Getting Started

### 🔧 Prerequisites

* Node.js & npm
* MongoDB (Local or Atlas)
* Git

---

### 📦 Installation

#### 1. Clone the repository

```bash
git clone https://github.com/your-username/blogger-website.git
cd blogger-website
```

#### 2. Install backend dependencies

```bash
cd backend
npm install
```

#### 3. Install frontend dependencies

```bash
cd ../frontend
npm install
```

#### 4. Setup MongoDB

Make sure MongoDB is running locally or update your MongoDB URI in `.env`:

```env
MONGO_URI=your_mongodb_connection_string
```

#### 5. Run the app

* Backend:

  ```bash
  cd backend
  npm start
  ```

* Frontend:

  ```bash
  cd frontend
  npm start
  ```

Visit `http://localhost:3000` to use the app.

---

## 📸 Screenshots 

Include screenshots of your UI here for better clarity.

---

## 🤝 Contribution

Contributions are welcome! Feel free to submit issues or pull requests.

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

## ✨ Author

**\[Your Name]**
GitHub: [@moniieekaa](https://github.com/moniieekaa)

```
