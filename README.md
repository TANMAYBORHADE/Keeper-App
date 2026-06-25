# Keeper App

A simple note-taking React application built with [Vite](https://vitejs.dev/). Create, manage, and organize your notes with an intuitive user interface.

## Features

- ✏️ Create new notes with title and content
- 📝 View all notes in a clean, organized layout
- 🗑️ Delete notes you no longer need
- ⚡ Fast development with Vite

## Tech Stack

- **React** 17.0.2 - UI library
- **Vite** - Fast build tool and dev server
- **React DOM** - DOM rendering

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone or download the project:
```bash
cd Keeper-app-React
```

2. Install dependencies:
```bash
npm install
```

### Running the App

**Development mode** - Run with hot module replacement:
```bash
npm run dev
```

The app will be available at `http://localhost:5173`

**Build for production** - Create an optimized build:
```bash
npm run build
```

**Preview the production build** - View the optimized build locally:
```bash
npm run preview
```

## Project Structure

```
Keeper-app-React/
├── public/
│   └── styles.css          # Main stylesheet
├── src/
│   ├── index.jsx           # React entry point
│   └── components/
│       ├── App.jsx         # Main App component
│       ├── CreateArea.jsx  # Note creation component
│       ├── Note.jsx        # Individual note component
│       ├── Header.jsx      # App header
│       └── Footer.jsx      # App footer
├── index.html              # HTML template
├── package.json            # Project dependencies and scripts
└── vite.config.js          # Vite configuration
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint to check code quality
- `npm run preview` - Preview production build locally

## License

This project is open source and available for personal use.
