# usePopcorn 🎬

usePopcorn is a movie search and watchlist application built with React. It uses the OMDb API to fetch movie information and includes a custom star-rating component so you can give movies your own ratings when adding them to your watchlist.

## Features

- **Search movies:** Find movies using data retrieved from the OMDb API.
- **View movie details:** See movie information such as its IMDb rating and runtime.
- **Create a personal watchlist:** Add movies you want to keep track of.
- **Rate movies yourself:** Use the custom star-rating component to give each movie a personal rating.
- **Compare ratings:** Keep the movie's IMDb rating separate from your own rating in the watchlist.

## Tech Stack

- React
- JavaScript
- CSS
- [OMDb API](https://www.omdbapi.com/) for movie data
- Create React App

## Getting Started

### Prerequisites

- [Node.js and npm](https://nodejs.org/)
- An API key from [OMDb API](https://www.omdbapi.com/apikey.aspx)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   ```

2. Move into the project folder:

   ```bash
   cd YOUR-REPOSITORY
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Configure your OMDb API key. If the app reads the key from an environment variable named `REACT_APP_OMDB_API_KEY`, create a `.env` file in the project root and add:

   ```env
   REACT_APP_OMDB_API_KEY=your_omdb_api_key
   ```

   Replace the placeholder with your own API key. If your code uses a different environment-variable name or configuration method, follow the name and approach used in the project. Keep `.env` out of Git and never commit your actual API key.

5. Start the development server:

   ```bash
   npm start
   ```

   Create React App will start the app, usually at `http://localhost:3000`.

## How to Use

1. Search for a movie.
2. Select a result to view its information.
3. Use the custom star-rating component to choose your personal rating.
4. Add the movie to your watchlist.
5. Review the watchlist to compare the movie's IMDb rating with your own rating and see its runtime.

## Project Purpose

This project demonstrates working with an external movie API, managing React application state, building a reusable interactive star-rating component, and maintaining a watchlist with personal ratings.
