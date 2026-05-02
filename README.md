🤖 MERN Chatbot Application

A full-stack Chatbot Web Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). This project provides real-time chat functionality with user authentication and a responsive UI.

🚀 Features
🔐 User Authentication (JWT-based login/signup)
💬 Real-time Chat Interface
🤖 Chatbot Responses (AI / rule-based)
📁 Full CRUD Operations
🛡️ Protected Routes
📱 Responsive UI (Tailwind CSS)
⚡ Fast API handling using Express.js
🛠️ Tech Stack

Frontend:

React.js
Tailwind CSS
Axios
React Router DOM

Backend:

Node.js
Express.js

Database:

MongoDB (Mongoose)

Authentication:

JSON Web Tokens (JWT)


⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/mern-chatbot.git
cd mern-chatbot


**Install Dependencies:**
    Frontend Folder :

    ```bash
    cd frontend
    npm install
    ```

    Backend Folder :

    ```bash
    cd backend
    npm install
    ```

**Set Up Environment Variables:**

    Configure the following environment variables by creating a .env file in the root of Forntend and Backend Folder:

    Frontend Folder :

    ```bash
    VITE_BACKEND_URL=http://localhost:9000
    ```

    Backend Folder :

    ```bash
    FRONTEND_URL=http://localhost:5173
    MONGODB_URI=mongodb://127.0.0.1:27017/chat-app
    PORT=3000
    JWT_SECRET=secret123
    ```

    Replace the values with your specific configurations.

**Run the Application:**

    Frontend Folder :

    ```bash
    npm run dev
    ```

    Backend Folder :

    ```bash
    npm run dev
    ```

 **Open in Your Browser:**

Open `http://localhost:5173` in your web browser.

## Project Structure

    ├── frontend
    │   ├── public
    │   ├── src
    │   │   ├── assets
    │   │   ├── components
    │   │   ├── pages
    │   │   ├── redux
    │   │   ├── socket
    │   │   ├── utils
    │   │   ├── App.jsx
    │   │   ├── main.jsx
    │   │   └── index.css
    │   ├── index.html
    │   ├── tailwind.config.js
    │   ├── .env
    │   └── package.json
    ├── backend
    │   ├── config
    │   ├── controllers
    │   ├── middlewares
    │   ├── models
    │   ├── routes
    │   ├── server.js
    │   ├── .env
    │   └── package.json
    └── README.md



👨‍💻 Author

Dipanshu Patidar

GitHub: https://github.com/your-username
Portfolio: https://your-portfolio-link
⭐ Support

If you like this project, give it a ⭐ on GitHub!