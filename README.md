# Express Health Check Backend

A simple Node.js and Express backend repository with a health check route.

## Getting Started

### Prerequisites
- Node.js (v18 or newer recommended)
- npm

### Installation

```bash
npm install
```

### Running the Server

#### Production / Standard Run
```bash
npm start
```

#### Development Mode (with auto-reload)
```bash
npm run dev
```

The server will listen by default on `http://localhost:3000`. You can configure the port using the `PORT` environment variable:

```bash
PORT=4000 npm start
```

## API Routes

### `GET /health`

Returns the health status, uptime, and current server timestamp.

**Response Example:**
```json
{
  "status": "ok",
  "uptime": 12.345,
  "timestamp": "2026-10-11T03:31:00.000Z"
}
```
