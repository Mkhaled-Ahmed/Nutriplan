# 🥗 NutriPlan  
### Smart Food, Nutrition & Fitness Planner

**NutriPlan** is a sleek, data-driven web application crafted to merge **meal discovery**, **nutritional awareness**, and **daily tracking** into one seamless experience.  
Built entirely with **vanilla JavaScript**, this project showcases advanced front-end engineering concepts without relying on external frameworks.

![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow.svg)
![CSS3](https://img.shields.io/badge/CSS3-Modern-blue.svg)
![API](https://img.shields.io/badge/API-TheMealDB-green.svg)
![Architecture](https://img.shields.io/badge/Architecture-Modular-purple.svg)

---

## ✨ Why NutriPlan?

NutriPlan is not just a UI demo—it is a **well-architected, scalable front-end application** designed to simulate real-world product development scenarios.

It emphasizes:
- Clean architecture
- Maintainable code
- Real API consumption
- State-driven UI updates

Perfect for **technical assessments**, **JavaScript exams**, and **portfolio reviews**.

---

## 🚀 Project Vision

The mission of NutriPlan is to bridge the gap between **meal inspiration** and **nutrition tracking** while demonstrating mastery of modern JavaScript patterns.

### 🎯 Engineering Objectives
- **Modular Architecture**  
  Clear separation between API logic, application state, and UI components.
- **Asynchronous Mastery**  
  Efficient data fetching using `async / await` and the Fetch API.
- **SPA-Style Navigation**  
  Client-side routing without frameworks.
- **Persistent State**  
  Saving user progress using `LocalStorage`.

---

## 🧠 Core Features

- 🔍 **Meal Discovery**  
  Browse meals by category, search by name, or filter by region.
- 📖 **Detailed Recipes**  
  Ingredients, measurements, and step-by-step cooking instructions.
- 📝 **Food Log System**  
  Track daily meals and nutritional intake.
- 📊 **Weekly Analytics**  
  Interactive charts powered by **Plotly.js**.
- 🧪 **Product Scanner**  
  Product lookup with Nutri-Score filtering.
- 📱 **Responsive Design**  
  Optimized for desktop, tablet, and mobile screens.

---

## 🛠️ Tech Stack

| Category | Technology |
|-------|-----------|
| Language | JavaScript (ES6 Modules) |
| Markup | HTML5 |
| Styling | CSS3 (Flexbox & Grid) |
| API | TheMealDB |
| Charts | Plotly.js |
| Storage | Browser LocalStorage |

---

## 📁 Project Architecture

A scalable, production-style folder structure:

```text
starter/
├── index.html          # Application entry point
├── README.md           # Documentation
└── src/
    ├── css/
    │   └── style.css   # Global styles
    └── js/
        ├── main.js     # App bootstrap & navigation
        ├── api/
        │   └── mealdb.js     # API communication layer
        ├── state/
        │   └── appState.js   # Centralized state management
        └── ui/
            └── components.js # Reusable UI components
```
---

## 🚦 Getting Started

### Prerequisites
No special environment or build tools are required—just a modern web browser.

### Installation & Usage
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Mkhaled-Ahmed/Nutriplan---Design.git](https://github.com/Mkhaled-Ahmed/Nutriplan---Design.git)
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd Nutriplan---Design
    ```
3.  **Launch the app:**
    Open `index.html` in your browser. (Using the "Live Server" extension in VS Code is recommended).

---

## 🔗 API Reference

NutriPlan leverages **TheMealDB** (Free Tier) to fetch real-time culinary data:
* **Base URL:** `https://www.themealdb.com/api/json/v1/1/`
* **Endpoints:** Search by name, filter by category, and lookup detailed meal IDs.

---

## 💡 Technical Highlights

* **State-UI Synchronization:** The application UI updates automatically when the underlying `appState.js` changes.
* **Event Delegation:** Efficiently handles user interactions on dynamically generated elements.
* **Error Handling:** Implements robust `try-catch` blocks and loading states during API transitions.

---

## 👨‍💻 Author

**Mohamed Khaled** *Computer & Systems Engineer*

* **GitHub:** [@Mkhaled-Ahmed](https://github.com/Mkhaled-Ahmed)
* **Live Demo:** [@Mkhaled-Ahmed](https://mkhaled-ahmed.github.io/Nutriplan/#all-recipes-section)
* **LinkedIn:** [https://www.linkedin.com/in/mohammed-khaled7/]

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
