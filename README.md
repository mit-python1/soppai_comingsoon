# Soppai Intellisense

Solar power forecasting platform connected to the Reva Solar Plant. React/Vite frontend with a Python backend, plus a companion Android weather app.

## Tech Stack

- **Frontend:** React, Vite, Lucide React
- **Backend:** Python (HTTP server, APScheduler, smtplib)
- **Mobile:** React Native, Expo

## Setup

Frontend:

```bash
cd Solar_UI
npm install
npm run dev
```

Backend:

```bash
python ui_config_server.py
```

## Project Structure

```
Soppai/
├── Solar_UI/            # React + Vite web app
├── WeatherAppNative/    # React Native weather app
└── ui_config_server.py  # Python backend
```
