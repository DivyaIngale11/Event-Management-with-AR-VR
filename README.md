🎉 Event Management Website
A web application where users can explore and book events, view 360° virtual tours of event venues, and preview event displays using Augmented Reality. Admins can add, manage, and delete events easily through a backend system.

✨ Features
👥 For Users
🔍 View all upcoming events

📅 Book your favorite events

🌐 Take a 360° virtual tour of the event venue

📱 Use AR to preview event displays with your phone

🔐 Sign up / Log in to manage your bookings

🧑‍💼 For Admin
➕ Add new events

🗑️ Delete events

✏️ Update existing event details

📋 View and manage user bookings

🧠 Technologies Used
🔧 Frontend
HTML, CSS, JavaScript

Bootstrap (Responsive Design)

A-Frame (WebXR) → For VR 360° tour

AR.js → For Augmented Reality display preview

💻 Backend
Java + Spring Boot (API and logic)

MySQL (Database)

Maven (Dependency Management)

🗺️ AR/VR Integration
Feature	Page	Tech	Purpose
🌐 360° VR Tour	about.html	A-Frame	See the venue in 360° before booking
📱 AR Display Preview	events.html	AR.js	Preview the event display using phone camera

📁 Project Structure
pgsql
Copy
Edit
📦 Event-Management
├── frontend/
│   ├── index.html
│   ├── about.html
│   ├── events.html
│   └── styles.css
├── backend/
│   ├── Spring Boot project files
│   └── application.properties
└── database/
    └── schema.sql
🚀 How to Run
🔙 Backend
Import the Spring Boot project in IntelliJ or VS Code

Update DB credentials in application.properties

Run the project using the main class

🌐 Frontend
Open index.html in a browser

Use a WebXR-enabled browser for VR features

Use a camera-enabled browser (mobile recommended) for AR display

📌 Future Plans
Add payment gateway for event booking

Email notifications

Admin dashboard with analytics

