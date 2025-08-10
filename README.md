## API Overview
The Open Movie Database (OMDb) API is a RESTful web service providing detailed movie and TV series information — such as titles, plots, ratings, posters, and more — returned in JSON or XML format. It’s maintained collaboratively by users and is widely used for building media-related applications. :contentReference[oaicite:0]{index=0}

## Version
The OMDb API does not specify explicit versioning in its public documentation. It’s commonly referred to simply as “OMDb API.” :contentReference[oaicite:1]{index=1}

## Available Endpoints
- **Search by Title** (`?apikey=YOURKEY&t=MOVIE_TITLE`): Retrieves details about a movie given its title. :contentReference[oaicite:2]{index=2}
- **Search by IMDb ID** (`?apikey=YOURKEY&i=IMDB_ID`): Retrieves details using the movie’s IMDb identifier. :contentReference[oaicite:3]{index=3}
- **Search by Year** (`?apikey=YOURKEY&y=YEAR`): Filters movie information by release year. :contentReference[oaicite:4]{index=4}
- **Search by Type** (`?apikey=YOURKEY&type=TYPE`): Filters by content type (movie, series, episode). :contentReference[oaicite:5]{index=5}
- **Plot Length Options** (`?plot=short|full`): Specify length of plot description. :contentReference[oaicite:6]{index=6}

## Request and Response Format
A typical request by title:
