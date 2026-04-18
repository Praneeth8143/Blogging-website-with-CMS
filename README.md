# 🚀 BlogHub - Multi-User Blogging Platform

A modern blogging platform built with Flask, MongoDB, and Tailwind CSS where users can create blogs and admins review them before publishing.

---

## 📌 Features

### 👤 User Features

* Secure registration & login
* Create and submit blogs
* Select categories
* Track approval status
* Manage personal blogs

### 🛠️ Admin Features

* Admin dashboard
* Approve / reject blogs
* Manage users and content
* View platform statistics

### 🌐 Platform Features

* 8 predefined categories (Tech, Travel, Food, etc.)
* Responsive design (mobile + desktop)
* Real-time status updates
* Search & filter functionality

---

## 🧰 Tech Stack

* Backend: Flask (Python)
* Database: MongoDB
* Frontend: HTML, Tailwind CSS
* Authentication: Flask-Login, bcrypt

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/Praneeth8143/Blogging-Website-With-CMS
cd blogging-platform
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Setup Environment Variables

Create a `.env` file:

```env
SECRET_KEY=your-secret-key
MONGODB_URI=mongodb://localhost:27017/
```

### 4. Run MongoDB

```bash
mongod
```

### 5. Start Application

```bash
python app.py
```

App runs at: http://localhost:5000

---

## 🔄 Workflow

1. User registers and logs in
2. Creates blog → Pending
3. Admin reviews
4. Approved → Published
5. Rejected → Hidden

---

## 📂 Project Structure

```
blogging-platform/
│── app.py
│── config.py
│── requirements.txt
│── templates/
│── static/
```

---

## 🔐 Security

* Password hashing using bcrypt
* Secure sessions with Flask-Login
* Input validation

---

## 🚀 Future Improvements

* Comments system
* Likes and shares
* Rich text editor
* User profiles

---

## 📜 License

MIT License

