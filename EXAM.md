
# Lab Exam: Build and Deploy a NestJS Backend with PostgreSQL Using Docker

## Objective

Your goal is to create a NestJS backend application that connects to a PostgreSQL database. The backend must be containerized using Docker, and the services managed using Docker Compose. The application should include CRUD functionality for a User entity.

## Instructions

1.	Ensure the following tools are installed:
    - Node.js and npm
	- Docker and Docker Compose
2.	Complete the tasks outlined below.
3.	Submit your solution via GitHub assignment repository link.

## Tasks

1. Initialize the Project
	- [10 points] Set up a new NestJS project using the NestJS CLI:
	- Install the CLI globally.
	- Create a new project named nestjs-docker-exam.

2. Configure PostgreSQL

	- [30 points] Set up a PostgreSQL database for the project:
	- Install and configure PostgreSQL-related dependencies.
	- Update the project configuration to use TypeORM with environment variables.
	- Create a .env file to define the database connection details.

3. Implement the User Resource

	-	[20 points] Create and implement the User resource:
	-	Generate a User entity using the CLI.
	-	The entity should have the following fields:
	-	id (Primary Key, UUID)
	-	name (String)
	-	email (String, unique)
	-	createdAt (Date)
	-	Implement CRUD endpoints for the User resource.

4. Dockerize the Application

	-	[30 points] Create a containerized environment:
	-	Write a Dockerfile to containerize the application.
	-	Configure a docker-compose.yml file to define the application and database services.

5. Verify and Test

	-	[10 points] Test the application functionality:
	-	Start the application using Docker Compose.
	-	Test the CRUD endpoints using Postman or cURL to ensure the application works as expected.

6. Bonus

	- [+5 points] Add a /health endpoint to verify database connectivity.

## Submission

1.	Push your project to a GitHub repository or compress the project folder into a .zip file.****
2.	Include a README.md file with the following details:
	- Project description.
	- Instructions for running the application.
	- Environment variables required.

## Grading Rubric

| Task                     | Points |
| ------------------------ | ------ |
| Project Initialization   | 10     |
| PostgreSQL Configuration | 30     |
| User Resource            | 20     |
| Docker Configuration     | 30     |
| Testing and Verification | 10     |
| Bonus Task               | +5     |
