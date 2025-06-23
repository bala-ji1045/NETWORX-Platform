# React + Vite Networx API Demo

This project is a modern React website (built with Vite) that connects to the Networx Recommendation API and supports user authentication, registration, dashboard, profile, and chat features.

## How to use

1. Start the development server:
   ```sh
   npm run dev
   ```
2. Open your browser to the local address shown in the terminal (usually http://localhost:5173).
3. Register a new user or login with existing credentials.
4. After login, access your dashboard to see recommended people and start chats.
5. View and edit your profile from the profile page.

## API Endpoint
- **Base URL:** [https://networx-s5t9.onrender.com](https://networx-s5t9.onrender.com)
- **API Docs:** [https://networx-s5t9.onrender.com/docs](https://networx-s5t9.onrender.com/docs)
- POST `/recommend` (for recommendations)
- POST `/register` (for user registration)
- POST `/login` (for user login)

## Project Structure
- `src/App.jsx`: Main app with routing for all pages.
- `src/Home.jsx`: Landing page with navigation.
- `src/Register.jsx`: User registration form.
- `src/Login.jsx`: User login form.
- `src/Dashboard.jsx`: Dashboard with recommendations and chat links.
- `src/Profile.jsx`: User profile page.
- `src/Chat.jsx`: Simple chat UI with recommended users.
- `src/api.js`: API base URL and endpoints.
- `src/App.css`: Modern, attractive CSS for the whole site.

---

This project was bootstrapped with [Vite](https://vitejs.dev/) and uses React (JavaScript).
