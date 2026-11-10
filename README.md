
# SimpleNotes API — Main Version

A simple REST API built with Node.js and Express.

## Requirements

- Node.js
- npm

## Installation

Clone the repository, then run:

```bash
npm install
```

## Run the application

```bash
node index.js
```

The API runs on:

http://localhost:3000

## API Endpoints

### GET /notes

Returns all notes.

### POST /notes

Creates a new note.

Example request body:

```json
{
  "text": "my first note"
}
```

Example response:

```json
{
  "id": 1,
  "text": "my first note"
}
```
