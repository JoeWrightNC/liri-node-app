# liri-node-app
Week 10 (LIRI Bot) Assignment

This app was created to fulfill the week 10 assignment in the UNC Chapel Hill Coding Bootcamp. We were challenged to create a Node.JS "LIRI" bot, like Apple's Siri, who would take in language commands via the terminal.  My version of LIRI is a command line node app that takes in various parameters and returns data when prompted with one of the following four commands:

  * `my-tweets`

  * `spotify-this-song`

  * `movie-this`

  * `do-what-it-says`

## Getting Started

- Clone this Repository.
- Run command 'npm install' in Terminal or GitBash to install the dependencies given in package.json
- Run command 'node liri.js' or one of the commands below.

## What Each Command Does

1. `node liri.js my-tweets`

  * Displays my last 20 tweets and when they were created in the terminal/bash window.  Enjoy the great coding humor!

2. `node liri.js spotify-this-song <song name>`

  * Shows the following information about the song in terminal/bash window.
    * Artist
    * Song Title
    * A Preview URL from Spotify
    * The Song's Album

  * Or if no song is passed through, it will default to
    * "The Sign" by Ace of Base

3. `node liri.js movie-this <movie name>`

  * Shows the following information in terminal/bash.

    * Title of the movie.
    * Year the movie came out.
    * IMDB Rating of the movie.
    * Rotten Tomatoes Rating.
    * Country where the movie was produced.
    * Language of the movie.
    * Plot of the movie.
    * Actors in the movie.

  * Or if no movie is passed through, it will default to "Mr. Nobody"

4. `node liri.js do-what-it-says`

  * Takes the text from random.txt and runs the song through spotify-this-song command

## Tech used
- Node.js
- Twitter NPM Package - https://www.npmjs.com/package/twitter
- Spotify NPM Package - https://www.npmjs.com/package/spotify
- Request NPM Package - https://www.npmjs.com/package/request
- File System NPM Package - https://www.npmjs.com/package/file-system

## Prerequisites
```
- Node.js - Download the latest version of Node https://nodejs.org/en/
```

## Author

* **Joe Wright** 