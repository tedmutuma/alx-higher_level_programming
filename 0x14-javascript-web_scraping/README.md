JavaScript - Web scraping
js-semistandard-style

This project contains some tasks for learning how to perform web scraping with JavaScript.

Tasks To Complete
 0. Readme
0-readme.js contains a script that reads and prints the content of a file.

Requirements:
The first argument is the file path.
The content of the file must be read in utf-8.
If an error occurred during the reading, print the error object.
 1. Write me
1-writeme.js contains a script that writes a string to a file.

Requirements:
The first argument is the file path.
The second argument is the string to write.
The content of the file must be written in utf-8.
If an error occurred during while writing, print the error object.
 2. Status code
2-statuscode.js contains a script that displays the status code of a GET request.

Requirements:
The first argument is the URL to request (GET).
The status code must be printed like this: code: <status code>.
You must use the module request.
 3. Star wars movie title
3-starwars_title.js contains a script that prints the title of a Star Wars movie where the episode number matches a given integer.

Requirements:
The first argument is the movie ID.
You must use the Star wars API with the endpoint https://swapi-api.hbtn.io/api/films/:id.
You must use the module request.
 4. Star wars Wedge Antilles
4-starwars_count.js contains a script that prints the number of movies where the character "Wedge Antilles" is present.

Requirements:
The first argument is the API URL of the Star wars API: https://swapi-api.hbtn.io/api/films/.
Wedge Antilles is character ID 18 - your script must use this ID for filtering the result of the API.
You must use the module request.
 5. Loripsum
5-request_store.js contains a script that gets the contents of a webpage and stores it in a file.

Requirements:
The first argument is the URL to request.
The second argument the file path to store the body response.
The file must be UTF-8 encoded.
You must use the module request.
 6. How many completed?
6-completed_tasks.js contains a script that computes the number of tasks completed by user id.

Requirements:
The first argument is the API URL: https://jsonplaceholder.typicode.com/todos.
Only print users with completed task.
You must use the module request.
 7. Who was playing in this movie?
100-starwars_characters.js contains a script that prints all characters of a Star Wars movie.

Requirements:
The first argument is the Movie ID - example: 3 = "Return of the Jedi".
Display one character name by line.
You must use the Star wars API.
You must use the module request.
 8. Right order
101-starwars_characters.js contains a script that prints all characters of a Star Wars movie.

Requirements:
The first argument is the Movie ID - example: 3 = "Return of the Jedi".
Display one character name by line in the same order of the list "characters" in the /films/ response.
You must use the Star wars API.
You must use the module request.
