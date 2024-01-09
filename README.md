# Lab 9  

# ASP.NET Core Web API with Entity Framework Core

## Objective:
Develop a simple ASP.NET Core Web API project that uses Entity Framework Core with SQL Server. Implement a controller with CRUD actions for managing courses.

## Assignments:

### 1. Project Setup
   - Create a new ASP.NET Core Web API project.
   - Install necessary NuGet packages for Entity Framework Core and SQL Server.

### 2. Database Setup
   - Use Entity Framework Core to define a `DbContext`.
   - Create a `Course` model with the following properties:
     - `Id` (int, primary key)
     - `Name` (string)
     - `Code` (string)
     - `CreditCount` (int)

### 3. API Controller
   - Create a `CoursesController` with CRUD actions:
     - `GetCourses`: Retrieve all courses.
     - `GetCourse`: Retrieve a single course by ID.
     - `PostCourse`: Create a new course.
     - `PutCourse`: Update an existing course.
     - `DeleteCourse`: Delete a course.

### 4. Data Access
   - Implement data access logic in the controller using Entity Framework Core.
   - Ensure proper handling of asynchronous operations.

### 5. Testing
   - Test the API endpoints using a tool like Postman or Swagger.
