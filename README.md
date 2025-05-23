# 📝 Todo Management Application

A clean and beginner-friendly **React-based Todo List App** to help users stay organized and productive. This app enables users to add and remove tasks, showcasing the fundamentals of React components, props, and state management.

---

## 🔍 Overview

This application is a simple **Todo List Manager** built using **React.js**. It offers basic CRUD functionality with an intuitive UI and is perfect for beginners learning:

- 🔹 JSX syntax
- 🔹 Props & Component-Based Architecture
- 🔹 useState for State Management
- 🔹 Conditional Rendering

---

## 🚀 Features

- ➕ **Add New Task** with a due date
- 🗑️ **Delete Task** from the list
- 🎉 **Welcome Message** when list is empty
- ⚛️ **Fully Reactive UI** using React state

---

## 🧹 Component Structure

### 📁 `App.jsx`
- Manages app-level state using `useState`
- Contains handlers to add/delete todos
- Passes props to child components

### 📾 `AddTodo.jsx`
- Accepts user input for task and date
- **Props**: `onNewItem`
- Calls handler to add task

### 📜 `TodoItems.jsx`
- Renders list of todo items
- **Props**: `todoItems`, `onDeleteClick`

### ✅ `TodoItem.jsx`
- Renders single todo row with delete button
- **Props**: `todoName`, `todoDate`, `onDeleteClick`

### 😊 `WelcomeMessage.jsx`
- Displays a custom message when no tasks exist

---

## 🔄 State Management

- Main state is held in `App.jsx` using `useState`
- All child components receive props from the parent
- Todo list is maintained as an array of objects

---

## 📸 Final Output Screenshots

Add your screenshots below this section to showcase the UI and functionality.

### 🏠 Homepage with EmptyTasks
![Homepage with Tasks](Screenshot-1-2.png)

### ➕ Adding a New Task
![Add Task](Screenshot-1-3.png)

### 🏠 Homepage with Tasks
![Homepage with Tasks](Screenshot-1-4.png)

### 🗑️ Deleting a Task
![Delete Task](Screenshot-1-6.png)


---

## 🛆 Installation & Usage

```bash
# Clone the repo
git clone https://github.com/your-username/todo-app.git
cd todo-app

# Install dependencies
npm install

# Run the development server
npm start
```

---

## 🛠️ Built With

- [React.js](https://reactjs.org/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

## ✨ Author

Made with ❤️ by **Rohit Dhumal**  
🔗  [[LinkedIn](https://linkedIn.com/in/rohitdhumal24)](#) • [[GitHub](https://github.com/rohitdhumal-24)](#)


