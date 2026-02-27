## 📖 Introduction

Extensify is a smart and visually delightful browser extension that transforms your new tab page into a personalized productivity dashboard. Each time you refresh the tab, Extensify welcomes you with a time-aware greeting - Good Morning, Good Afternoon, or Good Evening - paired with a fresh, soothing background image to set the right tone for your session. Beyond the aesthetics, it helps you stay on track with a daily focus task and a persistent to-do list, so your priorities are always front and center.

Whether you're a developer, student, or professional - Extensify turns every refresh into a calm, intentional reset for your day.

---

## ✨ Key Features

- **🌅 Time-Aware Greetings** - Personalized greeting messages based on the time of day (morning, afternoon, evening).

- **🖼️ Dynamic Backgrounds** - A new beautiful, soothing background image appears every time you refresh the page.

- **👤 Personalized Welcome** - Enter your name on the home page and get a customized greeting routed to your task dashboard.

- **🎯 Daily Focus Task** - Set one main focus task for the day. Check it off or clear it to set a new goal. Automatically resets at midnight so you always start fresh.

- **✅ Persistent To-Do List** - A built-in to-do list in the bottom right that persists even when the day changes — your pending tasks are never lost.

---

## 🛠️ Tech Stack

| Technology            | Purpose                                       |
| --------------------- | --------------------------------------------- |
| **React.js**          | Component-based UI and state management       |
| **JavaScript (ES6+)** | Core logic, local storage, date/time handling |
| **CSS3**              | Styling, animations, and responsive layout    |
| **HTML5**             | Semantic structure and extension entry point  |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or above)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Git](https://git-scm.com/)

### Installation & Local Setup

1. **Clone the repository**

```bash
git clone https://github.com/Bhavin-Patel-dev/Extensify.git
```

2. **Navigate to the project directory**

```bash
cd Extensify
```

3. **Install dependencies**

```bash
npm install
```

4. **Start the development server**

```bash
npm start
```

The app will open at `http://localhost:3000` in your browser.

---

## 📁 Project Structure

```
Extensify/
├── public/
│   ├── favicon.ico               # App favicon
│   └── index.html                # HTML entry point
├── src/
│   ├── components/
│   │   └── Todo/
│   │       ├── Todo.jsx          # Todo component
│   │       └── Todo.css          # Todo styles
│   ├── context/
│   │   └── browser-context.js    # React context for global state
│   ├── db/
│   │   ├── images.js             # Background images data
│   │   └── quotes.js             # Quotes / greeting data
│   ├── pages/
│   │   ├── Home/
│   │   │   ├── Home.js           # Home page (name entry)
│   │   │   └── Home.css          # Home page styles
│   │   └── Task/
│   │       ├── Task.js           # Task/dashboard page
│   │       └── Task.css          # Task page styles
│   │   └── index.js              # Pages entry / routing
│   ├── reducer/
│   │   └── browser-reducer.js    # State reducer logic
│   ├── styles/
│   │   └── utility.css           # Shared utility styles
│   ├── App.js                    # Root component & routing
│   ├── App.css                   # Root styles
│   └── index.js                  # ReactDOM entry point
├── package.json
└── README.md
```

---

## 🧠 Learning Outcomes

Building Extensify offered hands-on experience across several important areas of modern web development:

- **React Fundamentals** - Deepened understanding of functional components, props, state, and the React component lifecycle through building a multi-page SPA.

- **React Router** - Learned client-side routing to navigate between the home (name entry) page and the task dashboard without a full page reload.

- **Local Storage & Persistence** - Implemented data persistence using the browser's `localStorage` API to maintain to-do items across sessions while resetting the daily task on day change.

- **Date & Time Manipulation** - Worked with JavaScript's `Date` object to conditionally render greetings and handle daily task resets automatically.

- **CSS Styling** - Crafted a clean, modern UI with dynamic background images and that works well as a new tab page.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 🙏 Acknowledgements

- Background images powered by [Pexels](https://www.pexels.com/)
- Inspired by and built with guidance from [GeeksforGeeks](https://www.geeksforgeeks.org/) Project-Based Learning.

---

<div align="center">
  Made with ❤️ using React.js
  <br/>
  ⭐ Star this repo if you found it helpful!
</div>
