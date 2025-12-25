🤖 Code Reviewer — AI-Powered Code Review Tool

Code Reviewer is a full-stack AI-powered web application that reviews source code and provides intelligent feedback using Google Generative AI (Gemini). The application allows users to submit code and receive detailed reviews, suggestions, error explanations, and optimized solutions in a clean and readable format.

🚀 Features

🔹 Frontend

🧑‍💻 Code editor input for submitting source code

🎨 Syntax highlighting using PrismJS

📝 AI responses rendered with Markdown formatting

⚡ Built with React (Vite) for fast development

📱 Clean and responsive UI styled with Tailwind CSS

🔄 API integration using Axios

🔹 Backend

🧠 RESTful backend built with Node.js & Express.js

📤 POST-based API for handling code review requests

🔐 Secure environment configuration using .env

🌐 CORS enabled for smooth frontend–backend communication

🔹 AI Integration

🤖 Integrated Google Generative AI (Gemini API)

AI-generated outputs include:

Code review feedback

Improvement suggestions

Error explanations

Optimized code recommendations

🛠️ Tech Stack

Frontend,
React,
Vite,
Tailwind CSS,
PrismJS,
React Markdown,
Axios

Backend

Node.js,
Express.js,
REST APIs,
CORS

AI

Google Generative AI (Gemini API)

📁 Project Structure

Code-Reviewer/

├── Frontend/   

├── Backend/

└── README.md

⚙️ Setup & Installation

1️⃣ Clone the repository
git clone https://github.com/your-username/code-reviewer.git
cd Code-Reviewer

2️⃣ Backend Setup
cd Backend
npm install


Create a .env file inside the Backend folder:

PORT=3000
GEMINI_API_KEY=your_google_gemini_api_key


Start the backend server:

npx nodemon

3️⃣ Frontend Setup

cd ../Frontend
npm install
npm run dev


Frontend will start on:

http://localhost:5173

🔄 Application Flow

User enters code in the frontend editor

Code is sent to the backend via a POST request

Backend forwards the request to Gemini AI

AI-generated review is returned and displayed using Markdown + syntax highlighting

👨‍💻 Author & Contribution

Kuldeep Patidar

Independently designed and developed the complete full-stack application

Implemented frontend UI, backend APIs, and AI integration

Refactored AI response handling and improved request structure

Managed the entire development lifecycle and version control

📌 Project Status

🚧 Deployment: Not deployed yet
