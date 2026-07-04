# URL Shortener

A simple full-stack URL shortener built with the MERN stack. It lets users convert long URLs into short, easy-to-share links while keeping track of the URLs associated with their account.

## Features

- Shorten long URLs with a single click.
- Redirect users to the original website using the generated short link.
- User authentication with cookie-based sessions.
- Store and manage shortened URLs for each logged-in user.

---

## Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Frontend
- React
- Vite
- ESLint

---

## Project Structure

```text
├── BACKEND/
│   ├── src/
│   ├── app.js
│   └── package.json
└── FRONTEND/
    ├── src/
    ├── index.html
    ├── vite.config.js
    └── package.json
```

---

## How It Works

1. Users sign in or create an account.
2. A long URL is submitted through the frontend.
3. The backend generates a unique short code and stores it in MongoDB.
4. When someone visits the shortened URL, the server looks up the original link and redirects them automatically.

---

## Getting Started

### Clone the repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### Backend

```bash
cd BACKEND
npm install
npm start
```

### Frontend

```bash
cd FRONTEND
npm install
npm run dev
```

---

## Future Improvements

- URL analytics (click count, location, device information)
- Custom short URLs
- QR code generation
- Link expiration
- User dashboard with search and filters
