# MERN Realtime Chat Application 🚀

A full-featured real-time chat application built with the **MERN stack**, powered by **Socket.IO**, **Redux Toolkit**, **Tailwind CSS**, and **JWT** authentication. Users can sign up, create or join chat rooms, send messages with emojis, and receive notifications—all with responsive UI.

Live demo: [talk-time.netlify.app](https://talk-time.netlify.app) :contentReference[oaicite:1]{index=1}

---

## 🔗 Tech Stack

- **Frontend**: React, Redux Toolkit, Tailwind CSS  
- **Backend**: Node.js, Express, Socket.IO  
- **Database**: MongoDB  
- **Auth**: JWT + Google OAuth  
- Real-time communication via **Socket.IO** :contentReference[oaicite:2]{index=2}

---

## ✨ Key Features

- ✅ User authentication (email/password + Google OAuth)  
- 🔄 Real-time messaging between users using Socket.IO  
- 👥 Create and manage one-on-one or group chat rooms  
- 📥 Push notifications for new messages  
- 😃 Send emojis in chat  
- 📸 User profiles: update avatar and display name  
- 🔍 Search users and chat rooms  
- 📱 Fully responsive design for mobile and desktop :contentReference[oaicite:3]{index=3}

---

## 🛠️ Getting Started (Local Setup)

1. **Clone this repo**  
   ```bash
   git clone https://github.com/14anshuman/MERN-Realtime-Chat-Application.git
   cd MERN-Realtime-Chat-Application
Client setup

bash
Copy
Edit
cd client
npm install
Create .env file in client/:

ini
Copy
Edit
REACT_APP_GOOGLE_CLIENT_ID=your_google_client_id
REACT_APP_SERVER_URL=http://localhost:8000
Server setup
Open a new terminal:

bash
Copy
Edit
cd server
npm install
Create .env file in server/:

ini
Copy
Edit
PORT=8000
URL=your_mongodb_connection_uri
SECRET=your_jwt_secret
CLIENT_ID=your_google_client_id
BASE_URL=http://localhost:3000
Run the app

Server: npm start

Client: in client folder, npm start

The application should now be running locally at http://localhost:3000.

🧩 Architecture Overview
Backend: Manages user auth, chat/message APIs, room logic, and Socket.IO events

Frontend: Handles UI, Redux state, Socket.IO connections

Socket.IO: Powers real-time events like messaging, typing indicators, and presence

MongoDB: Stores users, chat rooms, messages, and profiles

🤝 Contributing
Contributions are welcome! To get started:

Fork the repo

Create a new branch: git checkout -b feature-name

Commit changes: git commit -m "Add feature"

Push: git push origin feature-name

Open a Pull Request

📜 License
This project is released under the MIT License. 
github.com
+7
github.com
+7
github.com
+7
github.com
github.com

📞 Contact
Have questions or ideas? Feel free to open an issue or PR!
Check out the live demo: talk-time.netlify.app 
github.com
+2
github.com
+2
github.com
+2

yaml
Copy
Edit

---

Feel free to customize any details like the repository URL, environment variables, or demo link. Let me know if you'd like help adjusting or adding badges, images, or advanced setup instructions!
::contentReference[oaicite:26]{index=26}
