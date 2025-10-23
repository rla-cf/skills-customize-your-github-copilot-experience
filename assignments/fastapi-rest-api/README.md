# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build and deploy RESTful APIs using the FastAPI framework in Python. Students will create endpoints, handle requests, and return JSON responses.

## 📝 Tasks

### 🛠️ Create a Simple FastAPI App

#### Description
Set up a basic FastAPI application with a single endpoint that returns a welcome message.

#### Requirements
Completed program should:
- Use FastAPI to create a web server
- Define a GET endpoint `/` that returns a JSON welcome message
- Run locally and respond to requests

### 🛠️ Add CRUD Endpoints for a Resource

#### Description
Expand your FastAPI app to manage a resource (e.g., books, users, tasks) with full CRUD (Create, Read, Update, Delete) functionality.

#### Requirements
Completed program should:
- Define a resource model using Pydantic
- Implement endpoints for creating, reading, updating, and deleting resources
- Store data in-memory (list or dictionary)
- Return appropriate status codes and JSON responses

### 🛠️ API Documentation and Testing

#### Description
Explore FastAPI's automatic documentation and test your endpoints using the interactive Swagger UI.

#### Requirements
Completed program should:
- Provide OpenAPI documentation at `/docs`
- Demonstrate testing endpoints using Swagger UI
- Include instructions in README for running and testing the API
