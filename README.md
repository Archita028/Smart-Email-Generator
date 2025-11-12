🧠 SmartMail AI Assistant

An AI-powered email assistant that intelligently generates context-aware Gmail replies using Spring Boot, Spring AI, and React. The project also includes a Chrome Extension that integrates directly with Gmail, allowing users to compose smart replies effortlessly.

🚀 Project Overview

The SmartMail AI Assistant combines backend intelligence, a modern frontend interface, and a Gmail-integrated Chrome extension to enhance email productivity.
The Spring Boot backend handles request processing and reply generation.
Spring AI integrates with Google’s Gemini API to generate human-like, context-sensitive email responses.
The React frontend offers a standalone interface for generating replies manually.
The Chrome extension enables one-click insertion of AI-generated replies directly in Gmail.

🔧 Technical Highlights

Backend Setup:
Built using Spring Boot and Java, providing REST APIs to manage email data and generate responses.

AI Integration:
Powered by Spring AI with Google Gemini API, enabling intelligent and context-aware response generation.

Frontend Development:
Developed with React.js, HTML, CSS, and JavaScript to offer a clean and responsive UI.

Browser Extension:
A Chrome Extension (Manifest v3) integrates directly with Gmail to inject AI-generated replies seamlessly.

🧩 Tech Stack

Backend:
Spring Boot
Java

Spring AI (Google Gemini API)
Frontend:
React.js
HTML, CSS, JavaScript

Extension:
Chrome Extension (Manifest v3)

Communication:
RESTful APIs
JSON

⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/<your-username>/smartmail-ai-assistant.git
cd smartmail-ai-assistant

2. Backend Setup
cd backend
./mvnw spring-boot:run


Make sure to add your Gemini API key in the application properties file.

3. Frontend Setup
cd frontend
npm install
npm start

4. Chrome Extension Setup
Open Chrome → Extensions → Manage Extensions → Load unpacked
Select the chrome-extension folder from the project directory

🎯 Features
✉️ Generates intelligent, context-aware email replies
🤖 Integrates directly with Gmail for real-time suggstions
🧩 Modular architecture (Backend + Frontend + Extension)
⚡ Fast and seamless AI-driven email composition


🧠 Future Enhancements
Add user authentication for personalized responses
Enable multiple email provider integration

Improve UI/UX for reply customization

📝 License

This project is licensed under the MIT License – feel free to use, modify, and distribute with attribution.
