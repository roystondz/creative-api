# My API

This is a RESTful API created using Node.js. It allows you to perform CRUD operations on [resource name] and is tested using Postman.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [API Endpoints](#api-endpoints)
- [Testing with Postman](#testing-with-postman)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create, Read, Update, and Delete ([CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete)) operations
- JSON response format
- Error handling
- Authentication (if applicable)

## Technologies Used

- Node.js
- Express.js
- MongoDB (or any other database you are using)
- Postman (for API testing)

## Installation

### Prerequisites

Make sure you have Node.js and npm installed. You can download them from [Node.js official website](https://nodejs.org/).

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/roystondz/creative-api.git
   cd creative-api

2. Install dependencies:
   ```bash
   npm install

3. Run:
   ```bash
   nodemon index.js

## API Endpoints

| Method | Endpoint          | Description                      |
|--------|-------------------|----------------------------------|
| GET    | `/random`   | Retrieve random resource           |
| POST   | `/jokes`   | Create a new resource            |
| GET    | `/jokes/:id` | Retrieve a resource by ID      |
| PUT    | `/jokes/:id` | Update a resource by ID        |
| DELETE | `/jokes/:id` | Delete a resource by ID        |

### Importing Postman Collection

1. Download the `postman_collection.json` from the repository.
2. Open Postman and click on `Import`.
3. Select the `postman_collection.json` file.


## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a Pull Request.


