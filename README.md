# Random Quote Generator - React HW 22

This project is a simple React application bootstrapped with [Vite](https://vitejs.dev/). It fetches random quotes from the [ZenQuotes API](https://zenquotes.io/) and lets you request a new one with a single click. State is managed using Redux Toolkit and asynchronous requests are handled by Axios.

## Features

- Fetches a random quote and its author from a public API.
- Uses Redux Toolkit for state management.
- Styled with CSS Modules.
- Built with Vite for fast development and HMR.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and npm installed.

### Installation

```bash
npm install
```

### Running the app

```bash
npm run dev
```

The application will be available at <http://localhost:5173> (or the port Vite chooses).

### Other scripts

- `npm run build` – bundle the app for production.
- `npm run lint` – run ESLint over the project files.
- `npm run preview` – locally preview the production build.

## Project Structure

```
src/
  components/
    quote/          # Quote component and styles
  redux/
    slices/         # Redux slice for quote state
    store.js        # Redux store configuration
```

## API

Quotes are retrieved from [https://zenquotes.io/api/random](https://zenquotes.io/api/random). API key is required.
