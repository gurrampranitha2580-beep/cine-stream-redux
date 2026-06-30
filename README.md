# CineStream 🎬

This is a movie browsing app built using Next.js and Redux Toolkit.  
I built it as part of a frontend assignment to practice global state management and API integration.

---

## What it does

- Shows popular movies from TMDB API
- Search movies in real time
- Filter movies by genre and release year
- Add/remove favorites
- Infinite scroll for loading more movies
- Global state handled using Redux Toolkit

---

## Tech used

- Next.js
- React
- Redux Toolkit
- React Redux
- TMDB API
- CSS

---

## How state is handled

I used Redux Toolkit for managing global state instead of prop drilling.

There are two main slices:
- favorites → stores liked movies
- filters → handles genre and year filtering

This helps keep state shared across Navbar, MovieCard, and sidebar.

---

## Features breakdown

### Favorites
Clicking the heart icon adds/removes movies from global favorites.  
Navbar updates instantly with count.

### Search
Typing in search box fetches results from API with a small delay to avoid too many calls.

### Filters
Sidebar filters movies based on selected genre and year.  
Everything updates instantly because of Redux state.

### Infinite scroll
More movies load automatically when scrolling down using IntersectionObserver.

---

## What I learned

- How Redux Toolkit actually works in real apps
- How to structure a scalable React project
- How to connect API + UI + global state properly
- Performance basics using useMemo and useCallback

---

## Run locally

```bash
npm install
npm run dev
