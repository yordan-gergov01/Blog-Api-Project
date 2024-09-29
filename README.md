# Blog-API-Project

A simple blog site that allows users to create, update, and delete blog posts. This project demonstrates the use of Node.js, Express, EJS, Axios, and Nodemon for building a dynamic web application.

## Features

- **Add new blog posts:** Users can submit a title, author, and content to create a new post.
- **Edit existing posts:** Users can modify the title, author, and content of an existing post.
- **Delete posts:** Users can delete posts by selecting the delete option for any post.


![Blog Api - 1](https://github.com/user-attachments/assets/ecd716bc-880c-4789-805e-8b72154b2d76)
![Blog Api - 2](https://github.com/user-attachments/assets/a5faac4d-392c-4d2c-badf-894a9e3fc1ac)
![Blog Api - 3](https://github.com/user-attachments/assets/2ee76c55-ec33-431a-bd1d-9a82d216892b)


## Technologies used

- **NodeJS:** JavaScript runtime environment used for the backend server.
- **Express:** A web framework for Node.js, used for routing and handling requests.
- **EJS:** Embedded JavaScript templates for rendering dynamic HTML content.
- **Axios:** A promise-based HTTP client used to handle requests to the API.
- **Nodemon:** A development tool that automatically restarts the server when file changes are detected.

## Installation

1. Clone the repository:
   git clone https://github.com/yordan-gergov01/Blog-Api-Project.git

2. Navigate to the project directory
3. Install dependencies:
   npm install

## API Endpoints

- GET **/posts:** Retrieve all blog posts.
- GET **/posts/:id:** Retrieve a specific post by ID.
- POST **/posts:** Create a new post.
- PATCH **/posts/:id:** Update an existing post by ID.
- DELETE **/posts/:id:** Delete a post by ID.

## How it works:

- **Frontend Interaction:** Users interact with a dynamic frontend built with EJS templates. Axios is used for making API requests.
- **Backend Processing:** The backend, built with Node.js and Express, handles requests and communicates with the in-memory database of blog posts.
- **Development with Nodemon:** The application is run with Nodemon, ensuring automatic server restarts upon file changes.
