# Recipe Finder App

## Description

A responsive web-based Recipe Finder application built with HTML, CSS, and JavaScript. The application allows users to search for recipes by keyword, browse matching meals, view detailed cooking instructions, ingredient lists, and watch recipe videos. It fetches real-time recipe data from **TheMealDB API** and provides a clean, user-friendly interface.

---

## About This Project

The Recipe Finder App demonstrates how to consume a REST API using JavaScript's Fetch API to retrieve and display dynamic content. Users can search for recipes, browse matching meals, and explore detailed information including ingredients, cooking instructions, meal categories, and YouTube cooking tutorials.

The project also showcases asynchronous JavaScript, DOM manipulation, event handling, responsive web design, and proper error handling for failed searches and network requests.

---

## Features

- Search recipes by meal name or keyword
- Display recipe cards with meal images
- View meal categories
- Read complete cooking instructions
- Display ingredients with measurements
- Watch recipe tutorials on YouTube
- Fetch live recipe data using TheMealDB API
- Fully responsive layout for desktop and mobile
- Handles empty searches and invalid recipe names
- Modern and clean user interface

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Fetch API
- TheMealDB API
- Font Awesome

---

## Project Structure

```text
07-Recipe_Finder/
│
├── screenshots/
│   ├── home.png
│   ├── search-results.png
│   └── recipe-details.png
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/07-Recipe_Finder.git
```

### 2. Navigate to the project folder

```bash
cd 07-Recipe_Finder
```

### 3. Open the application

Open **index.html** in your preferred web browser.

No installation or build tools are required.

---

## How It Works

1. Enter a recipe name or keyword into the search bar.
2. Click the **Search** button or press **Enter**.
3. The application sends a request to TheMealDB API.
4. Matching recipes are displayed as interactive cards.
5. Click any recipe card to view:
   - Recipe image
   - Meal category
   - Cooking instructions
   - Ingredients and measurements
   - YouTube cooking tutorial (if available)

---

## API Used

This project uses the free **TheMealDB API**.

### Search Meals

```http
https://www.themealdb.com/api/json/v1/1/search.php?s=
```

### Lookup Meal Details

```http
https://www.themealdb.com/api/json/v1/1/lookup.php?i=
```

---

## Future Improvements

- Save favorite recipes
- Random recipe generator
- Filter recipes by category
- Search recipes by ingredient
- Dark mode
- Pagination for large search results
- Save favorites using Local Storage
- Like and bookmark recipes

---

## Learning Objectives

This project helped practice:

- Working with REST APIs
- JavaScript Fetch API
- Async/Await
- DOM Manipulation
- Event Listeners
- Responsive Web Design
- Error Handling
- Dynamic HTML Rendering

---
