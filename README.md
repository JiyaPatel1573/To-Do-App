<h1>🚀 Full-Stack Todo List Application</h1>
<div align="center">
  <img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</div>
<h2>📑 Table of Contents</h2>

📋 Features
🛠️ Tech Stack
🚀 Getting Started
💻 Installation
🔧 Configuration
📦 Deployment
🧪 Testing
🤝 Contributing
📄 License

<h2 id="features">📋 Features</h2>

✅ Create, read, update, and delete tasks
✅ Mark tasks as completed
✅ Responsive design for mobile and desktop
✅ Real-time updates
✅ Clean and intuitive user interface
✅ Data persistence with MongoDB
✅ RESTful API architecture

<h2 id="tech-stack">🛠️ Tech Stack</h2>
<h3>Frontend</h3>

Next.js - React framework
React Hooks - State management
Tailwind CSS - Styling
Axios - API requests

<h3>Backend</h3>

Node.js - Runtime environment
Express.js - Web framework
MongoDB - Database
Mongoose - ODM
Cors - Cross-origin resource sharing

<h2 id="getting-started">🚀 Getting Started</h2>
<h3>Prerequisites</h3>

Node.js (v14 or higher)
MongoDB (local or Atlas)
Git

bashCopy# Verify Node.js installation
node --version

# Verify npm installation
npm --version
<h2 id="installation">💻 Installation</h2>

Clone the repository

bashCopygit clone https://github.com/yourusername/todo-list-app.git
cd todo-list-app

Setup Backend

bashCopy# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create environment file
cp .env.example .env

Setup Frontend

bashCopy# Navigate to frontend directory
cd ../frontend

# Install dependencies
npm install

# Create environment file
cp .env.example .env.local
<h2 id="configuration">🔧 Configuration</h2>
<h3>Backend Environment Variables (.env)</h3>
envCopyMONGODB_URI=your_mongodb_connection_string
PORT=5000
NODE_ENV=development
<h3>Frontend Environment Variables (.env.local)</h3>
envCopyNEXT_PUBLIC_API_URL=http://localhost:5000/api
<h2 id="running">▶️ Running the Application</h2>

Start Backend Server

bashCopycd backend
npm run dev

Start Frontend Development Server

bashCopycd frontend
npm run dev
Access the application at: http://localhost:3000
<h2 id="deployment">📦 Deployment</h2>
<h3>Backend Deployment (Railway)</h3>

Create Railway account
Install Railway CLI:

bashCopynpm i -g @railway/cli

Deploy:

bashCopyrailway up
<h3>Frontend Deployment (Vercel)</h3>

Create Vercel account
Install Vercel CLI:

bashCopynpm i -g vercel

Deploy:

bashCopyvercel
<h2 id="testing">🧪 Testing</h2>
<h3>Running Tests</h3>
bashCopy# Backend tests
cd backend
npm test

# Frontend tests
cd frontend
npm test
<h2 id="api">📡 API Endpoints</h2>
MethodEndpointDescriptionGET/api/tasksGet all tasksPOST/api/tasksCreate new taskPUT/api/tasks/:idUpdate taskDELETE/api/tasks/:idDelete task
<h2 id="folder-structure">📁 Project Structure</h2>
Copytodo-list-app/
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   │   ├── layout.js
│   │   │   ├── page.js
│   │   │   └── globals.css
│   │   ├── components/
│   │   ├── hooks/
│   │   └── styles/
│   ├── public/
│   └── package.json
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
│   └── package.json
└── README.md
<h2 id="contributing">🤝 Contributing</h2>

Fork the repository
Create your feature branch:

bashCopygit checkout -b feature/AmazingFeature

Commit your changes:

bashCopygit commit -m 'Add some AmazingFeature'

Push to the branch:

bashCopygit push origin feature/AmazingFeature

Open a Pull Request

<h2 id="troubleshooting">❗ Troubleshooting</h2>
<h3>Common Issues</h3>

MongoDB Connection Issues

bashCopy# Check if MongoDB is running
mongosh

Port Already in Use

bashCopy# Kill process using port 5000
sudo lsof -i :5000
kill -9 PID
<h2 id="license">📄 License</h2>
This project is licensed under the MIT License - see the LICENSE file for details.
<h2 id="acknowledgments">👏 Acknowledgments</h2>

Next.js Documentation
Express.js Documentation
MongoDB Documentation
Tailwind CSS Documentation

<div align="center">
  <h3>🌟 Don't forget to star this repository if you found it helpful! 🌟</h3>
</div>

<div align="center">
  Made with ❤️ by [Your Name]
</div>
