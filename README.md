# nastrzala-be

Backend server for Nastrzala application built with Node.js, Express, and TypeScript.

## Features

- ✅ Node.js with Express server
- ✅ TypeScript support
- ✅ CORS enabled for local development
- ✅ JSON request body parsing
- ✅ Health check endpoint

## Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn

## Installation

```bash
npm install
```

## Development

Run the server in development mode with hot reload:

```bash
npm run dev
```

## Production

Build the TypeScript code:

```bash
npm run build
```

Start the production server:

```bash
npm start
```

## API Endpoints

- `GET /` - Welcome message
- `GET /health` - Health check endpoint

## Configuration

The server runs on port 3000 by default. You can change this by setting the `PORT` environment variable:

```bash
PORT=8080 npm start
```

## CORS

CORS is enabled for all origins (`*`) with credentials support for local development.