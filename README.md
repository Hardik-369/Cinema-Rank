# CinemaRank - Top Movies Dashboard

CinemaRank is a visually stunning web application that displays the top-rated movies of all time in an interactive dashboard. Built with modern web technologies, it provides an elegant interface for exploring cinema's greatest achievements.

## Features

- **Beautiful UI/UX**: Modern gradient design with glass-morphism cards and smooth animations
- **Comprehensive Movie Database**: Over 200 of the highest-rated movies with detailed information
- **Powerful Search & Filtering**: 
  - Search by movie title
  - Filter by rating (R, PG-13, PG, etc.)
  - Sort by rank, rating, year, or title
- **Interactive Statistics**: Real-time stats including total movies, average rating, top decade, and longest runtime
- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop
- **Performance Optimized**: Efficient loading and rendering with loading shimmer effects

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS with custom animations
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)
- **Data**: JSON (local data storage)

## Project Structure

```
├── index.html          # Main HTML file
├── data.json           # Movie database (200+ movies)
├── README.md           # This file
```

## How to Run

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. No additional setup or dependencies required

## Key Components

### Header Section
- Hero gradient background with project title
- Search input for finding movies by title
- Sort and filter controls

### Statistics Dashboard
- Total movies count
- Average rating across all movies
- Top decade representation
- Longest runtime movie

### Movie Cards
Each movie card displays:
- Rank badge with position
- Title and star rating
- Release year and runtime
- MPAA rating with color-coded tag
- Interactive star visualization

### Responsive Design
- Grid layout adjusts based on screen size:
  - 1 column on mobile
  - 2 columns on tablet
  - 3 columns on desktop

## Data Source

The application uses a comprehensive dataset of over 200 top-rated movies, including classics like:
- The Shawshank Redemption
- The Godfather
- The Dark Knight
- Pulp Fiction
- Forrest Gump
- Inception
- Interstellar
- Parasite
- And many more...

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Development

This is a client-side only application with no build process required. Simply open the `index.html` file in a browser to run.

## Future Enhancements

- Add movie details modal with extended information
- Implement pagination for better performance with large datasets
- Add dark/light theme toggle
- Include movie posters and additional metadata
- Add "Top Movies by Genre" feature
- Implement user ratings and reviews

## Author

Created as part of the Smart India Hackathon (SIH) preparation.

## License

This project is open source and available under the MIT License.