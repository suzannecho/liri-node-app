# liri-node-app

In this assignment, we used Node JS to create a Liri bot. 
<br> LIRI is like iPhone's SIRI. 
<br>However, while SIRI is a Speech Interpretation and Recognition Interface, 
<br>LIRI is a Language Interpretation and Recognition Interface. 
<br>LIRI will be a command line node app that takes in parameters and gives you back data.

# Npm Packages
[Spotify](https://www.npmjs.com/package/node-spotify-api)

[Axios](https://www.npmjs.com/package/axios)

[Moment](https://www.npmjs.com/package/moment)

[DotEnv](https://www.npmjs.com/package/DotEnv)

# Commands
* concert-this

* spotify-this song

* movie-this

* do-what-it-says

# What Each Command Should Do

1. node liri.js concert-this <artist/band name here>

This will search the Bands in Town Artist Events API ("https://rest.bandsintown.com/artists/" + artist + "/events?app_id=codingbootcamp") for an artist and render the following information about each event to the terminal:

* Name of the venue
* Venue location
* Date of the Event (use moment to format this as "MM/DD/YYYY")

<div align="center">
    <img src="/images/concert-this.jpg" width="800px"</img> 
</div>

2. node liri.js spotify-this-song '<song name here>'

This will show the following information about the song in your terminal/bash window

* Artist(s)
* The song's name
* A preview link of the song from Spotify
* The album that the song is from

<div align="center">
    <img src="/images/spotify-this-song.jpg" width="800px"</img> 
</div>
If no song is provided then your program will default to "The Sign" by Ace of Base.

<div align="center">
    <img src="/images/default-spotify-this-song.jpg" width="800px" </img> 
</div>

3. node liri.js movie-this '<movie name here>'

This will output the following information to your terminal/bash window:

   * Title of the movie.
   * Year the movie came out.
   * IMDB Rating of the movie.
   * Rotten Tomatoes Rating of the movie.
   * Country where the movie was produced.
   * Language of the movie.
   * Plot of the movie.
   * Actors in the movie.
<div align="center">
    <img src="/images/movie-this.jpg" width="800px" height="300px"</img> 
</div>

If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'
<div align="center">
    <img src="/images/default-movie-this.jpg" width="800px" height="300px"</img> 
</div>

4. node liri.js do-what-it-says

<div align="center">
    <img src="/images/do-what-it-says.jpg" width="800px"</img> 
</div>

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

It should run spotify-this-song for "I Want it That Way," as follows the text in random.txt.
Edit the text in random.txt to test out the feature for movie-this and concert-this.


# Author
* Suzanne Cho
