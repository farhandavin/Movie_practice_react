# 🎬 Movie Practice App

A dynamic movie discovery web application built with **React** and **Vite**. This application allows users to browse popular movies, search for specific titles, and manage a personalized list of favorite movies using the **TMDB API**.

## ✨ Features

* **🔥 Popular Movies:** Displays a grid of currently popular movies fetched directly from The Movie Database (TMDB).
* **🔍 Search Functionality:** Real-time search feature to find movies by title.
* **❤️ Favorites System:** Add or remove movies from your favorites list.
* **💾 Local Storage Persistence:** Your favorite movies are saved in the browser's local storage, so they remain saved even after refreshing the page.
* **📱 Responsive Design:** Fully responsive layout that adapts to desktop, tablet, and mobile screens.
* **⚡ Fast Performance:** Powered by Vite for lightning-fast development and build speeds.

## 🛠️ Tech Stack

* **Frontend:** React.js, Vite
* **Styling:** CSS3 (Custom modular CSS)
* **Routing:** React Router DOM (v7)
* **State Management:** React Context API
* **Data Source:** TMDB API (The Movie Database)
* **Deployment Config:** Vercel

## 📂 Folder Structure

```text
frontend/
├── public/
├── src/
│   ├── assets/          # Static assets
│   ├── components/      # Reusable components (MovieCard, NavBar)
│   ├── contexts/        # Global State (MovieContext)
│   ├── css/             # Styling files
│   ├── pages/           # Page components (Home, Favorites)
│   ├── services/        # API configuration (api.js)
│   ├── App.jsx          # Main App component
│   └── main.jsx         # Entry point
├── .gitignore
├── index.html
├── package.json
└── vite.config.js
🚀 Getting Started
Follow these steps to set up the project locally on your machine.

Prerequisites
Node.js (v18 or higher recommended)

npm or yarn

Installation
Clone the repository

Bash

git clone [https://github.com/your-username/movie-practice.git](https://github.com/your-username/movie-practice.git)
cd movie-practice
Navigate to the frontend directory Important: The project files are located inside the frontend folder.

Bash

cd frontend
Install dependencies

Bash

npm install
API Configuration The project currently uses a hardcoded API key in src/services/api.js.

Optional (Best Practice): You can create a .env file in the frontend root to store your key securely:

Code snippet

VITE_TMDB_API_KEY=your_api_key_here
Note: You would need to update src/services/api.js to read from import.meta.env.VITE_TMDB_API_KEY.

Run the development server

Bash

npm run dev
Open the app Open your browser and navigate to http://localhost:5173 (or the port shown in your terminal).

🌐 Deployment
This project includes a vercel.json configuration file, making it easy to deploy to Vercel.

Push your code to GitHub.

Import the project into Vercel.

Set the Root Directory to frontend in the project settings.

Deploy!

🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you have any ideas for improvements.

Fork the Project

Create your Feature Branch (git checkout -zb feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 License
Distributed under the MIT License.

Created by Farhan Davin Rinaldi
