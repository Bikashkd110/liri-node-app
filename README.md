LIRI-node-app
Language Interpretor and Recogonition Interface

A NPM interpretor for Spotify, Band in Town, and OMDB requests.

Installing
Once you've cloned the repository, you'll need to install the required node packages listed in packages.json. This is done with a simple npm install command.

After the packages are installed you'll be able to run 'node liri.js'

Interacting with LIRI
You may either enter in one of the commands as an argument; "concert-this", "spotify-this-song", "movie-this", or "do-what-it-says", or alternatively enter in no arguments for a interactive menu.

For "concert-this", "spotify-this-song", or "movie-this" you'll also need to enter in an artist/band, song title, or movie title to search for.

concert-this will run a search on bandsintown.com and list all the upcoming concerts, with their name, venue location, and the date's listed for the given artist/band.

spotify-this-song will search Spotify for all songs with the given title and list their artist(s), song name, album, and a link to the song preview.

movie-this will search the OMDB and give you information on the movie including it's release year, IMDB rating, country of production, language, a short plot, and the starring actors.

do-what-it-says will read a random.txt file, and run the command stored in the text file.

Built With
Javascript
Node
Dotenv
Inquirer
moment
node-spotify-api
request

Below are the screen shots of My CLI

<img width="564" alt="Screen Shot 2019-08-02 at 5 51 02 PM" src="https://user-images.githubusercontent.com/49846962/62415131-761b8300-b5ea-11e9-8f2e-891613bcf5c0.png">

<img width="565" alt="Screen Shot 2019-08-03 at 10 10 01 AM" src="https://user-images.githubusercontent.com/49846962/62415137-8df30700-b5ea-11e9-88a4-6dcf5436fcd9.png">

<img width="1041" alt="Screen Shot 2019-08-03 at 10 34 00 AM" src="https://user-images.githubusercontent.com/49846962/62415138-90edf780-b5ea-11e9-9f13-0a13952357d5.png">

<img width="1038" alt="Screen Shot 2019-08-03 at 11 19 43 AM" src="https://user-images.githubusercontent.com/49846962/62415139-93505180-b5ea-11e9-97d1-7f59b15d7862.png">

<img width="1038" alt="Screen Shot 2019-08-03 at 11 31 04 AM" src="https://user-images.githubusercontent.com/49846962/62415142-95b2ab80-b5ea-11e9-90f1-0938c6d77257.png">


