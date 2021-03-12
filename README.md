# GuestBook

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

> This is part of Academy's [technical curriculum for **The Mark**](https://github.com/WeAreAcademy/curriculum-mark). All parts of that curriculum, including this project, are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

# What's this?

This is starting code for a guestbook API, inspired by a similar one in the [http conventions](https://github.com/WeAreAcademy/mark-nodejs-proj--http-conventions) project.

It is not currently working, as it is incomplete - the database parts have been left to you.

## Setup

- Create a database called `guestbook`
- In that new database, run the commands in [db/create_tables.sql](db/create_tables.sql), to create a table.

## Tasks

Find all the lines of code that have the comment `//FIXME-TASK`

At each of these locations, write code to execute SQL commands to read from, insert, update, or delete table rows in the database, as appropriate.

## Testing

Test your server manually with Postman.

There is a Postman collection file in this repo, [here](./postman/guestbook.postman_collection.json). This can be imported into Postman to quickly give you some requests to use in testing.
