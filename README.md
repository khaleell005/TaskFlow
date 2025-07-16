# 📋 TaskFlow – Drag-and-Drop Task Manager App

TaskFlow is a simple, elegant, and responsive **task management application** built using **pure HTML, CSS, and JavaScript** — no libraries or frameworks. It allows users to manage their tasks using a **drag-and-drop interface**, track progress in real-time (simulated), collaborate across users (locally), and view analytics with built-in data visualization.

---

## 🚀 Features

### ✅ Core Functionalities
- **Drag-and-drop tasks** between boards (*To Do*, *In Progress*, *Done*).
- **Create, edit, and delete** tasks with title, description, due date, priority, and assigned user.
- **Simulated real-time updates** using `localStorage` and the `storage` event.
- **Collaborative experience** with simulated user sessions.
- **Persistent task data** saved in `localStorage`.

### 📊 Data Visualization
- Dynamic charts showing:
  - Task status distribution.
  - Completion rate over time.
  - Tasks assigned per user (optional).
- Built using `<canvas>` or SVG, no libraries.

### 💡 Extras
- Light/Dark mode toggle.
- Search/filter tasks by keyword, user, or category.
- Overdue task indicators.
- Responsive mobile-first layout.

---

## 📂 Project Structure

```

taskflow/
│
├── index.html           # Main HTML page
├── style.css            # CSS styling and themes
├── app.js               # Core logic and task management
├── /assets              # Icons, images, SVGs
└── /data
└── sample-tasks.json (Optional sample data)

````

---

## 🛠️ Built With

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6+)**
- **HTML5 Drag and Drop API**
- **localStorage / Web Storage API**
- **Canvas / SVG for charting**

---

## 🔧 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/khalell005/Taskflow.git
````

2. Open `index.html` in your browser:

   ```bash
   cd taskflow
   open index.html   # or just double-click the file
   ```


---

## 🧠 Stretch Features (Optional)

* Offline support using **Service Workers**
* Multi-user authentication simulation
* Notification system for deadlines
* Keyboard accessibility

---

## 👨‍💻 Author

**Ibrahim Abubakar Ibrahim**

* GitHub: [@your-username](https://github.com/khalell005)
* Portfolio: (khaleel.web.app)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
