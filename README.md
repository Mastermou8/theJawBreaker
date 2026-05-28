# theJawBreaker
A simple website

TheJawBreaker/
├── backend/                                                   
│   ├── config/               # Database connection strings
│   ├── models/               # MongoDB Schemas (Event.js, Announcement.js)
│   ├── routes/               # API endpoints (auth.js, events.js)
│   ├── middleware/           # Security guards (checking if someone is an admin)
│   ├── server.js             # Server entry point
│   └── package.json          # Server dependencies (express, mongoose, dotenv)
│                                  
└── frontend/                                                                   
    ├── public/                                  
    ├── src/                                  
    │   ├── admin/                                   
    │   │   ├── login/                                  
    │   │   ├── logout/                                  
    │   │   ├── panel/                                  
    │   │   ├── add-event/                                  
    │   │   ├── edit-event/                                  
    │   │   └── delete-event/                                  
    │   ├── user/                                            
    │   │   ├── pages/                                  
    │   │   ├── contact-us/                                  
    │   │   └── google-drive/                                  
    │   ├── shared/                                           
    │   ├── App.jsx           # Main routing and global state
    │   └── main.jsx                                  
    └── package.json          # Frontend dependencies (react, react-router-dom)
