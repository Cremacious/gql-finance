# gql-finance

A full-stack GraphQL finance tracker built with Express, Apollo Server, MongoDB, and React.

## Features

- User authentication (sign up, login, logout)
- Track financial transactions
- GraphQL API with Apollo Server
- MongoDB for data storage
- Passport.js for authentication
- Cron jobs for scheduled tasks
- Modern React frontend (Vite, TailwindCSS)

## Technologies Used

- **Backend:** Express v5, Apollo Server v4, MongoDB, Mongoose, Passport.js, GraphQL
- **Frontend:** React, Vite, Apollo Client, TailwindCSS

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- MongoDB Atlas or local MongoDB instance

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Cremacious/gql-finance.git
   cd gql-finance
   ```
2. Install backend dependencies:
   ```bash
   npm install
   ```
3. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   cd ..
   ```
4. Create a `.env` file in the root directory:
   ```env
   MONGO_URI=your_mongodb_connection_string
   SESSION_SECRET=your_session_secret
   PORT=4000
   ```

### Running the App

- Start the backend server:
  ```bash
  npm run dev
  ```
- Start the frontend (in a separate terminal):
  ```bash
  cd frontend
  npm run dev
  ```
- Backend runs at `http://localhost:4000/graphql`
- Frontend runs at `http://localhost:3000`

## Project Structure

```
gql-finance/
├── backend/
│   ├── db/
│   ├── models/
│   ├── resolvers/
│   ├── typeDefs/
│   ├── passport/
│   ├── cron.js
│   └── index.js
├── frontend/
│   └── ...
├── package.json
├── .env
└── README.md
```

## Scripts

- `npm run dev` — Start backend in development mode
- `npm start` — Start backend in production mode
- `npm run build` — Install and build frontend

## License

MIT

---

Built by Cremacious
