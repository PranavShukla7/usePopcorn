# usePopcorn

A React application for searching and managing your movie watchlist. Search for movies using the OMDB API, view detailed information, rate them, and keep track of watched movies.

## Features

- **Movie Search**: Search for movies by title using the OMDB API.
- **Movie Details**: View detailed information including plot, actors, director, runtime, and IMDb rating.
- **Star Rating**: Rate movies with a custom star rating component.
- **Watched List**: Add movies to your watched list, view summaries, and delete entries.
- **Local Storage**: Persist your watched list using local storage.
- **Keyboard Shortcuts**: Use 'Enter' to focus the search input and 'Escape' to close movie details.
- **Responsive Design**: Clean and responsive UI for a great user experience.

## Tech Stack

- **React**: 19.1.0
- **JavaScript**: ES6+
- **CSS**: Custom styles
- **API**: OMDB API for movie data
- **Testing**: Jest and React Testing Library

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/usepopcorn.git
   cd usepopcorn
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Get an API key from [OMDB API](http://www.omdbapi.com/apikey.aspx) and replace the `KEY` constant in `src/App.js` with your key.

4. Start the development server:

   ```bash
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Usage

- Enter a movie title in the search bar to find movies.
- Click on a movie to view its details.
- Rate the movie using the star rating component and add it to your watched list.
- View your watched movies summary and manage your list.

## Scripts

- `npm start`: Runs the app in development mode.
- `npm test`: Launches the test runner.
- `npm run build`: Builds the app for production.
- `npm run eject`: Ejects from Create React App (irreversible).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is private and not licensed for public use.
