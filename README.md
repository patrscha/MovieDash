# MovieDash
Dashboard for local movie files

DESCRIPTION
------------
A dashboard that shows all movies from a directory on a nice tiled screen (like netflix for the movies you own).
The main service scans the directory and adds any new movies to database.
All movies must be in their own directory where dir name = movie title (movie file will be renamed)

DATABASE
-----------
MOVIE:
-ID
-Title
-Year
-Description (from IMDB)
-IMDB Rating
----------

FEATURES
------------
-Search via title
-filter by genre
-get cover photo when missing
-select movie --> info page with rating, description, other IMDB info --> PLAY  --> Open in VLC (if it's possible to force)
