# Tic Tac Toe Frontend (React)

A retro-themed Tic Tac Toe game for the web. This is a **two-player, same-device** game that displays the board and announces a winner (or draw) when the game ends.

## Requirements

- Node.js + npm (LTS recommended)

## Setup

From this folder:

```bash
npm install
```

## Run (Development)

```bash
npm start
```

By default, the app runs on port **3000** and will open in your browser automatically.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.

### `npm test`

Runs tests in watch mode (Create React App default).

### `npm run build`

Builds the app for production into the `build/` folder.

### `npm run eject`

Ejects the Create React App configuration (not recommended unless you know you need it).

## Configuration (Environment Variables)

This container supports the following environment variables (configured via the container `.env`):

- `REACT_APP_API_BASE`
- `REACT_APP_BACKEND_URL`
- `REACT_APP_FRONTEND_URL`
- `REACT_APP_WS_URL`
- `REACT_APP_NODE_ENV`
- `REACT_APP_NEXT_TELEMETRY_DISABLED`
- `REACT_APP_ENABLE_SOURCE_MAPS`
- `REACT_APP_PORT`
- `REACT_APP_TRUST_PROXY`
- `REACT_APP_LOG_LEVEL`
- `REACT_APP_HEALTHCHECK_PATH`
- `REACT_APP_FEATURE_FLAGS`
- `REACT_APP_EXPERIMENTS_ENABLED`

Notes:
- In Create React App, only variables prefixed with `REACT_APP_` are exposed to the browser bundle.
- If you change environment variables, you typically need to restart `npm start` for them to take effect.

## How to Play

1. Open the app in your browser.
2. Players take turns placing their marks on the 3×3 grid.
3. The game ends when a player gets three in a row, or when all squares are filled (draw).

## Troubleshooting

- **Port already in use**: stop the process using port 3000 or adjust your environment configuration to use a different port.
- **Blank page after build**: ensure the app is served from the correct base path (typical CRA deployment consideration).

## License

Internal project / template-based. Add a license file if you plan to distribute this publicly.
