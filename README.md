# 🥗 NutriPlan

**NutriPlan** is a modern, data-driven web application designed for comprehensive meal exploration and nutritional tracking. Built with vanilla JavaScript, this project demonstrates high-level proficiency in API integration, state management, and dynamic UI rendering without the need for external frameworks.

![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow.svg)
![CSS3](https://img.shields.io/badge/CSS3-Modern-blue.svg)
![API](https://img.shields.io/badge/API-TheMealDB-green.svg)

---

## 🚀 Project Overview

The core mission of NutriPlan is to bridge the gap between meal inspiration and health tracking. It serves as a robust practice model for building scalable, modular applications using **ES6 Modules** and **State-driven logic**.

### Key Technical Goals:
* **Modular Architecture:** Implementing a clean "Separation of Concerns" (API, State, UI).
* **Asynchronous Flow:** Mastering `Async/Await` and the `Fetch API` for real-time data retrieval.
* **Client-Side Routing:** Handling multi-page navigation within a Single Page Application (SPA) structure.
* **Data Persistence:** Utilizing `LocalStorage` to maintain user logs across browser sessions.

---

## 🧠 Core Features

* **Meal Discovery:** Browse meals by category, search by name, or filter by geographical area.
* **Detailed Recipe Insights:** View complete ingredient lists, measurements, and cooking instructions.
* **Dynamic Food Log:** Track daily intake and maintain a history of meals consumed.
* **Visual Analytics:** Weekly nutrition overview powered by **Plotly.js** for data visualization.
* **Product Scanner:** Interface for looking up products and Nutri-score filtering.
* **Responsive UI:** A clean, mobile-friendly design that works across all screen sizes.

---

## 🛠️ Technologies Used

* **Language:** JavaScript (ES6 Modules)
* **Styling:** CSS3 (Flexbox & Grid)
* **Markup:** HTML5
* **Data Source:** [TheMealDB API](https://www.themealdb.com/api.php)
* **Charts:** Plotly.js
* **Persistence:** Browser LocalStorage

---

## 📁 Project Structure

The project follows a modular directory structure to ensure maintainability:

```text
starter/
├── index.html          # Main Entry Point
├── README.md           # Project Documentation
└── src/
    ├── css/            # Stylesheets
    │   └── style.css
    └── js/
        ├── main.js     # App Initialization & Event Delegation
        ├── api/        # API communication logic (mealdb.js)
        ├── state/      # Global state management (appState.js)
        └── ui/         # Reusable UI components (components.js)
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
* **LinkedIn:** [Your LinkedIn Profile]

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
