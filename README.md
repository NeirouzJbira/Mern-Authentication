# Mern-Authentication

Minimal full-stack MERN app with authentication using passport and JWTs.

This project uses the following technologies:
-React and React Router for frontend
- Express and Node for the backend
- MongoDB for the database
- Redux for state management between React components



## Configuration

Make sure to add your own `MONGOURI` from your database in `config/keys.js`.

```javascript
module.exports = {
  mongoURI: "YOUR_MONGO_URI_HERE",
  secretOrKey: "secret"
};
```

## Quick Start

```javascript
// Install dependencies for server & client
npm install 

// Run client & server with concurrently
npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000
```


