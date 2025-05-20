
---
# 📣 NotifyAll - Messaging & Notification System

**Live App:** [notifyallrnlkwc.vercel.app](https://notifyallrnlkwc.vercel.app)
**GitHub Repository:** [Captivating-Shree/NotifyAll-Application](https://github.com/Captivating-Shree/NotifyAll-Application)

NotifyAll is a scalable, real-time messaging and notification platform built using **Next.js** and **Firebase FCM**. It includes a powerful **Admin Panel** for managing users and messages and an **Interactive User Panel** for private and broadcast communication. It supports **PDF sharing**, real-time push notifications, and is designed with performance and user experience in mind.

---

## 🚀 Features

* 🔐 **Authentication** – Secure login for admin and users.
* 💬 **Private Messaging** – Send direct messages between users.
* 📢 **Broadcast Messaging** – Admins can send announcements to all users.
* 📎 **PDF File Support** – Send and preview PDF files within the chat.
* 🔔 **Firebase FCM Notifications** – Instant push notifications.
* 📱 **Responsive UI** – Mobile-friendly, clean, and interactive interface.
* ⚙️ **Admin Panel** – Manage messages, users, and broadcasts.
* 📈 **Scalable Architecture** – Optimized for performance using serverless functions and Firebase.

---

## 🛠️ Tech Stack

* **Frontend:** Next.js, Tailwind CSS
* **Backend:** Firebase Cloud Functions
* **Database & Auth:** Firebase Firestore, Firebase Authentication
* **Notifications:** Firebase Cloud Messaging (FCM)
* **Deployment:** Vercel

---

## 📦 Installation & Local Development

Follow these steps to clone, configure, and run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Captivating-Shree/NotifyAll-Application.git
cd NotifyAll-Application
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Firebase

* Create a Firebase project in [Firebase Console](https://console.firebase.google.com).
* Enable **Firestore**, **Authentication**, and **Cloud Messaging**.
* Get your Firebase config from the project settings and add it to a `.env.local` file:

```bash
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

### 4. Start Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📚 Project Structure

```
NotifyAll-Application/
├── components/         # Reusable UI components
├── pages/              # Next.js pages (admin, user, login, etc.)
├── firebase/           # Firebase config and messaging setup
├── public/             # Static assets
├── styles/             # Global and modular styles
├── utils/              # Helper functions
└── .env.local          # Environment variables
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### 1. Fork the Repository

Click the **Fork** button in the top-right corner of the GitHub page.

### 2. Create a New Branch

```bash
git checkout -b feature/your-feature-name
```

### 3. Make Your Changes

Add your improvements or features and commit your code:

```bash
git add .
git commit -m "Add your message"
```

### 4. Push and Create Pull Request

```bash
git push origin feature/your-feature-name
```

Go to your fork on GitHub and create a **Pull Request** into the `main` branch of this repo.

---

## 📄 License

This project is licensed under the **MIT License**.
Feel free to use and modify it for your own needs. Contributions welcome!

---

## 🙌 Acknowledgements

Thanks to all contributors and users helping improve this project!

---
