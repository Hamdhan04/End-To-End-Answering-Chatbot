# 🌌 Callisto AI – End-to-End Answering Chatbot

**Callisto AI** is a sophisticated full-stack conversational platform designed to provide seamless, real-time question-answering. Built with a modern dark-themed UI, it features secure user authentication and persistent conversation management, making it a robust foundation for AI-driven assistant systems.

---

##  Features

* Intelligent Responses: Leverages LLM capabilities to provide detailed, context-aware answers.
* Secure Authentication: Full login and registration flow to protect user data and personalize experiences.
* Dynamic Chat Interface: A responsive, real-time messaging UI with a focus on readability and user flow.
* Conversation Persistence: Sidebar integration to save, view, and manage multiple chat histories.
* Premium UI/UX: A sleek, modern dark-mode aesthetic built for long-form reading and interaction.

---

##  System Overview

| Component | Description |
| --- | --- |
| **Login/Auth** | Secure entry point for users to access their private chat history. |
| **Dashboard** | A personalized welcome screen to initiate new sessions. |
| **Chat Engine** | The core interface featuring message bubbles and real-time LLM streaming. |
| **Sidebar** | Organized list of recent interactions for easy navigation. |

---

##  Tech Stack

### **Frontend**

* **HTML5 & CSS3:** Custom-styled components with a focus on responsiveness.
* **JavaScript (ES6+):** Handles DOM manipulation and asynchronous API calls.

### **Backend**

* **Node.js & Express.js:** A scalable server environment managing routes and business logic.
* **RESTful APIs:** Structured endpoints for communication between the UI and AI services.

---

##  Project Structure

```text
Callisto-AI/
├── backend/            # Express server, API routes, and controllers
│   ├── routes/         # Auth and Chat endpoint definitions
│   ├── controllers/    # Logic for handling requests
│   ├── services/       # AI/LLM integration logic
│   └── server.js       # Entry point for the backend
├── frontend/           # Client-side assets
│   ├── pages/          # HTML structures for Login, Dashboard, and Chat
│   ├── assets/         # Images, icons, and global styles
│   └── scripts/        # Frontend logic and API integration
├── public/             # Static files
└── README.md

```

---

##  Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/your-username/Callisto-AI.git
cd Callisto-AI

```


2. **Install dependencies**
```bash
npm install

```


3. **Configure Environment (Optional)**
*Create a `.env` file in the root and add your API keys.*
4. **Start the server**
```bash
npm start

```


5. **Access the app**
Navigate to `http://localhost:3000` in your browser.

---

##  Use Cases

* **Knowledge Assistant:** Deployment as a specialized internal wiki or documentation bot.
* **Academic Research:** A tool for summarizing and explaining complex topics.
* **Portfolio Foundation:** A battle-tested template for building more complex AI SaaS products.
