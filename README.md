# Movie-Searcher App

An elegant web application that allows you to search and discover detailed information about your favorite movies, TV series, and games using the OMDB API.

## Features

- 🎬 **Search Movies & TV Series** - Find detailed information about movies and TV shows
- 🎮 **Search by ID** - Look up content using OMDB ID
- 📋 **Pagination** - Browse through search results easily
- 🎨 **Responsive Design** - Modern and user-friendly interface
- 📊 **Comprehensive Details** - View plot, ratings, cast, release date, and more

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v12 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/TheInfinity007/Movie-Search-App.git
cd Movie-Search-App
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OMDB API key:
```
OMDB_API_KEY=your_api_key_here
```

> Get your free API key from [OMDB API](http://www.omdbapi.com/apikey.aspx)

## Configuration

Update the `config.js` file with your OMDB API configuration if needed.

## Usage

1. Start the application:
```bash
npm start
```

2. Open your browser and navigate to:
```
http://localhost:3000
```

3. Use the search interface to find:
   - Movies by title (with optional year filter)
   - TV series by title
   - Content by OMDB ID

## Project Structure

```
Movie-Searcher-App/
├── app.js                 # Main application file
├── config.js              # Configuration file
├── package.json           # Project dependencies
├── README.md              # This file
├── public/                # Static files
│   ├── images/           # Image assets
│   └── stylesheets/
│       └── main.css      # Main stylesheet
└── views/                # EJS templates
    ├── search.ejs        # Search page
    ├── results.ejs       # Search results page
    ├── show.ejs          # Movie details page
    └── partials/
        ├── header.ejs    # Header template
        └── footer.ejs    # Footer template
```

## Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: EJS (Embedded JavaScript templating)
- **Styling**: CSS
- **HTTP Client**: request
- **Middleware**: body-parser
- **Environment Management**: dotenv
- **API**: OMDB API

## Dependencies

- `express` - Web framework for Node.js
- `ejs` - Templating engine
- `body-parser` - Middleware for parsing request bodies
- `request` - HTTP client for API calls
- `dotenv` - Environment variable management

## API Reference

This app uses the **OMDB API** (Open Movie Database) for fetching movie and TV show data.

Learn more: [OMDB API Documentation](http://www.omdbapi.com/)

## License

ISC

## Author

TheInfinity007

## Repository

[GitHub Repository](https://github.com/TheInfinity007/Movie-Search-App)
