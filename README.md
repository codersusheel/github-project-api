github-project-api/
│
├── package.json
├── server.js
├── .env
├── .env.example
├── .gitignore
│
├── config/
│   └── config.js
│
├── src/
│   ├── github/
│   │   ├── github-api.js
│   │   ├── repositories.js
│   │   └── repository.js
│   │
│   ├── parser/
│   │   └── haproven-md.js
│   │
│   ├── analyzer/
│   │   ├── project-score.js
│   │   └── project-analyzer.js
│   │
│   ├── api/
│   │   ├── projects.js
│   │   ├── profile.js
│   │   └── project.js
│   │
│   └── utils/
│       ├── cache.js
│       └── helpers.js
│
├── public/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── app.js
│
└── README.md