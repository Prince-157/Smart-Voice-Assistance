🗺️ Real-Time Location Tracking App

A real-time location-sharing web application using Node.js, Socket.io, and Leaflet.js.

📌 Features

✅ Live location tracking of multiple users✅ Users' markers update in real time✅ Auto-adjusts zoom to fit all users✅ Removes disconnected users automatically✅ Uses Leaflet.js for an interactive map✅ Built with Node.js, Express, and Socket.io

📂 Project Structure

📁 Real-Time-Tracking-App│── 📁 public│   │── 📁 css│   │   └── style.css  # Styles for the map│   │── 📁 js│   │   └── script.js  # Handles real-time location updates│   │── 📁 images (optional)│   └── index.html  # Frontend UI│── 📁 views│   └── index.ejs  # Main page template│── 📄 server.js  # Node.js backend with Socket.io│── 📄 package.json  # Dependencies and scripts│── 📄 README.md  # This file

🛠️ Installation

1️⃣ Clone the Repository

git clone https://github.com/your-username/real-time-tracking-app.git
cd real-time-tracking-app

2️⃣ Install Dependencies

npm install

3️⃣ Run the Server

npm start

4️⃣ Open in Browser

http://localhost:3000

🖥️ Technologies Used

Node.js – Backend server

Express.js – Web framework

Socket.io – Real-time communication

Leaflet.js – Interactive maps

EJS – Template engine

HTML, CSS, JavaScript – Frontend

📌 How It Works

1️⃣ User opens the website2️⃣ Their location is shared automatically (if permission is granted)3️⃣ Users' locations update in real time on the map4️⃣ If a user disconnects, their marker disappears

💡 Future Improvements📍 Add user names with markers🌍 Implement custom map styles📱 Improve mobile UI/UX🛠️ Add authentication for privacy

🔗 Live Demo: Real-Time Tracking App
