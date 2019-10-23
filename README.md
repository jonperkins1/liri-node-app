# liri-node-app

What the project does
Why the project is useful
How users can get started with the project
Where users can get help with your project
Who maintains and contributes to the project

## liri-node-app

# Introduction

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters and gives you back data.

# Setup

1. Run npm install, and the following packages should be installed:

Node-Spotify-API

# LIRI functions:

-   concert-this

-   spotify-this-song

-   movie-this

-   do-what-it-says

# Commands:

-   node liri.js concert-this 'concert or band name'

This will show the following information about each event to your terminal/bash window:

Name of the Venue

Location of the Venue

Date of the Event

-   node liri spotify-this-song 'song name'

This will show the following about the song in your terminal/bash window:

Artist(s)

Song Name

Album of the Song

Song Preview Link

-   node liri.js omdb 'movie name'

This will output the following information to your terminal/bash window:

Title of the Movie

Year the Movie was Released

The IMDB Rating

Country the Movie was made in

Language the Movie is in

Plot of the Movie

Actors in the Movie

The Rotten Tomatoes Rating

-   node liri.js do-what-it-says

The program will take the text inside of random.txt and use it to call the first command with the second part as it's parameter

Currently in random.txt, the following text is there:

spotify-this-song,"I Want it That Way"

This would call the spotify-this-song function and pass in "I Want it That Way" as the song.
