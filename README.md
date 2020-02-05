# Intro to SQL

1. Install the SQLite Browser if you haven't already [here](http://sqlitebrowser.org/)
2. Open the SQLite Browser and click 'File -> Open DataBase'
3. Choose the `chinook.db` file from this repo. This database is open source and maintained by Microsoft (SQL is no fun if you don't have any data)
4. Click the tab that says 'Execute SQL'. Type SQL queries in the box above. Press the play button. See the results of that query in the box below

# SQL (Structured Query Language)

Most applications need to store at least at little, if not a lot, of data. Storing data is also referred to as data persistence. SQL is a language that is specific to database management - you won't see it used to do anything else.

Databases store data in binary format - if you attempt to open a .db file in your text editor you get a nice message that tells you it can't be opened. We can look at the data stored in our database through the terminal, and we can execute SQL code through the terminal. We can even execute SQL code in our text editor by using the .sql extension, and executing that code against our database.

We can also use a cool GUI (Graphical User Interface) tool that helps us visualize and manipulate our database in a more user friendly way - DB Browser for SQLite.

Let's execute all of the following SQL challenges in the DB Browser.

## Challenges

1. Write the SQL to return all of the rows in the artists table

2. Write the SQL to select the artist with the name "Black Sabbath"

3. Write the SQL to create a table named 'fans' with an autoincrementing ID that's a primary key and a name field of type text

4. Write the SQL to alter the fans table to have an artist_id column type integer

5. Write the SQL to add yourself as a fan of the Black Eyed Peas? ArtistId **169**

6. Check out the [Faker gem](https://github.com/stympy/faker). `gem install faker`, open up irb, run `require 'faker'` and then generate a fake name for yourself using `Faker::Name.name`. How would you update your name in the fans table to be your new name?

7. Write the SQL to return fans that are not fans of the black eyed peas

8. Write the SQL to display an artists name next to their album title

9. Write the SQL to display artist name, album name and number of tracks on that album

10. Write the SQL to return the name of all of the artists in the 'Pop' Genre

11. I want to return the names of the artists and their number of rock tracks
    who play Rock music
    and have move than 30 tracks
    in order of the number of rock tracks that they have
    from greatest to least