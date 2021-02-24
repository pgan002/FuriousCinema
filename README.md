# FuriousCinema
Web app for a cinema that shows moves from The Fast and The Furious

A small cinema, which only plays movies from the [Fast & Furious](https://en.wikipedia.org/wiki/The_Fast_and_the_Furious) franchise, is looking to develop a mobile/web app for their users. Specifically, they wish to support the following functions:

* An internal endpoint in which they (i.e. the cinema owners) can update show times and prices for their movie catalog
* An endpoint in which their customers (i.e. moviegoers) can fetch movie times
* An endpoint in which their customers (i.e. moviegoers) can fetch details about one of their movies (e.g. name, description, release date, rating, IMDb rating, and runtime). Even though there's a limited offering, please use the OMDb APIs (detailed below) to demonstrate how to communicate across APIs.
* An endpoint in which their customers (i.e. moviegoers) can leave a review rating (from 1-5 stars) about a particular movie

* Creating a persistence layer to save results for certain actions (e.g. via SQL/NoSQL/etc)
* Present API documentation leveraging OpenAPI/Swagger 2.0 standard

## Movie Catalog

This cinema plays the following movies:

| Title | IMDb ID |
| :- | :- |
| [The Fast and the Furious](https://www.imdb.com/title/tt0232500) | tt0232500 |
| [2 Fast 2 Furious](https://www.imdb.com/title/tt0322259) | tt0322259 |
| [The Fast and the Furious: Tokyo Drift](https://www.imdb.com/title/tt0463985)| tt0463985 |
| [Fast & Furious](https://www.imdb.com/title/tt1013752) | tt1013752 |
| [Fast Five](https://www.imdb.com/title/tt1596343) | tt1596343 |
| [Fast & Furious 6](https://www.imdb.com/title/tt1905041) | tt1905041 |
| [Furious 7](https://www.imdb.com/title/tt2820852) | tt2820852 |
| [The Fate of the Furious](https://www.imdb.com/title/tt4630562) | tt4630562 |

## OMDb APIs

To fetch details about a movie, we use the [Open Movie Database API](http://www.omdbapi.com/), which is a RESTful web service to obtain movie information
