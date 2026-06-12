# WhisperLedger

WhisperLedger is an advanced, privacy-focused expense management suite featuring an automated mobile app, an admin dashboard, and a supporting API server.

## Project Structure

- **whisperledger-app**: The core mobile application built with React Native (Expo). Features AI-powered SMS parsing for automated expense tracking, biometric security, and cloud sync.
- **admin-dashboard**: A web-based administrative interface for managing users, broadcasts, and support tickets.
- **api-server**: The backend service providing API support for the dashboard and app.
- **lib/**: Shared libraries including database schemas (Drizzle), API specifications, and shared types.
- **scripts/**: Maintenance and utility scripts.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+)
- [pnpm](https://pnpm.io/)
- [Expo Go](https://expo.dev/client) (on your mobile device)

### Installation

```bash
pnpm install
```

### Running the App

```bash
pnpm app-dev
```

### Running the API Server

```bash
pnpm api-dev
```

### Admin Dashboard

Open `admin-dashboard/index.html` in your browser.

## Support

For issues or feature requests, please use the support portal in the Admin Dashboard.
