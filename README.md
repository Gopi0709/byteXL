# InfoHub — ByteXL Coding Challenge

Simple single-page app combining Weather, Currency Converter, and Motivational Quotes.

## Tech stack
- Frontend: React + Vite
- Backend: Node.js + Express
- External APIs: OpenWeatherMap (optional key), exchangerate.host, zenquotes.io

## Run locally
1. Backend:
   cd backend
   cp .env.example .env
   # add OPENWEATHER_API_KEY if you want
   npm install
   npm run dev

2. Frontend:
   cd frontend
   npm install
   npm run dev

Open http://localhost:5173

## Deploy
- Deploy backend on Render/Heroku/Railway. Set envs.
- Deploy frontend on Vercel. Set VITE_API_BASE to backend URL.

## Demo
- Provide public URL and 2–3 minute walkthrough video showing each module.

