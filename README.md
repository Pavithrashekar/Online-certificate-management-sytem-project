# **Online Certificate Management System**

Overview:

The Online Certificate Management System is a secure web-based portal designed to streamline the management of student credentials and certificates for organizations. The system emphasizes robust security and efficient handling of data, catering to both administrative and student needs.

Key Features:

- Admin Capabilities:

    - Single Admin Account: The system supports one administrative account per organization, ensuring centralized control.

    * User Credential Management: Admins can manually create and manage student accounts, including setting up usernames and passwords.

    + Certificate Authorization: Admins can review and approve or reject student certificate requests, maintaining control over the 
      certification process.

    - User and Certificate Overview: Admins can view and manage the list of all students and their certificate statuses.

- Student/User Capabilities:
  
    - Self-Service Features: Students can change or recover their passwords through a self-service process.

    - Certificate Application: Students can apply for course completion certificates by filling out an application form.

    - Certificate Access: Once a certificate is authorized, students can view and download it. Until authorization, certificates are not 
      accessible.

 - Technologies Used:

- Frontend:

     - React: A JavaScript library used to build the user interface, leveraging hooks for managing state and side effects.

     - Material-UI: Provides a suite of modern, responsive UI components such as tables, buttons, and grids to enhance user experience.

     - JavaScript ES6+: Utilizes modern JavaScript features for concise and effective code.

     - Axios: Used for making HTTP requests to interact with the backend.

     - Blob and URL APIs: Manage file downloads by creating and handling file-like objects in the browser.
     
- Backend:

    - Spring Boot: A framework that facilitates the development of backend services, including JPA for database operations, Spring 
      Security for authentication and authorization, and RESTful web services.
    
    - JWT (JSON Web Tokens): Handles secure authentication and authorization.
    
    - MySQL: The database system used for reliable data storage and retrieval.

    - Flying Saucer PDF: Generates PDF documents for certificates, enabling downloadable and printable versions.
    
    - Lombok: Reduces boilerplate code, simplifying development and enhancing productivity.

- Design Principles:

    - Object-Oriented Programming (OOP): Structuring the backend code using classes and objects for a modular and maintainable approach.
    
    - DRY Principle (Don’t Repeat Yourself): Promotes code reusability by avoiding duplication and creating reusable components.
    
    - Modular Design: Organizes code into distinct layers such as models, controllers, services, and repositories to ensure separation of 
      concerns and ease of maintenance.
 

   




