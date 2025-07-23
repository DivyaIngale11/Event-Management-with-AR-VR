<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Event Management Website - README</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; background-color: #f9f9f9; }
    h1, h2, h3 { color: #2c3e50; }
    table { width: 100%; border-collapse: collapse; margin: 20px 0; }
    th, td { border: 1px solid #ccc; padding: 10px; text-align: left; }
    th { background-color: #eee; }
    code, pre { background-color: #f4f4f4; padding: 5px; border-radius: 4px; }
    ul { margin-left: 20px; }
  </style>
</head>
<body>

  <h1>🎉 Event Management Website</h1>
  <p>A web application where users can explore and book events, view 360° virtual tours of event venues, and preview event displays using Augmented Reality. Admins can add, manage, and delete events easily through a backend system.</p>

  <h2>✨ Features</h2>

  <h3>👥 For Users</h3>
  <ul>
    <li>🔍 View all upcoming events</li>
    <li>📅 Book your favorite events</li>
    <li>🌐 Take a 360° virtual tour of the event venue</li>
    <li>📱 Use AR to preview event displays with your phone</li>
    <li>🔐 Sign up / Log in to manage your bookings</li>
  </ul>

  <h3>🧑‍💼 For Admin</h3>
  <ul>
    <li>➕ Add new events</li>
    <li>🗑️ Delete events</li>
    <li>✏️ Update existing event details</li>
    <li>📋 View and manage user bookings</li>
  </ul>

  <h2>🧠 Technologies Used</h2>

  <h3>🔧 Frontend</h3>
  <ul>
    <li>HTML, CSS, JavaScript</li>
    <li>Bootstrap (Responsive Design)</li>
    <li><a href="https://aframe.io/" target="_blank">A-Frame (WebXR)</a> → For VR 360° tour</li>
    <li><a href="https://github.com/AR-js-org/AR.js" target="_blank">AR.js</a> → For Augmented Reality display preview</li>
  </ul>

  <h3>💻 Backend</h3>
  <ul>
    <li>Java + Spring Boot (API and logic)</li>
    <li>MySQL (Database)</li>
    <li>Maven (Dependency Management)</li>
  </ul>

  <h2>🗺️ AR/VR Integration</h2>

  <table>
    <thead>
      <tr>
        <th>✅ Feature</th>
        <th>📄 Page</th>
        <th>⚙️ Technology</th>
        <th>🎯 Purpose</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>🌐 360° VR Tour</td>
        <td><code>about.html</code></td>
        <td>A-Frame</td>
        <td>See the venue in 360° before booking</td>
      </tr>
      <tr>
        <td>📱 AR Display Preview</td>
        <td><code>events.html</code></td>
        <td>AR.js</td>
        <td>Preview the event display using phone camera</td>
      </tr>
    </tbody>
  </table>

  <h2>📁 Project Structure</h2>
  <pre>
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
  </pre>

  <h2>🚀 How to Run</h2>

  <h3>🔙 Backend</h3>
  <ol>
    <li>Import the Spring Boot project in IntelliJ or VS Code</li>
    <li>Update DB credentials in <code>application.properties</code></li>
    <li>Run the main class to start the backend server</li>
  </ol>

  <h3>🌐 Frontend</h3>
  <ol>
    <li>Open <code>index.html</code> in any modern browser</li>
    <li>Use a <strong>WebXR-enabled browser</strong> (like Chrome) for VR tour</li>
    <li>Use a <strong>camera-enabled mobile browser</strong> for AR display</li>
  </ol>

  <h2>📌 Future Plans</h2>
  <ul>
    <li>💳 Add payment gateway for event booking</li>
    <li>📧 Email notifications for booking confirmation</li>
    <li>📊 Admin dashboard with analytics and event insights</li>
  </ul>

</body>
</html>
