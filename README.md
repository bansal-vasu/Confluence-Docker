# Project Title: Pet Clinic Dockerized Application

This project is based on the work of 'feelgood1987' and 'dsyer', created in collaboration with the Spring Boot Community and hosted in the repository [spring-projects/spring-petclinic](https://github.com/spring-projects/spring-petclinic). Full credit goes to the original creators and contributors for their efforts in developing and maintaining this exemplary application.

**INTRODUCTION**
This project involves creating a fully functional Pet Clinic application, packaged and deployed using Docker. The Pet Clinic application serves as a robust management tool for pet owners, veterinarians, and clinic administrators, enabling seamless operations and efficient management of pet-related information. The application is designed with user-friendly features that enhance the user experience, coupled with a dynamic in-memory database for data storage and retrieval.

**Application Features:**

 - **Add Pets:** Users can add pet profiles, including details such as name, species, and other attributes.
 - **Add Owners:** A feature to register and manage pet owner information.
- **Find Owners:** Search functionality to retrieve owner details efficiently.
- **Find Veterinarians:** Users can access a list of veterinarians registered in the system.
 - **Exception Handling:** Robust error-handling mechanisms ensure the system operates smoothly under various scenarios.
   
**Database Configuration:**

 - **In-Memory Database:** The application uses the H2 database in its default configuration, populated with sample data at startup.
 - **Database Console:** Accessible via http://localhost:8080/h2-console, allowing users to interact with the database directly.
 - **Dynamic Connection URL:** The database connection URL (jdbc:h2:mem:<uuid>) is generated at runtime and logged to the console for convenience.

**Docker Capabilities:**

 - **Isolation:** The application is containerized to ensure isolation from the host environment and other applications.
 - **Portability:** The Docker container allows the application to run consistently across various environments without compatibility issues.
 - **Ease of Deployment:** All dependencies, configurations, and runtime environments are packaged into a single Docker image for streamlined deployment.
 - **Scalability:** The Dockerized setup can be scaled horizontally, allowing multiple instances of the Pet Clinic to be deployed.
 - **Simplified Management:** Using Docker Compose or other orchestration tools, the application can be integrated with additional services or databases.

This project demonstrates the potential of combining Docker's capabilities with an interactive web application, showcasing expertise in both application development and containerization.

**Prerequisites:**
**Docker:** Make sure Docker is installed on your system. [Docker Installation Guide](https://docs.docker.com/get-docker/)  

**Steps to Set-Up this Docker:**







