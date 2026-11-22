# ResolveDesk Frontend

ResolveDesk is a React dashboard for creating, filtering, and managing support tickets.

## Demo & Screenshots

- **Video Walkthrough:** [Watch the ResolveDesk Demo on Loom](https://www.loom.com/share/3d73999636fd4ce19ddc78734cf73d04)

### Dashboard Preview
[Ticket Dashboard]<img width="959" height="440" alt="image" src="https://github.com/user-attachments/assets/79121fe0-c83a-4f37-b3c7-b86eb77a3115" />

### Create & Filter Tickets
[Ticket Filtering]<img width="959" height="437" alt="image" src="https://github.com/user-attachments/assets/568d9d56-01b3-43a4-b0be-9a362c6dd7b5" />


## Requirements

- Node.js 20.19 or later, or 22.12 or later
- npm 9 or later
- A running ResolveDesk backend API

## Setup

From this directory, install dependencies and create the local environment file:

```powershell
npm install
Copy-Item .env.example .env
```

Set `VITE_API_URL` in `.env` to the backend API URL. For local development:

```env
VITE_API_URL=http://localhost:5000/api
```

## Run

```bash
npm run dev
```

Vite serves the frontend at `http://localhost:5173`.

## Checks

```bash
npm test
npm run lint
npm run build
```

The local `.env` file is ignored by Git. Keep credentials and private configuration out of the repository.
