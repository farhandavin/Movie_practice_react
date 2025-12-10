🎬 Movie Practice
Movie Practice is a dynamic front-end web application built with React. It allows users to browse popular movies, search for specific titles, and manage a personalized list of favorite movies.

This project was developed to practice fundamental React concepts such as Components, Hooks (useState, useEffect), Context API, and integration with external REST APIs.

✨ Key Features
Popular Movies Feed: Displays a real-time list of trending movies fetched from a public API.

Search Functionality: An interactive search feature that allows users to find specific movies by title.

Favorites Management: Users can add movies to their "Favorites" list and remove them. The favorites state is managed globally using the Context API to ensure accessibility across the app.

Movie Info Cards: Presents movie details (Poster, Title, Release Year) using a reusable UI component.

Responsive Design: A modern interface that adapts seamlessly to different screen sizes.

🛠️ Tech Stack
Frontend Framework: React.js (powered by Vite)

Language: JavaScript (ES6+)

Styling: CSS3 (Component-specific stylesheets)

State Management: React Context API

Data Source: The Movie Database (TMDB) API

Routing: React Router (for navigation between Home and Favorites)

⚙️ Installation & Setup
Follow these steps to run the project locally on your machine:

1. Clone the Repository
Download the source code to your computer:

Bash

git clone https://github.com/your-username/movie-practice.git
cd movie-practice
2. Navigate to Frontend Directory
Ensure you are in the folder containing package.json:

Bash

cd frontend
3. Install Dependencies
Install all necessary libraries (React, React Router, etc.):

Bash

npm install
4. API Key Configuration (Optional)
If the app requires a TMDB API Key, create a .env file in the frontend folder and add your key:

Code snippet

VITE_API_KEY=your_tmdb_api_key_here
(Note: Adjust this according to your implementation in src/services/api.js)

5. Run the Application
Start the local development server:

Bash

npm run dev
Open the URL shown in your terminal (usually http://localhost:5173) in your browser.

📂 Folder Structure
Here is an overview of the project structure:

frontend/
├── public/
├── src/
│   ├── assets/          # Static assets (images/icons)
│   ├── components/      # UI Components (MovieCard, NavBar)
│   ├── contexts/        # Context API (MovieContext) for global state
│   ├── css/             # Separate CSS files for styling
│   ├── pages/           # Main Pages (Home, Favorites)
│   ├── services/        # API call logic (api.js)
│   ├── App.jsx          # Main component & Route configuration
│   └── main.jsx         # Application entry point
├── index.html
├── package.json
└── vite.config.js
🚀 Future Improvements (To-Do)
[ ] Add a Movie Detail page (Synopsis, Rating, Cast).

[ ] Implement infinite scroll or pagination for the Home page.

[ ] Enhance UI with transition animations.

Created by farhan davin rinaldi
