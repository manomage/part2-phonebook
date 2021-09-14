# phonebook
A simple Phonebook application  users have the possibility to a add, update & delete a person as well as its phone number.  Person's names are unique, which means that users cannot add names that already exist in the phonebook. A search field is also available in the app to filter the people by their name.

This initial state of the application is stored in a file db.json, which correspond to a list of users along with their numbers. This file is used by the tool JSON Server that acts as a backend server where the data are stored.

# Start the application

To start an application, do the following :

# Install dependencies
$ npm install
# Start the JSON Server
$ npx json-server --port 3001 --watch db.json
# On another terminal, start the application
$ npm start
You can then access the app on : http://localhost:3000

You can also see the content of the JSON Server by heading to http://localhost:3001/persons
