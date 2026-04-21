# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

```bash
npm install      # Install dependencies
npm run dev      # Start dev server at http://localhost:5173
npm run build    # Build for production
npm run lint     # Run ESLint
npm run preview  # Preview production build
```

## Project Structure

This is a React + Vite expense tracker starter project. The main application code lives in `src/`:

- `src/main.jsx` - Entry point, renders the App component
- `src/App.jsx` - Main application component, manages state and coordinates child components
- `src/components/Summary.jsx` - Displays income/expense totals
- `src/components/TransactionForm.jsx` - Add transaction form with description, amount, type, and category inputs
- `src/components/TransactionList.jsx` - Transaction table with filtering by type and category
- `src/App.css` / `src/index.css` - Styling

The app uses React 19 with Vite 7 for bundling and includes ESLint for code quality.