📊 Cloud-Based Web Admin Panel with Scraped Data Viewer
-----
---

🧩 Project Description
A full-stack web application featuring an admin panel that allows authenticated users to:
-Scrape data from a public website (e.g., job listings, news headlines)
-Store the data in a cloud database
-View the data in a sortable, paginated table
-Trigger scraping on-demand using a "Scrape Now" button

---

📦 Tech Stack
---
🔹 Frontend:
--
React (with TypeScript template), Axios (API communication), Tailwind CSS

🔹 Backend:
--
Node.js + Express, Scraping using Cheerio , REST API for frontend interaction

🔹 Database:
--
MongoDB Atlas, Firebase Firestore

🔹 Authentication:
--
Dummy login (email/password)

🔹 Deployment:
--
Frontend: Vercel ,Backend: Render or Railway

---

📁 Project Structure
--
/fullstack-admin-panel
│
├── /client                 # React frontend
│   ├── /src
│   └── package.json
│
├── /server                 # Express backend
│   ├── /routes
│   ├── /scraper
│   ├── /models
│   ├── /controllers
│   └── server.js
│
├── .env                    # Environment variables
├── README.md
└── .gitignore
