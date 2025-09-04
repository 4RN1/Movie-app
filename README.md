# 📌 Movie App

## 📖 Overview

This is a simple React Movie App that fetches popular movies and allows users to search for movies using the TMDB API.
The app was built as a learning project to practice React, component-based architecture, state management, and Tailwind CSS styling.

## 🚀 Features

- View a list of popular movies
- Search for movies by title
- Display movie details (title, release date, poster)
- Responsive layout using Vanilla CSS
- Favorite movies saved in local storage

## 🛠️ Tech Stack

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com/)  [![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)  [![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)  [![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)

## 📂 Project Structure

```plaintext
movie-app/
├─ public/                  
├─ src/
│  ├─ components/          
│  │  ├─ Header.jsx
│  │  ├─ MovieCard.jsx
│  │  ├─ ProductCard.jsx
│  │  └─ UserCard.jsx
│  ├─ pages/               
│  │  └─ Home.jsx
│  ├─ services/             
│  │  └─ api.js
│  ├─ css/                  
│  │  └─ Home.css
│  └─ App.jsx             
├─ package.json           
├─ tailwind.config.js       
└─ .gitignore

```

## 🎮 How to Run
```
Clone the repository

git clone https://github.com/yourusername/movie-app.git
cd movie-app


Install dependencies

npm install


Set up your TMDB API key
Inside src/services/api.js, replace with your own key:

 const API_KEY = "YOUR_API_KEY_HERE";


Start the development server

npm run dev


Open the app in your browser
Visit 👉 http://localhost:5173
 (or whichever port Vite shows).
```


## 🤝 Contributing

Contributions are welcome!
If you'd like to contribute:

Fork the repository

Create a new branch (git checkout -b feature-branch)

Commit your changes (git commit -m "Add new feature")

Push to the branch (git push origin feature-branch)

Open a Pull Request

Built while following a YouTube tutorial.
👉 Author’s YouTube Channel: [Tech With Tim](https://www.youtube.com/watch?v=G6D9cBaLViA)



