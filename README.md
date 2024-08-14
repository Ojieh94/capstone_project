# Movie Listing API

The Movie Listing API is a comprehensive platform for managing movie listings, user interactions, and ratings. It provides functionality for listing movies, viewing details, and allows users to rate and comment on movies. The API is secured with JWT authentication and deployed on Render.

## Technical Stack

- **Language**: Python
- **Framework**: FastAPI
- **Database**: PostgreSQL
- **Authentication**: JWT (JSON Web Tokens)
- **ORM**: SQLAlchemy
- **Password Hashing**: Passlib
- **Cloud Platform**: Render
- **Testing**: Pytest
- **Documentation**: OpenAPI/Swagger
- **Environment Variables**: python-dotenv


## Features

- **User Authentication:**
Secure user login and registration with JWT to ensure authorized access.
- **CRUD Operations:**
Manage movies, users, ratings, and comments with full CRUD capabilities.

- **Movie Management:**
 List, search, and view detailed information about movies.

- **Rating and Comments:**
Users can rate movies and leave comments, enhancing interaction.
- **Advanced Querying:**
Support for filtering, pagination, and searching.

- **Dependency Injection and Modularity:**
Utilizes FastAPI’s dependency injection for a modular and maintainable codebase.

- **Robust Logging and Error Handling:**
 The application employs comprehensive logging and error handling mechanisms to ensure reliable operation. Logs are managed and monitored using Better Stack.


## Use Cases:

- **Movie Listing Platforms:**  Build movie databases or discovery platforms.

- **Review Aggregators:** Aggregate and manage movie ratings and reviews.

- **Content Management Systems (CMS):** Integrate with media-related CMS platforms.

## Getting Started

### Prerequisites

Python 3.12.1
PostgreSQL


### Installation

1. **Clone the repository**:

   ```sh
   git clone https://github.com/Ojieh94/henry.git
   cd Capstone_Project
   ``` 

2. **Install the dependencies**:

    ```sh
    pip install -r requirements.txt
    ```

3. **Set up the database**: 

Create a PostgreSQL database and configure the connection in the `.env` file.
```
SQLALCHEMY_DATABASE_URL=your_database_url  # Replace with your database URL
```

4. **Start the application**:

    ```sh
    uvicorn movie_app.main:app --reload
    ```

### Running Tests

To ensure the API functions correctly, we have implemented tests using `pytest`.

1. **Install `pytest`**:

   ```sh
   pip install pytest
   ```

2. **Run the tests**:
   ```sh
   pytest
   ```


## Contributions

Feel free to contribute and make changes! Please create a pull request with a detailed description of your changes

## Contact

[henry.ojieh@gmail.com](mailto:henry.ojieh@gmail.com).
