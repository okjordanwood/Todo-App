# 📝 Interactive Todo App

A sleek, interactive todo list application built with **React**, featuring task filtering, completion tracking, and persistent local storage. Designed for simplicity and productivity with clean UI components and modular architecture.

---

## 🚀 Features

- ✅ Add, complete, and delete tasks
- 🗂️ Filter tasks by `All`, `Open`, and `Completed`
- 💾 Automatic saving to `localStorage` (persists across page reloads)
- ⚡ Instant feedback with stateful UI updates
- 🎨 Styled with custom CSS using `FantaCSS`

---

## 🛠️ Tech Stack

| Frontend | State Management | Styling     | Persistence |
|----------|------------------|-------------|-------------|
| React    | useState, useEffect | FantaCSS / Custom CSS | localStorage |

---

## 🧪 How It Works

- `App.jsx` manages all todos and passes props down to child components.
- Tasks are stored in local state and synchronized with `localStorage`.
- Components are cleanly separated:
  - `Header`: shows task count
  - `Tabs`: filters tasks
  - `TodoInput`: adds tasks
  - `TodoList` & `TodoCard`: render and manage individual todos

---

## 🌐 How to Access and Use

You can use the app right now at:  
👉 [https://todope.netlify.app](https://todope.netlify.app)

### Instructions:
1. Type a task into the input field and click the **+** button to add it.
2. Switch between `All`, `Open`, and `Completed` using the tabs at the top.
3. Mark tasks as complete or delete them using the buttons on each task card.
4. All tasks are saved in your browser, so they’ll be there when you return!

---

## 📄 License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Jordan Wood**  
- 📬 Email: [jordancwood2002@gmail.com](mailto:jordancwood2002@gmail.com)  
- 🌐 Portfolio: [https://jordanwood.netlify.app](https://jordanwood.netlify.app)  
- 🐙 GitHub: [okjordanwood](https://github.com/okjordanwood)  
- 🔗 LinkedIn: [linkedin.com/in/jordan-wood-085274247](https://www.linkedin.com/in/jordan-wood-085274247)
   
