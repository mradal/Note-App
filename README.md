# Notes App

A simple note-taking application with a back end built in Node.js and Express.js, and a front end using HTML and JavaScript.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Notes App is a web-based application that allows users to create, view, and delete notes. It provides a simple and intuitive interface for managing your notes.

## Features

- Create new notes with a title and text content.
- View a list of existing notes.
- Delete notes that are no longer needed.

## Getting Started

To get started with the Notes App locally, follow these steps:

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies: `npm install`.
4. Set up the database: Create a `db.json` file in the project root.
5. Run the server: `node server.js`.

## Usage

1. Open your web browser and go to `http://localhost:3000/` to access the landing page.
2. Click on "Get Started" to navigate to the notes page.
3. On the notes page, you can create new notes, view existing notes, and delete notes.

## API Routes

The application uses the following API routes:

- **GET /api/notes**: Retrieve all saved notes.
- **POST /api/notes**: Save a new note.
- **DELETE /api/notes/:id**: Delete a note by ID.

## Deployment

The Notes App is deployed on Heroku. Visit the live app [here](Your Heroku App URL).

## Technologies Used

- Node.js
- Express.js
- Heroku

