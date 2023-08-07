# TypeScript--REST-API-todoapp
This is a simple ToDo REST API built using TypeScript and Express. 
The API allows you to perform basic CRUD (Create, Read, Update, Delete) operations on ToDo items.

## Features

- Get a list of all ToDo items.
- Add a new ToDo item.
- Update an existing ToDo item.
- Delete a ToDo item.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Prerequisites

- Node.js and npm installed on your machine

### Installing

1. Clone the repository to your local machine:

`git clone https://github.com/your-username/todo-api.git`
cd todo-api

Install project dependencies:
`npm install`

Start the server:
npm start

The API will be accessible at http://localhost:3000.

### API Endpoints

- `GET /todos`: Get a list of all ToDo items.
- `POST /todos`: Add a new ToDo item.
- `PUT /todos/`:id: Update an existing ToDo item.
- `DELETE /todos/`:id: Delete a ToDo item.
