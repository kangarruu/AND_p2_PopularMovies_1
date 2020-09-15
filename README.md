# AND_p2_PopularMovies_1
## Udacity Android Developer Nanodegree project 2 (Stage 1 of 2) 


## Project Overview
This is stage one of two of the Popular Movies project. In this stage I built the core experience of the movie app. The app showcases building clean and compelling user interfaces, fetching data from network services, and optimizing the experience for various mobile devices.

## Getting Started
In order to build the app you must provide your own API key from [The Movie Database (TMDb)](https://www.themoviedb.org/documentation/api) API. Please request an [API Key](https://www.themoviedb.org/documentation/api) and enter it into the gradle.properties file:

```gradle.properties
MOVIE_DB_API_KEY="Your Api Key"
```

## Features
*   Fetch data from the Internet with theMovieDB API.
*   Use adapters and custom list layouts to populate list views to present the user with a grid arrangement of movie posters upon launch.
*   Allow the user to change sort order by most popular or by highest-rated
*   Allow the user to tap on a movie poster and transition to a details screen with additional information such as original title, movie poster image thumbnail, A plot synopsis, user rating, release date
