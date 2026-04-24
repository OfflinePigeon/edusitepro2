# EDUsite

Educational Activities Learning Portal — Ultraviolet proxy.

## Structure
```
EDUsite/
├── public/          ← static files served to browser
│   ├── index.html
│   ├── index.css
│   ├── index.js
│   ├── search.js
│   ├── register-sw.js
│   ├── plus.png
│   └── uv/
│       └── uv.config.js
├── src/
│   └── index.js     ← Node.js server
├── package.json
└── .gitignore
```

## Deploy

```bash
npm install
npm start
```

Server runs on port 8080 by default, or $PORT if set.
