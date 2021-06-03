Simple Api call for movie info

1. clone repo
   2.run `npm i`
2. generate api key from omdbapi.com and set it in apiKey.js module
3. run `npm start`
   5.format body as json
   `{ "result": { "parameters": { "movie": "Movie Title" } } }`
4. make post request to `http://localhost:8000/get-movie-details`
