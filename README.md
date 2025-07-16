# Express TypeScript Node.js Boilerplate

<p align="center">
  <b>A minimalist, production-ready foundation for building Express.js applications with TypeScript</b>
</p>

## 📋 Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Environment Variables](#environment-variables)
- [Logging](#logging)
- [Code Style](#code-style)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **TypeScript Support** - Write type-safe code with TypeScript
- **Express.js Framework** - Fast, unopinionated, minimalist web framework for Node.js
- **Clean Architecture** - Well-organized project structure for scalability
- **Environment Configuration** - Easy environment variable management with [dotenv](https://www.npmjs.com/package/dotenv)
- **Logging System** - Comprehensive logging with [winston](https://www.npmjs.com/package/winston) & [morgan](https://www.npmjs.com/package/morgan)
- **Code Quality Tools**
  - Prettier for consistent code formatting
  - ESLint for code quality
  - Pre-configured rules and settings
- **Error Handling** - Centralized error handling middleware
- **API Documentation** - Ready for API documentation
- **Request Parsing** - Built-in JSON and cookie parsing support
- **Development Tools** - Hot-reload for faster development

## 🔧 Prerequisites

- Node.js (version >= 14.0.0)
- npm or yarn
- Git

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/express-typescript-nodejs-boilerplate.git
   cd express-typescript-nodejs-boilerplate
   ```

2. Install dependencies:
   ```bash
   npm install --legacy-peer-deps
   # or
   yarn install
   ```

3. Create a `.env` file in the root directory:
   ```env
   PORT=3000
   NODE_ENV=development
   ```

4. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

## 📁 Project Structure

```
src/
├── app.ts              # Express app configuration
├── handlers/           # Request handlers
├── helpers/           # Helper functions
├── middlewares/       # Custom middlewares
├── routes/            # API routes
└── utils/            # Utility functions
```

## 📜 Available Scripts

- `npm run dev` - Start the development server with hot-reload
- `npm run build` - Build the TypeScript code
- `npm start` - Start the production server
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier
- `npm test` - Run tests (when implemented)

## 🔐 Environment Variables

The following environment variables can be configured:

| Variable    | Description           | Default     |
|-------------|--------------------|-------------|
| PORT        | Server port number | 3000        |
| NODE_ENV    | Environment name   | development |

## 📝 Logging

This boilerplate uses:
- **Winston** for application logging
- **Morgan** for HTTP request logging

Logs are configured in `src/utils/logger.ts`

## 💅 Code Style

- We use ESLint and Prettier to maintain code quality
- Configure rules in `.eslintrc.js` and `.prettierrc`
- Run `npm run format` to automatically format code

## 👥 Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and development process.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
