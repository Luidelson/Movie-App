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

## API

This project uses The Movie Database (TMDB) API to fetch movie data.

The current API integration is in `frontend/src/services/api.js`.

## Notes

- Favorites are stored in the browser using localStorage.
- The current TMDB API key is stored directly in the frontend source. For a public repository, move it to an environment variable before sharing broadly.
