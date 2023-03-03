Note-taking App
This is a simple note-taking application that allows users to create, save, and delete notes. The application uses Express.js on the back-end to save and retrieve note data from a JSON file, and a simple HTML/JS/CSS front-end to display and interact with the notes.

Getting Started
To run the application, follow these steps:

Clone the repository to your local machine.
Install the dependencies by running npm install in the project directory.
Start the server by running npm start.

Usage
The application allows users to create, save, and delete notes. To create a new note, click the "New Note" button in the top-right corner of the screen. This will open a new note editor where you can enter a title and content for the note. To save the note, click the "Save" button. To delete a note, click the trash icon next to the note title in the note list.

API Endpoints
The back-end of the application provides the following API endpoints:

GET /api/notes: Retrieves all notes from the server.
POST /api/notes: Saves a new note to the server.
DELETE /api/notes/:id: Deletes a note with the specified ID from the server.
Technologies Used
Express.js
Node.js
HTML
CSS
JavaScript


