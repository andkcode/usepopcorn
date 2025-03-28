# usePopcorn 🍿

## Overview

usePopcorn is a React-based movie search and watchlist application that allows users to explore movies, track watched films, and view movie statistics. The app leverages the OMDb API to fetch movie data and provides an intuitive interface for movie enthusiasts.

## Features

- **Movie Search**: Quickly search for movies using the OMDb API
- **Movie Listing**: Display search results with movie posters and basic information
- **Watched Movies Tracker**: 
  - Add movies to your watched list
  - View detailed statistics about watched movies
  - Track personal ratings and movie details

## Technologies Used

- React
- useState and useEffect Hooks
- OMDb API
- CSS for styling
- Responsive design

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or Yarn
- OMDb API Key

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/usepopcorn.git
   cd usepopcorn
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Create a `.env` file in the project root and add your OMDb API key
   ```
   REACT_APP_OMDB_API_KEY=your_api_key_here
   ```

4. Start the development server
   ```bash
   npm start
   ```

## Project Structure

- `App.js`: Main application component
- `NavBar`: Navigation bar with logo and search
- `Main`: Primary content area
- `Box`: Reusable collapsible container
- `MovieList`: Displays search results
- `WatchedMoviesList`: Shows watched movies
- `WatchedSummary`: Provides statistics on watched movies

## Key Components

### Search Functionality
- Real-time movie searching
- Displays number of search results
- Fetches data from OMDb API

### Watched Movies Tracking
- Add movies to watched list
- Calculate average ratings
- Track runtime and personal ratings

## API Integration

The app uses the OMDb API to fetch movie data:
- Endpoint: `http://www.omdbapi.com/`
- Fetches movie details based on search query
- Handles loading and error states

## State Management

Utilizes React's `useState` and `useEffect` hooks for:
- Managing movie search results
- Tracking watched movies
- Handling loading and error states

## Error Handling

- Graceful error messages for API failures
- Loading indicators during data fetch
- Fallback UI for no search results

## Performance Considerations

- Minimal re-renders using React hooks
- Efficient state management
- Async data fetching with error handling

## Potential Improvements

- Implement movie details view
- Add ability to remove movies from watched list
- Persistent storage (localStorage/database)
- Implement user authentication
- Add more detailed movie filtering

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Email: andriiwork18@gmail.com

GitHub: @andkcode.
