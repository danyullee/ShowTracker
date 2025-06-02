# ShowTracker
ShowTracker allows users to track what their currently watching and what shows they plan to watch

1. **Project Architecture**
📁 showtracker/
│
├── 🚀 backend/ (FastAPI server)
│ ├── main.py - Core API routes
│ ├── models/ - Data schemas
│ │ ├── show.py - Show tracking model
│ │ └── user.py - Authentication model
│ ├── crud/ - Database operations
│ ├── database/ - DB connection setup
│ └── requirements.txt - Python dependencies
│
├── 🎨 frontend/ (React app)
│ ├── src/features/ - Feature modules
│ │ ├── shows/ - Show tracking UI
│ │ └── auth/ - Login/signup flows
│ ├── App.jsx - Main component
│ └── index.css - Global styles
│
├── 🔧 .github/workflows/ (CI/CD Automation)
│ ├── backend-ci.yml - Python tests & Docker builds
│ ├── frontend-ci.yml - React builds & deploys
│ └── e2e-tests.yml - Playwright browser tests
│
├── 🐳 docker-compose.yml - One-command dev setup
