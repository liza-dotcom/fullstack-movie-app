# 🎬 Full-Stack Movie Tracking Platform

A full-stack web app where users can browse movies, manage a personal watchlist, 
track completed films, and view personalized stats — built with a React frontend 
and PHP/MySQL backend featuring dual authentication (session-based + JWT) and 
12+ RESTful API endpoints.

---

## Tech Stack

**Frontend**
- React
- JavaScript
- HTML, CSS

**Backend**
- PHP
- REST APIs
- MySQL (phpMyAdmin)

**Tools**
- Git & GitHub

---

## Features

- Dual authentication system — session-based login and JWT with protected routes
- 12+ RESTful PHP API endpoints with input validation and SQL injection prevention
- Normalized MySQL database with relational tables, foreign keys, and indexes
- Watchlist management — add, track, and complete movies per user
- Search by title and genre with async React fetch and error handling UI
- Personalized User Stats dashboard (total watch time, ratings, completed count)
- Movie detail modal with ratings, runtime, budget, genres, and studio info

---

## Project Architecture

This project is split into two repositories:

- **Frontend (React):**  
  https://github.com/COIS-WebDev/assn3-liza-dotcom.git

- **Backend (PHP API):**  
  https://github.com/COIS-WebDev/assn2-liza-dotcom.git

The React frontend communicates with the PHP backend using RESTful API calls. Authentication is handled on the backend, with protected endpoints accessible only to authenticated users.

---

## Screenshots

### Login & Authentication

_Styled login screen with username/password auth, session management, and a "Create Account" flow._

<img width="736" height="415" alt="Screenshot 2025-12-16 at 6 45 45 PM" src="https://github.com/user-attachments/assets/01380329-26c6-4933-9f34-f6c456a0a992" />

### Movie Browse / Dashboard

_Home dashboard showing movie posters with ratings, watchlist buttons, and search by title and genre_

<img width="1451" height="827" alt="Screenshot 2025-12-16 at 6 46 34 PM" src="https://github.com/user-attachments/assets/3fbb3fca-e09c-4277-8e92-ec11653db2ca" />

### Feature Example

_Movie detail modal pulling live data — rating, votes, runtime, budget, revenue, genres, and studio_

<img width="1427" height="814" alt="Screenshot 2025-12-16 at 6 46 55 PM" src="https://github.com/user-attachments/assets/6eb1b0f7-1f34-4a9e-b7e8-b1a2b3c93b31" />

### User Stats 
_Authenticated user dashboard showing completed movies, planned watchlist, total watch time, and average rating._

<img width="1463" height="601" alt="Screenshot 2025-12-16 at 6 55 56 PM" src="https://github.com/user-attachments/assets/c5021fc7-dcab-4011-8b65-6f5f85753587" />

---

## Running the Project Locally

**Frontend**
# cd frontend
# npm install
# npm start

**Backend**

# 1. Set up XAMPP or MAMP and start Apache + MySQL
# 2. Import the provided SQL schema into phpMyAdmin
# 3. Update db_config.php with your local database credentials
# 4. Place the backend folder in your htdocs directory
_Note: Environment-specific configuration may be required._

---


