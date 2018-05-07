# PopularMoviesPro
PopularMoviesPro is the second part of an app built for the Udacity Android Development Nanodegree.

Instructions to set the API key for The Movie Database (TMDb) follow.

Edit the file app/src/main/java/com/paschburg/rich/popularmoviespro/TMDbKey.java.
Replace "PLACE API KEY HERE" with the actual TMDb API key.

Note: from the project root directory do the command:

    git update-index --assume-unchanged app/src/main/java/com/paschburg/rich/popularmoviespro/TMDbKey.java

Then if you insert the API key within the file, the changed file with the TMDb API key will
not be synced to the public repository.

As an additional precaution, you can add the line

    TMDbKey.java

to the .gitignore file after you set the TMDb API key string.

The TMDb API key was not committed to this repository.