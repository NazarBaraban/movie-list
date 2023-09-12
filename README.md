# Movies List
Rendered a list of movies from the provided moviesFromServer array within the App component initially.
Extracted the rendering of movies into a separate MoviesList component.
Passed the moviesFromServer data to the MoviesList component as a movies prop.
Further abstracted the rendering of individual movie cards into a MovieCard component.
The MoviesList component now passes each movie as a movie prop to the MovieCard.
Utilized the movie.imdbId as the unique key for each movie card.
Maintained the data-cy attributes for testability, ensuring that the tests continue to function as expected.


[DEMO LINK](https://nazarbaraban.github.io/react_movies-list-js/) 