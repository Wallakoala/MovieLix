# RapidAPI

- X-RapidAPI-Host: `unogs-unogs-v1.p.rapidapi.com`
- X-RapidAPI-Key: `392eac5962mshd6cbfe2e3d4f643p17704bjsn75e2a2d6d3ab`

## Endpoints

### Netflix

- `GET New release per country`: lista de nuevas peliculas por país (en inglés). Ej:

  ```json
  {
      "netflixid":"81140577",
      "title":"Dave Chappelle: Sticks and Stones",
      "image":"http://occ-0-3467-346...q_oP0.jpg?r=9f7",
      "synopsis":"Dave Chappelle takes on gun culture, the opioid ...",
      "rating":"",
      "type":"movie",
      "released":"2019",
      "runtime":"1h5m",
      "largeimage":"",
      "unogsdate":"2019-08-27",
      "imdbid":"",
      "download":"0",
  }
  ```

- `GET Deleted`: lista de películas descatalogadas, ej:

  ```json
  {
      "netflixid":"60029157",
      "title":"Pirates of the Caribbean: The Curse of the Black Pearl",
      "ccode":"US",
      "date":"2018-12-25 19:14:15"
  }
  ```

### IMDB

`GET by ID or Title`:

  ```json
  {
      "Title":"Avengers: Endgame"
      "Year":"2019",
      "Rated":"PG-13",
      "Released":"26 Apr 2019",
      "Runtime":"181 min",
      "Genre":"Action, Adventure, Sci-Fi",
      "Director":"Anthony Russo, Joe Russo",
      "Writer":"Christopher Markus (screenplay by), Stephen McFeely (screenplay by), Stan Lee (based on the Marvel comics by), Jack Kirby (based on the Marvel comics by), Jim Starlin (Thanos, Gamora & Drax created by), Jack Kirby (Groot created by)",
      "Actors":"Robert Downey Jr., Chris Evans, Mark Ruffalo, Chris Hemsworth",
      "Plot":"After the devastating events of Avengers: Infinity War (2018), the universe is in ruins. With the help of remaining allies, the Avengers assemble once more in order to reverse Thanos' actions and restore balance to the universe.",
      "Language":"English, Japanese, Xhosa",
      "Country":"USA",
      "Awards":"N/A",
      "Poster":"https://m.media-amazon.com/images/M/MV5BMTc5MDE2ODcwNV5BMl5BanBnXkFtZTgwMzI2NzQ2NzM@._V1_SX300.jpg",
      "Ratings":[
          ...
      ],
      "Metascore":"78",
      "imdbRating":"8.6",
      "imdbVotes":"531,604",
      "imdbID":"tt4154796",
      "Type":"movie",
      "DVD":"N/A",
      "BoxOffice":"N/A",
      "Production":"Marvel Studios",
      "Website":"N/A",
      "Response":"True",
  }
  ```
