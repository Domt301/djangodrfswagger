# DRF API Project

This is a Django Rest Framework (DRF) project named `drf_api` designed to manage and serve a simple Notes application. The project uses Docker for containerization and PostgreSQL as its database. Additionally, it integrates Swagger documentation via the `drf-yasg` library.

## Project Setup

### Prerequisites

- Docker and Docker Compose
- Git (for cloning the repository)

### Setup Instructions

1. **Clone the repository**:

2. **Build the Docker containers**:


3. **Run migrations**:
This initializes the database schema for the Notes app.


4. **Start the project**:


5. Access the project in your browser:
- API Root: [http://localhost:8000/](http://localhost:8000/)
- Admin Dashboard: [http://localhost:8000/admin/](http://localhost:8000/admin/)
- Swagger Documentation: [http://localhost:8000/swagger/](http://localhost:8000/swagger/)

## Features

- **Notes CRUD Operations**: Create, Read, Update, and Delete notes using HTTP requests.
- **Swagger Documentation**: Interactive API documentation using Swagger UI.
- **Docker Integration**: Ensures consistent environments between development and production.
- **PostgreSQL Backend**: Robust database management with PostgreSQL.

## Future Improvements

- Add user authentication and permissions.
- Implement advanced filtering and search capabilities for notes.
- Enhance the notes model with tagging or categorization features.

## Contributing

If you'd like to contribute to this project, please fork the repository, create a feature branch, and then submit a pull request.

## License

This project is licensed under the MIT License.
