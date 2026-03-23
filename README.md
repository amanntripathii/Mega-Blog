# 🚀 Mega Blog Platform

A modern full-stack blogging platform where users can create, edit, and manage blogs with authentication, media uploads, and a clean UI.

---

## 📌 Features

* ✍️ Create, edit, delete blog posts
* 🔐 Authentication (Login / Signup)
* 🖼️ Image upload & storage
* 🧾 Rich text blog editor
* 📱 Responsive UI
* ⚡ Fast and optimized performance

---

## 🛠️ Tech Stack

**Frontend**

* React.js
* Tailwind CSS
* React Router

**Backend / Services**

* Appwrite (Auth, Database, Storage)

---

## 📂 Project Structure

```bash
src/
│── appwrite/      # Appwrite service logic (auth, DB, storage)
│── assets/        # Images, icons, static files
│── components/    # Reusable UI components (buttons, cards, etc.)
│── conf/          # Configuration files (API keys, constants)
│── pages/         # Page-level components (Home, Login, Blog, etc.)
│── store/         # State management (Redux / Context API)
│
│── App.jsx        # Main app component
│── main.jsx       # Entry point (React DOM rendering)
│── App.css        # App-specific styles
│── index.css      # Global styles
```

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/mega-blog.git
cd mega-blog
npm install
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file:

```env
VITE_APPWRITE_URL=your_url
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
VITE_APPWRITE_BUCKET_ID=your_bucket_id
VITE_TINYMCE_API_KEY=your_RTE_id
```

---

## 🚀 Key Concepts Used

* Component-based architecture
* Centralized state management
* API abstraction using Appwrite services
* Clean folder separation for scalability

---

## 🔮 Future Enhancements

* ❤️ Like & Comment system
* 🔔 Notifications
* 📊 Analytics dashboard
* 🌐 SEO optimization
* 🤖 AI-powered blog suggestions

---

## 👨‍💻 Author

**Aman Tripathi**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
