# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Create a REST API for a task management system using the FastAPI framework, implementing CRUD operations for tasks with proper data validation and error handling.

## 📝 Tasks

### 🛠️ Set Up FastAPI Project Structure

#### Description
Initialize a new FastAPI project with proper directory structure and dependencies.

#### Requirements
Completed project should:

- Create a main.py file with FastAPI app instance
- Set up basic project structure with models, routes, and dependencies
- Include requirements.txt with FastAPI and uvicorn
- Create a basic root endpoint that returns API information

### 🛠️ Implement Task Data Model

#### Description
Define Pydantic models for task data with proper validation.

#### Requirements
Completed program should:

- Create Task model with id, title, description, completed status, and created_at fields
- Implement TaskCreate and TaskUpdate models for input validation
- Use appropriate data types and validation constraints
- Include example data for testing

### 🛠️ Build CRUD Endpoints

#### Description
Implement complete CRUD operations for task management.

#### Requirements
Completed program should:

- Create GET /tasks endpoint to retrieve all tasks
- Create GET /tasks/{task_id} endpoint to retrieve a specific task
- Create POST /tasks endpoint to create new tasks
- Create PUT /tasks/{task_id} endpoint to update existing tasks
- Create DELETE /tasks/{task_id} endpoint to delete tasks
- Return appropriate HTTP status codes and error responses

### 🛠️ Add Advanced Features

#### Description
Enhance the API with filtering, pagination, and documentation.

#### Requirements
Completed program should:

- Add query parameters for filtering tasks by completion status
- Implement pagination for the tasks list endpoint
- Include automatic API documentation with OpenAPI/Swagger
- Add proper error handling for invalid requests
- Include response models for consistent API responses