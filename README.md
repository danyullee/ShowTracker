# ShowTracker
ShowTracker allows users to track what their currently watching and what shows they plan to watch

1. **Project Architechture**
showtracker/
├── backend/                  # FastAPI
│   ├── main.py
│   ├── models/
│   │   ├── show.py           # Pydantic models
│   │   └── user.py
│   ├── crud/                 # Database ops
│   ├── database/             # SQLite/Mongo setup
│   └── requirements.txt
├── frontend/                 # React
│   ├── src/
│   │   ├── features/
│   │   │   ├── shows/
│   │   │   └── auth/
│   │   ├── App.jsx
│   │   └── index.css
│   └── package.json
├── .github/
│   └── workflows/
│       ├── backend-ci.yml
│       ├── frontend-ci.yml
│       └── e2e-tests.yml
├── docker-compose.yml
└── README.md
