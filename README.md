# Content Management API

This is a simple content management API built using FastAPI and SQLAlchemy. The API allows users to create, retrieve, update, and delete content items.

## Features

- **Create Content**: Add new content with a title, body, and content type.
- **Retrieve Content**: List all content items or retrieve a single item by its ID.
- **Update Content**: Modify existing content by ID.
- **Delete Content**: Remove content by ID.

## Installation

### Using Poetry

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/content-management-api.git
    cd content-management-api
    ```

2. Install dependencies:
    ```bash
    poetry install
    ```

3. Run the application:
    ```bash
    poetry run uvicorn content_management_api.main:app --reload
    ```

### Using Pip

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/content-management-api.git
    cd content-management-api
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    uvicorn content_management_api.main:app --reload
    ```

## Usage

After starting the application, you can interact with the API at `http://127.0.0.1:8000`.

### Endpoints

- **POST /content/**: Create new content.
- **GET /content/**: List all content items.
- **GET /content/{content_id}**: Retrieve a specific content item by ID.
- **PUT /content/{content_id}**: Update an existing content item by ID.
- **DELETE /content/{content_id}**: Delete a content item by ID.

You can also explore the API documentation by visiting `http://127.0.0.1:8000/docs` in your browser.

