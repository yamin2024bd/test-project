# Test Project

A Node.js project scaffold for building web applications. This repository is in early setup and includes environment variable support via [dotenv](https://github.com/motdotla/dotenv).

## Tech Stack

| Layer | Technology |
|-------|------------|
| Runtime | Node.js |
| Language | TypeScript (planned) |
| Framework | Next.js — App Router (planned) |
| UI | React (planned) |
| Package manager | npm |

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm (included with Node.js)

## Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd "Test Project"
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the project root:

```env
# Add your environment variables here
# Example:
# API_KEY=your_api_key
```

> **Note:** Do not commit `.env` files or other secrets to version control.

### 4. Run the project

Application scripts will be added as the project grows. For now, you can verify the setup with:

```bash
npm test
```

## Project Structure

```
Test Project/
├── cursor.md          # Project context and guidelines for Cursor AI
├── package.json       # Project metadata and dependencies
├── package-lock.json  # Locked dependency versions
└── README.md          # This file
```

## Dependencies

- **dotenv** — Loads environment variables from a `.env` file into `process.env`

## Development Guidelines

- Keep code simple and readable
- Avoid unnecessary changes; edit only what is needed
- Follow existing project conventions
- Read related files before making changes

## License

ISC
