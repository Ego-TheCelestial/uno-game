## FOLDER STRUCTURE

uno-game\
│\
│── client # Frontend (React)\
│ │── public\
│ │── src\
│ │ ├── assets # Images, sounds\
│ │ ├── components # Reusable UI components\
│ │ ├── pages # Lobby, GameRoom, etc.\
│ │ ├── context # Game state via context API\
│ │ ├── hooks # Custom React hooks (e.g., socket)\
│ │ ├── services # API and socket clients\
│ │ ├── utils # Helper functions\
│ │ ├── App.jsx\
│ │ ├── main.jsx\
│ │ └── index.css\
│ │\
│ └── vite.config.js\
│\
│── server # Backend (Node.js)\
│ ├── config # DB config, dotenv\
│ ├── controllers # Game room, player actions\
│ ├── models # Mongoose schemas (User, Room, etc.)\
│ ├── routes # REST APIs (optional)\
│ ├── sockets # All Socket.IO handlers\
│ ├── gameEngine # UNO logic, rules, deck generator\
│ ├── utils # Helper functions\
│ ├── middleware # (Optional) Error, Auth, etc.\
│ ├── server.js # Main entry file\
│ └── .env\
│\
│── shared # Shared data between FE & BE\
│ └── constants.js # Card colors, types, actions, etc.\
│\
│── README.md\
└── .gitignore
