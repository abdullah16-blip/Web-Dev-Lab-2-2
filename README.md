# Web Application Development Lab (CSE2252)

## 📌 Project Overview
This repository contains lab exercises for the **CSE2252 Web Application Development Lab** course. The project focuses on JavaScript **DOM manipulation** and developing a **React-based Meal Info App** using the [TheMealDB API](https://www.themealdb.com/api.php).

## 📂 Repository Structure
```
Web-Dev-Lab-2-2/
│-- task1/  # JavaScript DOM Manipulation Tasks
│   ├── index.html
│-- task2/  # React Meal Info App
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│-- Lab Ques/  # Things we will implement
│-- .gitignore/  # Things ignored in git
└──
```

---

## 📝 Task 1: JavaScript DOM Manipulation
In **task1**, we will modify `index.html` using JavaScript to perform the following tasks:

1. **Change Background Color**: Add a click event to the `Change Background Color` button to change the `<body>` background to `#CCCCFF`.
2. **Add List Item**: Implement a click event on the `Add List Item` button to append a new `<li>` with the text `Item n` (where `n` is the current item count +1) to the `<ul>`.
3. **Live Text Update**: Attach a `keyup` event listener to an `<input>` field that updates `<div id="output">` to match the user input.

---

## 🖥️ Task 2: React Meal Info App
In **task2**, a React application skeleton is provided for fetching and displaying meal categories.

### 🛠️ Setup
1. Navigate to the `task2` directory:
   ```sh
   cd task2
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the development server:
   ```sh
   npm start
   ```

### 📌 Features to Implement
- **Fetch Meal Categories:**
  - Modify `src/pages/CategoryPage.jsx` to fetch meal categories from the API below when the **View Meal Categories** button is clicked.
  - API Endpoint: `https://www.themealdb.com/api/json/v1/1/categories.php`
  
- **Display Meals by Category:**
  - When clicking **View Food** in each category, fetch and display meals using:
    ```sh
    https://www.themealdb.com/api/json/v1/1/filter.php?c={category}
    ```
  - Example for `Seafood`: `https://www.themealdb.com/api/json/v1/1/filter.php?c=Seafood`

---


---

## 💡 Useful Resources
- [MDN JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [React Official Documentation](https://react.dev/)
- [TheMealDB API Documentation](https://www.themealdb.com/api.php)

---

### 🏆 Happy Coding! 🚀



