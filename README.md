# This is the Movies API

## It's hosted at https://moviesbackapi.herokuapp.com/api

## API Endpoints

### All Endpoints starts with the above link + the specified route.

## GET ENDPOINTS

### {URL}/movies
This endpoint collects all the movies from the database.

### {URL}/movies/:id
This endpoint gets the data of the movie with the requested id.

### {URL}/movies/recomended/:rating
This endpoint collects every movie with a rating equal or above as specified in the route. (Recieves a number between 1 to 10).

### {URL}/genres
This endpoint gets a list of all genres in database.

### {URL}/genres/:id
Selects a specific genre by its id and gets all the information.

### {URL}/genres/:id/movies
Gets all the movies with the selected genre.

### {URL}/actors
Gets a list of all actors in database.

### {URL}/actors/:id
Gets the information of the selected actor/actress.

### {URL}/actors/:id/movies
Gets all the movies where the selected actor/actress worked at.