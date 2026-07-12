# 📱 Dynamic Multi-Platform Social Media Post Composer

A modern **Full Stack Social Media Post Composer** built with **React.js**, **Tailwind CSS**, **Node.js**, and **Express.js**. The application enables users to create, validate, schedule, and simulate publishing social media posts while following platform-specific content constraints.

---

## 🚀 Features

- 📝 Create posts with Title and Description
- 📷 Optional image and video upload with preview
- 📅 Schedule posts with Date & Time picker
- 🌐 Platform selection via dropdown
- 📊 Real-time character counter
- ✅ Platform-specific validation
- 💾 Save and restore drafts using Local Storage
- 🚀 Simulated Publish API using Express.js
- 🌙 Dark Mode support
- 📱 Fully Responsive UI
- 🔔 Toast notifications for user feedback

---

## 📌 Supported Platforms

| Platform | Character Limit |
|----------|----------------:|
| Twitter (X) | 280 |
| Threads | 500 |
| Pinterest | 500 |
| Instagram | 2200 |
| Quora | 3000 |
| Facebook | 63206 |

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- JavaScript (ES6)
- React Hooks

### Backend
- Node.js
- Express.js
- REST API

### Storage
- Local Storage (Draft Management)

---

## 📂 Project Structure

```
social-media-post-composer/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── utils/
│   │   ├── assets/
│   │   ├── styles/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   └── package.json
│
├── server/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/social-media-post-composer.git
```

### 2. Navigate into the project

```bash
cd social-media-post-composer
```

### 3. Install frontend dependencies

```bash
cd client
npm install
```

### 4. Install backend dependencies

```bash
cd ../server
npm install
```

---

## ▶️ Running the Application

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

The frontend will typically run on:

```
http://localhost:5173
```

The backend will typically run on:

```
http://localhost:5000
```

---

## 🔄 Application Workflow

1. Enter the **Title**.
2. Write the **Description**.
3. Optionally upload an image or video.
4. Select the desired social media platform.
5. Choose a schedule date and time.
6. Real-time validation checks the input.
7. Save as a draft or publish the post.
8. The backend simulates a successful publish request.

---

## ✅ Validation Rules

- Title is required.
- Description is required.
- Platform selection is required.
- Media upload is optional.
- Schedule date cannot be in the past.
- Character limits vary by platform.
- Publish is disabled if validation fails.

---

## 🎯 Learning Outcomes

This project demonstrates:

- Component-based architecture with React
- State management using React Hooks
- Responsive UI development with Tailwind CSS
- REST API development with Express.js
- Real-time form validation
- Draft persistence using Local Storage
- Modular and scalable project structure

---

## 🔮 Future Enhancements

- 🔐 User Authentication (JWT)
- 🗄️ MongoDB Integration
- ☁️ Cloudinary Media Upload
- 🤖 AI Caption Generator
- #️⃣ AI Hashtag Suggestions
- 📆 Calendar Scheduling
- 📈 Analytics Dashboard
- 👥 Multi-user Support
- 📡 Real Social Media API Integration

---

## 👨‍💻 Author

**Hemant**

B.Tech Computer Science & Engineering

Chandigarh Engineering College, Jhanjeri

---

## 📄 License

This project is developed for educational and learning purposes.
