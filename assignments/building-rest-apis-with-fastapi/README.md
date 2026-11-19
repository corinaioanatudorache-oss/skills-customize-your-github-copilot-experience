# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI to manage a reading list. Practice defining request and response data, using HTTP methods and status codes, and checking API behavior with FastAPI's interactive documentation.

## 📝 Tasks

### 🛠️ Create the API and Read Books

#### Description
Create a FastAPI application for a reading list. Store books in memory while the application is running; a database is not needed.

#### Requirements
Completed program should:

- Define a book data model with an integer `id`, a `title`, an `author`, and a boolean `finished` field
- Provide `GET /books` to return all books and `GET /books/{book_id}` to return one book
- Return a `404` response when a requested book does not exist


### 🛠️ Add Book Management

#### Description
Add endpoints so a client can add books, update whether a book is finished, and remove books from the reading list.

#### Requirements
Completed program should:

- Provide `POST /books` to create a book and return the created book with a `201 Created` status
- Provide `PATCH /books/{book_id}` to update a book's `finished` value
- Provide `DELETE /books/{book_id}` to remove a book, returning `404` if it does not exist
- Use FastAPI request models to validate incoming data, and return a clear error for invalid values


### 🛠️ Run and Explore the API

#### Description
Run the application locally and use FastAPI's interactive API documentation to try each endpoint.

#### Requirements
Completed program should:

- Start with `uvicorn main:app --reload` (adjust the module name if needed)
- Open `/docs` and successfully try each endpoint, including a request for a missing book
- Confirm that created, updated, and deleted books are reflected by `GET /books`
