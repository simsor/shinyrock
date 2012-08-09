ShinyRock
=========

A static blog generator written in Perl, using SQLite to store articles.

Usage
-----

Use the executable files in the directory to manage your blog:
* add - create a new article
* edit - modify an existing article (optionally change its title)
* delete - removes an article from the database (**WARNING**: this is not undoable! )
* list - list all the articles you wrote, and their id to modify them

Finally, you can generate your static blog by typing:
```bash
./generate
```

The result will be in output/
