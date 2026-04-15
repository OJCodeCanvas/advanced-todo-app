---

#### `README.md`

```markdown
# TaskFlow — Advanced Todo App

A fully-featured task manager built with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools — just clean, production-quality code.

![TaskFlow Preview](https://img.shields.io/badge/Status-Production%20Ready-22c55e?style=for-the-badge)

---

## ✨ Features

### Core
- **Add, edit, and delete tasks** with a smooth modal-based UI
- **Mark tasks complete** with animated custom checkboxes
- **Persistent storage** — all data saved to `localStorage`
- **Drag & drop reorder** — rearrange tasks by dragging

### Organization
- **4 categories** — Work (blue), Personal (purple), Health (green), Learning (yellow)
- **3 priority levels** — Low, Medium, High with visual flag indicators
- **Due dates** with smart formatting (Today, Tomorrow, or exact date)
- **Overdue detection** — overdue tasks automatically flagged in red

### Views & Filtering
- **Sidebar navigation** — All Tasks, Today, Upcoming, Overdue
- **Status filters** — All, Active, Completed
- **5 sort options** — Newest, Oldest, Priority, Due Date, Alphabetical
- **Live search** — instant filtering as you type

### UX & Design
- **Dark mode** with system-persistent toggle
- **Toast notifications** — success, error, and info feedback
- **Confirmation modals** — safe delete with undo option
- **Empty states** — context-aware messages for every view
- **Progress bar** — tracks today's task completion percentage
- **Staggered animations** — tasks animate in sequentially
- **Fully responsive** — mobile sidebar with overlay, touch-friendly

### Keyboard Shortcuts
| Shortcut | Action |
|---|---|
| `Enter` | Add task |
| `Escape` | Close modal / sidebar |
| `Ctrl + K` | Focus search bar |

---

## 🛠 Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, flexbox, animations, `backdrop-filter`
- **Vanilla JavaScript** — ES6+, no dependencies
- **Font Awesome 6** — icons
- **Google Fonts** — Inter typeface
- **localStorage** — client-side persistence

---

## 🚀 Live Demo

👉 **[View Live](#)** *(replace # with your GitHub Pages URL after deploying)*

---

## 📁 Project Structure

```
advanced-todo-app/
├── index.html      # App structure & modals
├── style.css       # Full responsive styling + dark mode
├── script.js       # All logic, state, and interactions
└── README.md       # This file
```

---

## 🚀 Getting Started

### Option 1 — Just open it
Clone or download the repo, then open `index.html` in your browser.

```bash
git clone https://github.com/YOUR-USERNAME/advanced-todo-app.git
cd advanced-todo-app
open index.html
```

### Option 2 — Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch and `/ (root)`
4. Click **Save**
5. Your site will be live at `https://YOUR-USERNAME.github.io/advanced-todo-app/`

---



### Light Mode
> Clean white interface with blue accent, sidebar navigation, and expandable task input.

### Dark Mode
> Deep dark background with optimized contrast and glowing accent colors.

### Mobile View
> Collapsible sidebar with overlay, stacked layout, and always-visible action buttons.

---

## 🎯 Why This Project

This project demonstrates proficiency in:

- **No-framework architecture** — organizing a complex UI with vanilla JS
- **State management** — centralized task state with derived views (filters, sorts, counts)
- **CSS custom properties** — theming system with 30+ design tokens
- **Responsive design** — desktop sidebar → mobile drawer pattern
- **Accessibility** — keyboard navigation, focus states, semantic HTML
- **UX patterns** — toast notifications, confirmation dialogs, empty states, loading animations
- **Data persistence** — localStorage with clean serialization

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Credits

Built as part of the **Wix Grow** application portfolio.

- Icons by [Font Awesome](https://fontawesome.com/)
- Font by [Google Fonts — Inter](https://fonts.google.com/specimen/Inter)
```

---

Just replace `YOUR-USERNAME` in the two places it appears (clone URL and GitHub Pages link) and you're done.
