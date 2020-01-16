# LIRI-CLI-nodeApp

### this is a Command Line Interface (CLI) that allows the user to:
1. get song details from spotifyAPI 
2. look up movie details from omdbAPI
3. get concert venue details in the area from bandsInTownAPI *** API KEY HAS EXPIRED AND WILL NOT ALLOW ME TO GET NEW ONE

#### How to make this application run
> $ node bin/dev [command] [query]


[command] is interchanged with the following depending on what method you are calling:
* spotify-this-song
* movie-this
* concert-this
* do-what-it-says

[query] is interchanged with whatever it is you are specifically looking up
* if the item you are searching for contains more than one word, then put quotes "" on your query parameter
