# Traveling — Backend API

Backend API for the Traveling website, built with Node.js, Express and
MongoDB. It provides the data and authentication layer used by the React
frontend.

Related repositories:

- Frontend: [traveling-website](https://github.com/sahilmyadav/traveling-website)
- Frontend variant: [traveling-frontend](https://github.com/sahilmyadav/traveling-frontend)

## Features

- REST API organised into controllers, models and routes
- Password hashing with bcryptjs and cookie handling
- CORS and dotenv-based configuration

## Tech Stack

- Node.js (ES modules), Express
- MongoDB, bcryptjs, cookie-parser, cors

## Getting Started

```bash
npm install
npm start
```

Add a `.env` file with your MongoDB URI and secrets first. Entry point is
`index.js`.

## Project Structure

```
controllers/   Request handlers
models/        Database models
routes/        API routes
utils/         Helpers
```
