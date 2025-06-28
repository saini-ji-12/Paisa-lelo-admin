Paisa-lelo-admin

A full-stack money earning web application and admin dashboard inspired by RewardX.

## Structure

- `/client` — User-facing web app (React)
- `/admin` — Admin dashboard (React)
- `/server` — Backend API (Node.js/Express)
- `/shared` — Shared code (types, utilities)

## Getting Started

1. Clone the repo.
2. Install dependencies in each folder:
   ```bash
   cd client && npm install
   cd ../admin && npm install
   cd ../server && npm install
   ```
3. Start development servers:
   - Client: `cd client && npm start`
   - Admin: `cd admin && npm start`
   - Server: `cd server && npm run dev`

## Features

- User registration, login, wallet, task earning, and reward redemption
- Admin dashboard for user/task/reward management, analytics, and payout controls

## Tech Stack

- React (client & admin)
- Node.js/Express (server)
- MongoDB (database)
