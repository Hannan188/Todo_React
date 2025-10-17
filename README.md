Todo App using React and Context API
Overview

This is a simple and responsive Todo List application built with React.js. It allows users to add, edit, delete, and mark tasks as completed. The project uses React Context API for global state management and localStorage for data persistence.

Features
Add new todos
Edit existing todos
Mark tasks as complete or incomplete
Delete todos
Save todos in browser localStorage
Clean and responsive UI with Tailwind CSS
Technologies Used
React.js
JavaScript (ES6)
Context API
React Hooks (useState, useEffect, useContext)
Tailwind CSS
LocalStorage
Installation
Clone the repository:
git clone https://github.com/yourusername/todo-app.git
Navigate to the project folder:
cd todo-app
Install dependencies:
npm install
Start the app:
npm run dev
Project Structure
src/
│
├── App.jsx          # Main application file
├── context.js       # Context API logic
├── components/
│   ├── TodoForm.jsx # Component to add todos
│   └── TodoItem.jsx # Component to display each todo
└── App.css          # Styles
How It Works
The App.jsx manages all todos using React state and Context API.
TodoForm adds new todos.
TodoItem handles editing, deleting, and completing tasks.
All todos are stored in localStorage for persistence.


Author

Mohd Abdul Hannan

License

This project is open-source and available under the MIT License.
