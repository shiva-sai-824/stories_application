MomentReel - Ephemeral Stories Web Application
MomentReel is a client-side web application delivering a modern "stories" experience, allowing users to share ephemeral image-based content that automatically expires after 24 hours. This project demonstrates proficiency in building interactive and responsive user interfaces with contemporary frontend technologies.
🚀 Live Demo: stories-application-two.vercel.app
💻 Source Code: github.com/shiva-sai-824/stories_application
Core Features & Technical Highlights
Dynamic Story Creation & Viewing: Users can upload images, which are processed (resized, converted to base64) and displayed as auto-playing stories with individual progress indicators.
Interactive Navigation: Implements intuitive swipe (via react-swipeable) and click-based navigation through story sequences.
Client-Side Persistence & Expiry: Leverages Browser LocalStorage for storing stories and managing their 24-hour lifecycle entirely on the client.
Responsive UI: Crafted with CSS3 for a seamless experience across various devices.
Modern Frontend Stack: Built with React.js (Hooks), JavaScript (ES6+), and styled with CSS3, all bundled efficiently using Vite.
Key Functionalities: Includes story deletion, visual distinction between viewed/unviewed stories, and robust error handling for image processing.
Technologies Used
Primary: React.js, JavaScript (ES6+), CSS3
State Management & UI: React Hooks
Build Tool: Vite
Client-Side Storage: Browser LocalStorage API
Gestures: react-swipeable
Deployment: Vercel
