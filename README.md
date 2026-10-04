# 📝 Full-Stack To-Do Application

A complete, responsive full-stack To-Do application built to help users organize their daily tasks efficiently. This application features a robust backend API and an intuitive frontend user interface.

## 🚀 Features
* **Full CRUD Functionality:** Create, read, update, and delete tasks effortlessly.
* **Status Toggling:** Mark tasks as complete or delete with a single click.
* **REST API:** Well-structured API endpoints for managing tasks.
* **Responsive Design:** Optimized for seamless use on desktop, tablet, and mobile devices.

## 🛠️ Tech Stack
* **Frontend:** [HTML/CSS/JavaScript]
* **Backend:** [Node.js, Express]
* **Database:** [SQLite]
* **Tools Used:** Git, REST Client

---

## 💻 Getting Started

Follow these steps to set up and run the project locally on your machine.

### 📋 Prerequisites
Make sure you have the following installed:
* [Node.js](https://nodejs.org) (v18 or higher recommended)
* [Git](https://git-scm.com)

### 🔧 Installation

1. **Clone the repository:**
   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL_HERE>
   cd <YOUR_PROJECT_FOLDER_NAME>
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   * Create a `.env` file in the root directory.
   * Copy the contents from `.env.example` and fill in your details:

4. **Run the application:**
   ```bash
   npm run dev
   ```

---

## 🔌 API Endpoints
If you want to test the backend using the included `todo-app.rest` file, here are the available routes:

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/todo` | Fetch all to-do items |
| **POST** | `/todo` | Create a new to-do item |
| **PUT** | `/todo/:id` | Update/Toggle a to-do item |
| **DELETE** | `/todo/:id` | Delete a specific to-do item |

---

## 📁 Project Structure
```text
├── public/          # Static assets (images, icons, index.html, css files)
├── src/             # Backend source code
├── .env.example     # Template for environment variables
├── .gitignore       # Files ignored by Git (node_modules, .env)
├── package.json     # Project dependencies and scripts
└── README.md        # Project documentation
```
