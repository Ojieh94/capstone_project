# capstone_project
# Movie Listing API

## Project Overview

This capstone project is designed to develop a movie listing API using FastAPI, SQL Alchemy and Python. The API allows users to list movies, view listed movies, rate them, and add comments. The application is secured using JWT (JSON Web Tokens), ensuring that only the user who listed a movie can edit it. The application is hosted on a cloud platform.

## Features

### User Authentication:
- **User Registration**: Users can sign up to access the API.
- **User Login**: Users can log in to receive a JWT token.
- **JWT Token Generation**: Secure endpoints with JWT for authentication.

### Movie Listing:
- **View a Movie**: Public access to view movie details.
- **Add a Movie**: Authenticated users can add movies.
- **View All Movies**: Public access to view all listed movies.
- **Edit a Movie**: Only the user who listed the movie can edit it.
- **Delete a Movie**: Only the user who listed the movie can delete it.

### Movie Rating:
- **Rate a Movie**: Authenticated users can rate movies.
- **Get Ratings for a Movie**: Public access to view movie ratings.

### Comments:
- **Add a Comment to a Movie**: Authenticated users can comment on movies.
- **View Comments for a Movie**: Public access to view comments on movies.
- **Add Comment to a Comment (Nested Comments)**: Authenticated users can reply to comments.

## Requirements

- **Language & Framework**: Python using FastAPI
- **Authentication**: JWT for securing endpoints
- **Database**: Any SQL or NoSQL database of your choice
- **Testing**: Include unit tests for the API endpoints
- **Documentation**: API documentation using OpenAPI/Swagger
