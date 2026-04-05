# 💰 Finance Dashboard UI

## 📌 Overview

This project is a **frontend-only Finance Dashboard** built using **HTML, CSS, and JavaScript**. It allows users to track financial activities, view insights, and interact with transaction data in a clean and responsive interface.

The goal of this project is to demonstrate **UI design, state management, and frontend logic** without relying on any backend services.

---

## 🚀 Features

### 📊 Dashboard Overview

* Displays **Total Balance, Income, and Expenses**
* 📈 Time-based visualization using a **line chart**
* 🥧 Category-based visualization using a **pie chart**

---

### 💳 Transactions Section

* View transaction details:

  * Date
  * Amount
  * Category
  * Type (Income / Expense)
* 🔍 Search transactions by category
* 🔽 Filter (All / Income / Expense)
* ↕ Sort by Amount and Date
* ❌ Delete transactions (Admin only)

---

### 👤 Role-Based UI

* **Viewer**

  * Can only view data

* **Admin**

  * Can add and delete transactions

* Role switching implemented using a dropdown for demonstration

---

### 📊 Insights Section

* Displays:

  * 🥇 Highest spending category
  * 💡 Simple financial observation

---

### ⚙️ State Management

State is managed using a centralized JavaScript object:

* Transactions data
* Selected role
* Filters
* Sorting
* Search input

This ensures a clean and maintainable approach without external libraries.

---

### 🎨 UI & UX

* Clean and modern layout
* ✨ Smooth hover animations
* 🌙 Dark mode toggle
* 📱 Fully responsive (mobile-friendly)
* Handles empty states gracefully

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (Flexbox, Grid, Media Queries)
* JavaScript (Vanilla JS)
* Chart library: **Chart.js**

---

## 📂 Project Structure

```
index.html   // Complete application (HTML + CSS + JS)
```

---

## ▶️ How to Run

1. Download or clone the repository
2. Open `index.html` in your browser

No installation required.

---

## 💡 Key Design Decisions

* Used **Chart.js** for quick and effective data visualization
* Maintained a **single state object** for better control of UI updates
* Focused on **simplicity and clarity** over unnecessary complexity
* Designed UI to be responsive across different screen sizes

---

## 📈 Possible Improvements

* Edit transaction functionality
* Local storage persistence
* Advanced analytics and insights
* Export data (CSV/JSON)

---

## 🏁 Conclusion

This project demonstrates how a functional and user-friendly dashboard can be built using only frontend technologies, with a focus on **clarity, usability, and maintainability**.

---
