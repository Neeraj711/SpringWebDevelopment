🌐 Spring Boot Web App – User Management System
This is a simple Spring Boot web application for managing users. It demonstrates how to build a CRUD-based web app with:

Thymeleaf for frontend rendering

Form validation using Jakarta Validation

Custom validation for unique email addresses

Enum-based dropdown fields (e.g., Gender, Country)

Pagination and sorting using Pageable

PostgreSQL integration

Bootstrap for styling

✨ Features
Add users with:

Name (2–20 characters)

Valid and unique email address

Gender selection (MALE, FEMALE, OTHER)

Country selection (INDIA, USA, CANADA, UK, AUSTRALIA)

Form-level and field-level validation using annotations

Custom @UniqueEmail annotation

Paginated and sortable user list

Clean error handling with fallback page

Responsive UI with Bootstrap

🔧 Tech Stack

Technology	Description
Spring Boot	Backend framework
Thymeleaf	Templating engine for UI
PostgreSQL	Relational database
Spring Data JPA	ORM for DB operations
Hibernate	JPA provider
Bootstrap	UI styling framework
🧩 Project Structure
graphql
Copy
Edit
├── controller/        # Web controllers for handling HTTP requests
├── entity/            # JPA entities (User with enums)
├── repository/        # Spring Data JPA interfaces
├── services/          # Custom service logic (optional)
├── validation/        # Custom validators like @UniqueEmail
├── templates/         # Thymeleaf HTML templates
├── application.yml    # DB config and properties
🚀 How to Run
Clone the repository

Configure your PostgreSQL connection in application.yml

Run the application:

bash
Copy
Edit
./mvnw spring-boot:run
Open your browser and go to http://localhost:8080

📸 Screenshots
You can add screenshots of the user form and paginated list here.

📦 API Endpoints (Web UI)
/ – List all users with pagination
