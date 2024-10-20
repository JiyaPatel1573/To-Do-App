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
npm start
Access the application at: http://localhost:3000

