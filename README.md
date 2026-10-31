# usePopcorn

React movie app for searching films, rating them and keeping track of what you have watched. Built while following a React course on Udemy, so this is learning work and not an original project.

## Features

- Search against the OMDb API, with outdated requests canceled as you type
- Detail view with a custom star rating component
- Watched list with statistics, saved in `localStorage`
- Keyboard shortcuts for the search field and for closing the detail view

## What this project demonstrates

- Custom hooks: `useMovies`, `useLocalStorageState` and `useKey`
- `useEffect` with cleanup, and `useRef`
- Reusable components

## Running the project

You need a free key from the [OMDb API](https://www.omdbapi.com/apikey.aspx) and Node 20.

```bash
npm ci
cp .env.example .env
npm start
```

Add your key as `REACT_APP_OMDB_KEY` in `.env` before starting the app.
