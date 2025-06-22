🤖 AiChatBot
AiChatBot is an intelligent and responsive chatbot application built using HTML, CSS, and vanilla JavaScript, seamlessly integrated with Google's Gemini 2.5 Flash API. This project demonstrates real-time conversational capabilities, including support for image-based input, all wrapped in a clean and mobile-friendly user interface.

✨ Features
Text & Image Interaction: Allows users to send text and upload image files (converted to base64) to receive intelligent responses from the AI.

Real-Time AI Responses: Integrated with Google Gemini 2.5 Flash API for dynamic, human-like replies based on the user's input.

Loading Feedback: Includes a typing/loading animation while waiting for the AI response.

Chat UI Design: Designed user and AI chat bubbles with avatars and auto-scrolling behavior.

Responsive Layout: Fully responsive and mobile-friendly interface for smooth experience on all screen sizes.

Live Hosting: Deployed publicly using GitHub Pages for real-time access.

🛠 Technologies Used
Frontend
HTML5 – Page structure and layout.

CSS3 – Styling and responsiveness.

JavaScript (Vanilla) – Handling user input, image upload, API communication.

FileReader API – To read and encode image files.

Base64 Encoding – For passing image data to the Gemini API.

API Integration
Google Gemini 2.5 Flash API – AI model that processes text and image input for contextual responses.

📁 Project Structure
bash
Copy
Edit
AiChatBot/
│
├── index.html           # HTML layout for the app
├── style.css            # All UI styling and responsiveness
├── script.js            # JS logic (API calls, DOM updates, image handling)
├── ai.png               # AI avatar
├── user.png             # User avatar
├── img.svg              # Image icon for upload
├── submit.svg           # Submit/send icon
├── loading.gif          # Typing animation
└── README.md            # Project overview
⚙️ Installation & Running Locally
No complex environment setup is required—just open the HTML file in a browser.

Optionally:
Clone the Repo:

bash
Copy
Edit
git clone https://github.com/mahesh6688/AiChatBot.git
cd AiChatBot
Run Locally:

Open index.html in your browser

Make sure to update your Gemini API key inside script.js

 Deployment
This project is live and accessible via GitHub Pages:
🔗 https://mahesh6688.github.io/AiChatBot/

 Conclusion
Developing AiChatBot has enhanced my understanding of integrating external AI APIs with frontend technologies and working with real-time user interaction workflows. It reflects my ability to build intelligent web apps with an emphasis on user experience, interface design, and API integration.
