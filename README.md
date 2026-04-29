# Movie App

A React movie browsing app built with Vite. It lets users browse popular movies, search for titles, and save favorites locally in the browser.

## Features

- Browse popular movies from TMDB
- Search movies by title
- Add and remove favorites
- Persist favorites with localStorage
- Separate Home and Favorites pages with React Router

## Tech Stack

- React
- Vite
- React Router
- CSS
- TMDB API

## Project Structure

```text
Movie App/
  frontend/
    src/
      components/
      contexts/
      css/
      pages/
      services/
```

## Getting Started

### 1. Install dependencies

```bash
cd frontend
npm install
```

### 2. Start the development server

```bash
npm run dev
```

### 3. Build for production

```bash
npm run build
```

### 4. Preview the production build

```bash
npm run preview
```

## Available Scripts

Inside `frontend`, you can run:

- `npm run dev` to start the Vite dev server
- `npm run build` to create a production build
- `npm run preview` to preview the production build
- `npm run lint` to run ESLint

## API

This project uses The Movie Database (TMDB) API to fetch movie data.

The current API integration is in `frontend/src/services/api.js`.

## Notes

- Favorites are stored in the browser using localStorage.
- The current TMDB API key is stored directly in the frontend source. For a public repository, move it to an environment variable before sharing broadly.

## GitHub

To push this project to GitHub after creating your first commit:

```bash
git add .
git commit -m "Add project README"
git push
```
