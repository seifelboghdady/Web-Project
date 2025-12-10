# 📑 Project Documentation: Greenfood 🌱

## Table of Contents

1.  [🚀 Executive Summary](#-executive-summary)
2.  [🔗 Live Demonstration](#-live-demonstration)
3.  [📌 Project Overview](#-project-overview)
4.  [🧩 Key Features](#-key-features)
5.  [🛠 Technology Stack](#-technology-stack)
6.  [📁 Project Structure & File System](#-project-structure--file-system)
7.  [⚙️ Local Development & Getting Started](#️-local-development--getting-started)
8.  [🧭 Usage & Interaction](#-usage--interaction)
9.  [📸 Visuals & User Interface](#-visuals--user-interface)
10. [📚 Lessons Learned & Technical Growth](#-lessons-learned--technical-growth)
11. [👤 Author & Contributions](#-author--contributions)

---

## 1. 🚀 Executive Summary

**Greenfood** is a focused, responsive front-end single-page application (SPA) developed to showcase a company dedicated to **sustainable and healthy food choices** using organic, locally sourced ingredients.

This project was a hands-on exercise focused on reinforcing core web development fundamentals—**HTML5, CSS3, and Vanilla JavaScript**—with a specific emphasis on structured semantic markup, modern CSS layouts, and implementing basic client-side state management (Dark Mode toggle).

## 2. 🔗 Live Demonstration

The production build of this project is hosted via GitHub Pages and is accessible at:

👉 **[https://seifelboghdady.github.io/Web-Project/](https://seifelboghdady.github.io/Web-Project/)**

## 3. 📌 Project Overview

This project delivers a simple yet robust landing page for the fictional Greenfood enterprise, including the following key sections:

* **Navigation:** A fixed, multi-section navigation bar (`<nav>`) providing quick access to different parts of the page (Home, Projects, Teams, Research, Support, Login).
* **Introduction:** A clear statement of the company's core mission and commitment to sustainable practices.
* **Team Section:** A dedicated area for displaying key team members, their roles, and professional details.
* **Thematic Control:** A primary feature is the **Dark Mode toggle**, allowing users to seamlessly switch between light and dark themes for enhanced accessibility and preference.

The primary objective was to build a clean, modular, and maintainable user interface (UI) structure.

## 4. 🧩 Key Features

* **Responsive Layout:** The design adheres to modern web standards, ensuring optimal viewing across various device screen sizes (desktop, tablet, mobile).
* **Sticky Navigation:** A top-of-page navigation bar that remains visible as the user scrolls.
* **Semantic HTML Structure:** Utilisation of appropriate HTML5 elements (e.g., `<header>`, `<main>`, `<section>`, `<footer>`) for improved accessibility and search engine optimisation (SEO).
* **Thematic Toggle:** A fully functional **Dark Mode** feature implemented with Vanilla JavaScript to manage CSS class changes across the application.
* **Clean and Intuitive UI:** A focus on minimalist design principles to highlight content and user experience.

## 5. 🛠 Technology Stack

| Technology | Role |
| :--- | :--- |
| **HTML5** | Provides the semantic structure and content of the single-page application. |
| **CSS3** | Handles all styling, layout (e.g., Flexbox/Grid), typography, and thematic definitions (Light/Dark mode styles). |
| **JavaScript** | **Vanilla JS** was used exclusively for core interactivity, specifically controlling the logic for the Dark Mode toggle feature. |

## 6. 📁 Project Structure & File System

The repository follows a clear, logical structure for ease of navigation and maintenance:

```text
Web-Project/
├── index.html            # Primary entry point and structural markup (the SPA)
├── style.css             # Main stylesheet (including theme variables and responsive breakpoints)
├── script.js             # Client-side logic for interactivity (e.g., event listeners, dark mode function)
└── assets/               # Directory for static media
    └── (images, icons, etc.)
```
## 7. ⚙️ Local Development & Getting Started

To get a copy of the project running on your local machine for development or review:

### Prerequisites

You need **Git** installed and a modern web browser.

### Procedure

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)<your-username>/Web-Project.git
    ```
2.  **Navigate to the Project Directory:**
    ```bash
    cd Web-Project
    ```
3.  **Launch the Application:**
    Since this is a static front-end project, no build tools or backend server are required. You can launch it by:
    * **Option A (Simplest):** Double-clicking the `index.html` file.
    * **Option B (Recommended):** Using a live server extension (e.g., in VS Code) for automatic browser refresh during development.

---

## 8. 🧭 Usage & Interaction

The application is designed for straightforward interaction:

* **Content Consumption:** Scroll through the page to review the company mission and team structure.
* **Navigation:** Use the links in the header to jump to specific sections within the single page.
* **Theme Switching:** Locate and click the **"Enable Dark Mode"** button to instantly switch the entire application's colour scheme.

---

## 9. 📸 Visuals & User Interface

The following screenshots illustrate the application's default and thematic states:

* **Light Theme (Default)**
    ![Greenfood Home](./screenshots/home-light.png)
* **Dark Theme (Toggled State)**
    ![Greenfood Dark Mode](./screenshots/home-dark.png)

---

## 10. 📚 Lessons Learned & Technical Growth

This project served as a foundational exercise, providing practical experience in:

* **Semantic Layout Design:** Creating a well-structured landing page that adheres to accessibility best practices.
* **Modern CSS Techniques:** Efficiently managing complex layouts and styling using contemporary CSS features (e.g., custom properties for thematic variables).
* **DOM Manipulation with Vanilla JS:** Successfully implementing a client-side interaction (Dark Mode) by manipulating the Document Object Model (DOM) without relying on external libraries.
* **Deployment Workflow:** Successfully publishing a project for public access using the straightforward workflow of GitHub Pages.

---

## 11. 👤 Author & Contributions

* **Author:** Seif El-Islam Elboghdady
* **GitHub Profile:** [https://github.com/seifelboghdady](https://github.com/seifelboghdady)
* **Live Demo:** [https://seifelboghdady.github.io/Web-Project/](https://seifelboghdady.github.io/Web-Project/)
