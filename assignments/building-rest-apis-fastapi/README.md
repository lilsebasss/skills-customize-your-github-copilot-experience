# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI to practice routes, request handling, and simple data validation in Python.

## 📝 Tasks

### 🛠️ Create a FastAPI App

#### Description
Set up a basic FastAPI application with a home endpoint and a simple API structure.

#### Requirements
Completed program should:

- Import `FastAPI` and create an app instance.
- Add a `GET /` route that returns a welcome message.
- Run the app locally with `uvicorn` to confirm the endpoint works.

### 🛠️ Add Item Endpoints

#### Description
Create a small resource endpoint for managing items using request and response models.

#### Requirements
Completed program should:

- Define a `BaseModel` for an item with at least `name` and `price`.
- Add a `POST /items` endpoint that accepts an item and returns it.
- Add a `GET /items/{item_id}` endpoint that returns the item for a given ID.
- Use clear JSON responses and simple validation for input data.
