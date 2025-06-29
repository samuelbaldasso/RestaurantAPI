# Backend for Restaurant Application with JWT Authentication and Authorization by Roles - Java / Spring Boot

This project is a backend for a restaurant management application. It offers features such as user authentication and authorization using JWT tokens (JSON Web Tokens) and a role system via RBAC. The backend is built in Java / Spring Boot with the MongoDB database via Docker.

## Feature Examples

- **User authentication**: User login and registration system.
- **Authorization via JWT**: After logging in, users receive a JWT token for subsequent access.
- **Restaurant Management**: Functionalities for adding, viewing, editing and deleting items / orders, as well as managing aspects associated with restaurants.

## Technologies Used

- **Java / Spring Boot**: Server execution environment.
- **MongoDB**: Efficient NoSQL database for storing user data and information on restaurants and their orders.
- **JWT (JSON Web Tokens)**: Used for authentication and authorization of users based on roles.

## API documentation

The full API documentation is available on the `/swagger-ui/index.html` endpoint. The documentation is interactive and allows you to test the endpoints directly via the Swagger interface.

## Installation and Use Instructions

1. Clone the repository: `git clone [REPOSITORY_URL]`

2. Navigate to the project folder and install the dependencies: `cd [FOLDER_NAME].

3. **Install Docker / MongoDB** (Optional):
   - Download Docker from the official website: [Download Docker - Windows, for example](https://docs.docker.com/desktop/install/windows-install/).
   - Follow the installation instructions for your operating system.
   - Create a new database in a Docker container using these commands:
   
   `docker pull mongo`
   
   `docker compose up -d`
   
5. Start the server: run the application from its main class in your preferred IDE (I recommend Intellij IDEA Community or Ultimate).

6. Go to `http://localhost:8080/swagger-ui/index.html` in your browser to view the API documentation.

---

Developed with ❤️ by Samuel Baldasso
