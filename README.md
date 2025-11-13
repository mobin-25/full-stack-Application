A fully functional real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Socket.io for instant two-way communication.
This project delivers seamless messaging, online/offline detection, typing indicators, message seen status, profile customization, and secure authentication — all wrapped in a clean, modern UI.

The application uses JWT authentication, bcrypt-secured passwords, and protected API routes to ensure user security. MongoDB manages user accounts, messages, and profile data, while Cloudinary handles profile image uploads. On the frontend, React with Tailwind CSS provides a fast, responsive, and intuitive interface for smooth chat interactions.

Socket.io enables users to send and receive messages instantly without refreshing. It updates online user lists in real-time, notifies when the other user is typing, and ensures that delivered/seen statuses are instantly synced. The application is fully responsive, scalable, and structured with clean folders and modular architecture, demonstrating full-stack expertise in real-time web development


How to Run the Project (Complete Steps)

Follow the steps below to run the Full-Stack Real-Time Chat Application on your local machine:

1️ Clone the Repository
git clone <your-repository-link>
cd <project-folder>

2️ Install All Dependencies
Backend:
cd server
npm install

Frontend:
cd ../client
npm install

3️ Create the .env File (Inside /server)

Create a file named .env and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret


 Do NOT use quotes.
Example: JWT_SECRET=test123 (not "test123")

4️ Start the Backend Server
cd server
npm run dev


Expected output:

MongoDB connected
Server is running on port 5000

5️ Start the Frontend Client
cd ../client
npm start


The React app will start at:

http://localhost:3000
