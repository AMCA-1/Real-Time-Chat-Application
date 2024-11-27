Real-Time Chat Application
A full-stack, real-time chat application built using modern web development technologies. The app supports real-time messaging, user authentication, group chats, and a sleek responsive design.

🚀 Features
Real-time messaging powered by WebSockets (Pusher or Socket.IO)
Authentication (Sign Up, Login, Logout)
Private and group chats
Responsive and modern UI built with TailwindCSS
User profiles and avatars
Persistent chat history using MongoDB
Backend APIs built with Nest.js
ORM support using Prisma
Deployment-ready for platforms like Vercel and AWS
🛠️ Tech Stack
Frontend:

Next.js: Framework for server-rendered React apps
TailwindCSS: For responsive and modern UI
Backend:

Nest.js: Scalable server-side application framework
WebSockets: For real-time messaging (via Pusher or Socket.IO)
Database:

MongoDB: NoSQL database for storing messages and user data
Prisma: ORM for seamless database management
Other Tools:

TypeScript: For type safety
NextAuth: Authentication library for Next.js
Cloudinary: For image and file uploads (optional)
📚 Installation Guide
Prerequisites
Node.js (>= 16)
MongoDB server or MongoDB Atlas account
Pusher account or WebSocket server
1️⃣ Clone the Repository
bash
Copy code
git clone https://github.com/your-username/realtime-chat-app.git
cd realtime-chat-app
2️⃣ Install Dependencies
bash
Copy code
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
3️⃣ Configure Environment Variables
Create a .env file in both the frontend and backend directories and add the following:

For Backend:
env
Copy code
DATABASE_URL="mongodb+srv://<username>:<password>@cluster.mongodb.net/chat-app"
PUSHER_APP_ID="your-pusher-app-id"
PUSHER_KEY="your-pusher-key"
PUSHER_SECRET="your-pusher-secret"
JWT_SECRET="your-jwt-secret"
For Frontend:
env
Copy code
NEXT_PUBLIC_PUSHER_KEY="your-pusher-key"
NEXTAUTH_SECRET="your-nextauth-secret"
4️⃣ Run the App
bash
Copy code
# Start the backend server
cd backend
npm run start:dev

# Start the frontend
cd frontend
npm run dev
5️⃣ Access the Application
Visit http://localhost:3000 to use the application.



**Other Tools:**
-TypeScript: For type safety
-NextAuth: Authentication library for Next.js
-Cloudinary: For image and file uploads (optional)
