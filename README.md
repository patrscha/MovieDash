# MovieDash
Dashboard for local movie files

DESCRIPTION
------------
A dashboard that shows all movies from a directory on a nice tiled screen (like netflix for the movies you own).
The main service scans the directory and adds any new movies to database.
All movies must be in their own directory where dir name = movie title (movie file will be renamed)

DATABASE
------------
-ID<br>
-Title<br>
-Year<br>
-Description (from IMDB)<br>
-IMDB Rating<br>
-cover path<br>
-sub path<br>

FEATURES
------------
-Search via title
-filter by genre
-get cover photo when missing
-select movie --> info page with rating, description, other IMDB info --> PLAY  --> Open in VLC (if it's possible to force)
-Enable/Disable subtitles when avaialiale

USAGE
------------
1)First open will ask for directory where movies are stored (this can always be changed in settings)
2)Service scans all subdirectories and all with video files are added to DB
3)Main dashboard is presented showing all movies with cover and title arranged to screen responsive grid
4)???
