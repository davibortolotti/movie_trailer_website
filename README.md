# Movie Trailer Website project

This is a project for Udacity "Full-stack developer" course.

In order to run it, you must clone the repo and pull it to your desktop.
Then, execute the `entertainment_center.py` file in a python shell, opening with Idle, or in a command line, by moving into the folder of the files and typing:
```
python entertainment_center.py
```

It will create a file called `fresh_tomates.html`. If you open it with your browser, you will see the result.

I added some features that were not in the project specifications, like showing the synopsis when hovering the movie poster, and changing some of the css to my liking.

For one to add other movies to the website, one must modify the `entertainment_center.py` file with the film's information, mirroring the code of those which are already put there.

E.g.:

```
dreams = media.Movie(
    # title
    "Dreams",
    # synopsis
    """A collection of tales based upon the actual dreams of director
    Akira Kurosawa.""",
    # poster img link
    "https://images-na.ssl-images-amazon.com/images/M/MV5BNDBkODdjMzEtNTY1NC0"+
    "0ZWQ5LTk3NDUtY2IwMTk5MzhmNTUwXkEyXkFqcGdeQXVyNjc1NTYyMjg@._V1_.jpg",
    # youtube link
    "https://www.youtube.com/watch?v=bPHsu5NaVfM")
movies.append(dreams)   # appends to the list
```

The website is also up and running on the internet [here](https://davibortolotti.github.io).

Thanks Udacity.
