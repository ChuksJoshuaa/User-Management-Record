# User Management Record

<img src="https://res.cloudinary.com/chuksmbanaso/image/upload/v1710941085/file-uploads/a4qogthay8qlyqy0eqeo.png" title="Image" alt="image">

This project is a simple users application built with React, Typescript, Node, Express and MongoDB. It allows users to create, filter, paginate and delete users.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes..

## Prerequisites

- Node.js (version 16.20.0)
- npm (version 8.19.4)

## Demo Link

Access the live site at [Project-Link]https://expatswap-users.netlify.app)

## Technologies Used

- React.js
- Tailwind CSS
- JavaScript
- Typescript
- Node.js
- Express.js
- MongoDB

### Installation

1. Clone the repository
2. Install dependencies in both client and server directories using `npm install`
3. Start the server from the server directory with `npm start`
4. Start the client from the client directory with `npm start`

## Client

The client is built with React, Tailwindcss and TypeScript. It uses Redux Toolkit for state management and Tailwind CSS for styling.

### Directory Structure

- `src/components`: Contains all the React components.
  - `Layout.tsx`: Handles the layout of the application.
  - `Form.tsx`: Handles the creation and updating of users.
  - `HomeView.tsx`: Displays a list of users.
  - `DateFilters.tsx`: Handles the users filters.
  - `Pagination.tsx`: Handles the users pagination.
  - `HeroHeader.tsx`: Handles the users headers.
  - `Loader.tsx`: Handles the loading component.
- `src/redux`: Contains the redux functionalities for state management.
- `src/constants`: Contains the action types for the reducer.
- `src/interface`: Contains the TypeScript interfaces used in the project.
- `src/utils`: Contains utility functions, such as notifications.
- `src/pages`: Contains all the pages of the application.
- `src/interface`: Contains all the typescript props and arguments.

## Server

The server is built with MongoDB, Express and Node. It provides a REST API for managing users.

### Directory Structure

- `src/routes`: Contains the routes for the API.
- `src/controllers`: Contains the controllers for handling requests.
- `src/models`: Contains the data models.

## API Design

The API is designed to handle the following endpoints:

- `GET /api/v1/users`: Retrieve a list of all users.
- `GET Single User /api/v1/users/:id`: Retrieve a single user.
- `GET FILTERED /api/v1/users/filtered?page=1&pageSize=10&startDate=&endDate=`: Retrieve a list of all filtered users.
- `POST /api/v1/users/create`: Create a new user.
- `PATCH /api/v1/users/edit/:id`: Update a user.
- `DELETE /api/v1/users/delete/:id`: Delete a user.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.
