# Student Record Management System

A lightweight, modern web-based application designed to manage student profiles, academic records, and performance metrics. Built using pure front-end web technologies, this application offers an intuitive interface to add, search, view, and manage student details with offline persistence.

---

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Application markup, semantic structure, and form validation controls. |
| **CSS3** | Modern responsive design, flexbox/grid layout, custom styling, and visual badge indicators. |
| **JavaScript (ES6+)** | DOM manipulation, state management, real-time search filtering, and LocalStorage interaction. |
| **Browser LocalStorage API** | Client-side persistent data storage without requiring an external database. |

---

## ✨ Features

* **Student Registration:** Add new students with fields for Full Name, Roll Number, Academic Branch, and Performance Marks.
* **Pass/Fail Auto-Calculation:** Automatically determines pass or fail status based on standard academic thresholds ($\ge 40\%$).
* **Real-time Live Search:** Filter student records dynamically by **Name**, **Roll Number**, or **Branch**.
* **Data Persistence:** All records are automatically saved in the browser's `localStorage` to ensure data isn't lost on page reload.
* **Duplicate Roll Number Protection:** Prevents duplicate entries using roll number verification logic.
* **Fully Responsive:** Styled using standard CSS Grid and Flexbox for seamless display on desktops, tablets, and mobile devices.

---

## 📁 Repository Structure

```text
├── srs.html       # Single-file implementation containing HTML, CSS, and JS
└── README.md        # Project documentation
