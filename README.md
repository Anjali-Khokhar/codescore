# codeScore
##project link:https://codescore-qklf-kw0b63xrm-anjalis-projects-6ec3dd57.vercel.app
## Project Overview

codeScore is a web application for analyzing and scoring code quality. It provides an intuitive interface for uploading code, viewing analysis results, and understanding code quality metrics. The project leverages modern web technologies for a fast and responsive user experience.

## Features
- Upload and analyze code files
- View code quality scores and breakdowns
- User authentication and protected routes
- Modern, responsive UI

## Tech Stack
- **Vite**
- **TypeScript**
- **React**
- **shadcn-ui**
- **Tailwind CSS**
- **Supabase** (for authentication and backend)

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [bun](https://bun.sh/)

### Installation

Clone the repository:
```sh
git clone <YOUR_GIT_URL>
cd codeScore-main
```

Install dependencies:
```sh
npm install
# or
bun install
```

### Running the Development Server
```sh
npm run dev
# or
bun run dev
```

The app will be available at `http://localhost:5173` by default.

### Building for Production
```sh
npm run build
# or
bun run build
```

### Linting
```sh
npm run lint
```

## Project Structure
- `src/` - Main source code
  - `components/` - React components
  - `pages/` - Page components (routes)
  - `contexts/` - React context providers
  - `hooks/` - Custom React hooks
  - `integrations/` - External service integrations (e.g., Supabase)
  - `lib/` - Utility functions
  - `utils/` - Code analysis and PDF generation utilities

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License
This project is licensed under the MIT License.
