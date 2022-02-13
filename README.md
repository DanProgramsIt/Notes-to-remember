# Notes-to-remember

Hello and welcome to Notes-to-remember

## Description

This application helps the user remember things by writing notes. you can also save and delete the notes. It uses an Express backend to save and retrive note data from a JSON file.


### API Routes

* GET /api/notes - Reads the db.json file and returns all saved notes as JSON.

* POST /api/notes - Receives a new note to save on the request body then adds it to the db.json file, and then returns the new note to the client.

* DELETE /api/notes/:id - Receives a query parameter containing the id of a note to delete, removes the note with the given id property, and then rewrites the notes to the db.json file.


## Table of Contents

* [Description](#description)
* [Deployed Link](#deployed-link)
* [Screenshots](#screenshots)
* [Installation](#installation)
* [Usage](#usage)
* [Questions](#questions)


## Deployed Link

Please visit my Heroku for the app at:  [Notes to remember](https://notestoremember.herokuapp.com/)


## Screenshots

View a demonstration of the application: [video](https://drive.google.com/file/d/14d_uskaSrLH1HjBIBS6yPgbl8re0DF-p/view)
![Notes to remember pic 2](/public/assets/images/Note%20taker%20begining.jpg)

![Notes to remember pic](/public/assets/images/Notes%20saved.jpg)



## Installation

To install dependencies, run the following:

`
npm i
`

## Usage

After downloading the files and installing dependencies, run 

`
node server.js
`

## Questions

For any questions about this repo, Please contact me at [soliddan211@gmail.com](mailto:soliddan211@gmail.com). View more of my work in GitHub at [Daniel Mendez](https://github.com/DanProgramsIt) 
