# ChatConnect

A **real-time chat application** built with **React**, **Vite**, and **Socket.IO**. ChatConnect allows users to join or create chat rooms and communicate instantly in real time. The app has a clean, responsive UI built with **Tailwind CSS**.

---

## 🔹 Features

* Join or create chat rooms with a nickname
* Real-time messaging with **Socket.IO**
* Online/offline room support
* Responsive and modern UI with **Tailwind CSS**
* Separate **frontend** and **backend** structure

---

## 🛠 Tech Stack

* **Frontend:** React, Vite, Tailwind CSS, TypeScript
* **Backend:** Node.js, Express, Socket.IO
* **Deployment:** Render (backend), Vercel (frontend)

---

## 🌐 Live Demo
* **Live :** https://anikate-chat-connect.vercel.app/ 
* **Frontend:** https://chat-connect-m60ruj2ae-anikatedahiyas-projects.vercel.app
* **Backend:** https://chatconnect-qdo3.onrender.com

---

## 💻 Installation & Running Locally

1. **Clone the repository**

```bash
git clone https://github.com/AnikateDahiya/ChatConnect.git
cd ChatConnect
```

2. **Install backend dependencies**

```bash
cd server
npm install
npm start
```

3. **Install frontend dependencies**

```bash
cd ../client
npm install
npm run dev
```

4. **Open the app**

* Frontend should open automatically (usually at `http://localhost:5173`)
* Backend runs on `http://localhost:3001` (or your configured PORT)

---

## ⚡ Usage

1. Enter a **nickname**
2. Enter a **Room ID** (create a new room or join an existing one)
3. Start chatting in real time with other users in the same room

---

## 📁 Project Structure

```
ChatConnect/
├── client/         # Frontend React app
├── server/         # Backend Node.js + Socket.IO
├── README.md
```

---

## 🔧 Environment Variables

* **Frontend (`client`)**

  * `VITE_SERVER_URL` → Your backend URL (e.g., `https://chatconnect-qdo3.onrender.com`)

* **Backend (`server`)**

  * No additional environment variables required by default

---

## 👨‍💻 Author

**Anikate Dahiya**

* GitHub: https://github.com/AnikateDahiya
* Email: anikate311204@gmail.com

---

## 📄 License

This project is **MIT licensed**.

