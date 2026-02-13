🍽️ Restaurant Reservation Bot (Express + Gemini AI)

A smart restaurant reservation chatbot built using Node.js, Express, and Google Gemini AI.
The bot allows users to book tables for specific time slots and automatically manages seat availability.

🚀 Features

✅ Simple reservation format: Name Time Guests

Example: Arun 7pm 3

📊 Real-time seat tracking (per time slot)

🤖 AI fallback using Gemini API for conversational responses

💬 Modern glass-effect chat UI

⚡ Fast Express backend

🌐 Runs locally on http://localhost:3000

⏰ Available Time Slots

Each slot has a capacity of 10 seats:

6pm

7pm

8pm

The bot automatically:

Confirms booking if seats are available

Rejects booking if slot is full

Updates seat count dynamically

🛠️ Technologies Used

Backend: Node.js + Express

Frontend: HTML, CSS, JavaScript

AI Integration: Google Gemini 2.5 Flash API

Styling: Custom CSS (Glassmorphism UI)

Server Port: 3000

📂 Project Structure
restaurant-reservation-bot/
│
├── server.js
├── public/
│   ├── index.html
│   ├── frontend.js
│   ├── style.css
│   └── images/
│       └── restuarant_pic.jpg
│
└── README.md
