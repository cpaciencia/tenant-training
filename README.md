# README #

# Technical Test: Movie Management System

## Objective
Develop a microservices-based system to manage information about movies and authors. The system must provide functionalities for data administration depending on the user's role.

## Project Start

### To download the entire project, use the following commands:
```bash
git clone https://github.com/cpaciencia/tenant-training.git --recursive
git submodule foreach 'git checkout main; git pull origin main'
```

### Import Database
Import [database.sql](https://github.com/cpaciencia/tenant-training/blob/main/database.sql) file to your MySQL database.

### Microservices included
The repository already includes the following microservices: `gateway`, `users`, `movies`, `authors`. Feel free to modify and create as needed to improve the architecture. You can add more microservices and more Spring Cloud functionalities. you can delete

## System Requirements
- Implement secure communication between microservices.
- Update to the latest version of Spring Boot.
- Users must provide a username and password to access the system.

Two users are already created, one with a user role and another with an admin role:
- User: `user1` with password `userAuth123456!`
- Admin: `admin1` with password `adminAuth123456!`

## APIs to Deliver
- Add movie.
- Delete a movie.
- List movies with pagination and filter by autor name

## Roles and Permissions
The system will have two main roles: **User** and **Admin**.
- **User**: Can view all information about movies and authors but cannot perform any modification actions.
- **Admin**: Has permissions to perform all available actions in the system.

## Deliverables
- Source code,in a zip file.
- postman collection to test end-points
- Additional comments.
- Instructions, if necessary.

## Evaluation
- Architectural improvements.
- Quality and clarity of the code.
- Security in authentication and management of roles and permissions.
- Correct and efficient implementation of pagination.

## Valuable
- Add Docker Compose to automatically bring up everything, including the database.

## Additional Notes
If you have any questions, please contact me at **cpaciencia@tenantevaluation.com**

We recommend using JWT tokens or similar technology for authentication to secure communications between microservices and the user interface.

Happy coding!
