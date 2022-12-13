# Flatdango
## Description
This JavaScript code is for a web page that displays a list of films from a REST API and allows users to purchase tickets for the films. The code first sets up a URL for the GET request to retrieve the film data from the API.

The getdata function makes a GET request to the API using the fetch function. Once the data is returned, the function extracts the relevant information from the first film in the data and calculates the number of available tickets. It then loops through the films in the data and adds a new li element to the page for each film.

The code also adds an event listener to the "Buy Ticket" button on the page to handle clicks. When a user clicks the button, the number of available tickets is checked. If there are any tickets available, the number of available tickets is decreased by 1 and a POST request is made to the API to update the number of tickets sold for the film. If there are no tickets available, an error message is displayed to the user.

Finally, the initialize function is called to start the process of making the GET request and displaying the film data on the page.
### Prerequisites
* node v14.17.4 and above
* npm 6.14.14 and above
* Vue 2.6.11
* Then install the various packages from package.json `npm install`
* Create environment variables
* Use this JSON file for the server DB https://moringa.instructure.com/courses/185/files/152618?wrap=1
```
Meta
----
Author:
   Daniel Mutie - *Initial work* - [dancunrandy](https://github.com/Dancunrandy/Wk3-code-challenge)
Status:
    maintained, and is currently in development
Version:
    v0.1.0
Usage
-----
## License
This project is licensed under the MIT License
Documentation
-------------
You can see the documentation over at **Read the Docs**
Resources
-------------