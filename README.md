# Coding Playground

[Frontend Repo](
    https://github.com/the-macson/playground-frontend
) | https://github.com/the-macson/playground-frontend

[Backend Repo](
    https://github.com/the-macson/playground-backend
) |  https://github.com/the-macson/playground-backend

## Description
This is a coding playground where users can solve different coding problems, write the code, and run it against specific hidden test cases.

## Features
- Users can solve different coding problems.
- Users can write code and run it against specific hidden test cases.
- Users can see the result of the code execution.
- Admins can add new coding problems.
- Admins can add new test cases for the coding problems.
- Authenticated users can submit their code.
- Authentication and authorization are handled using JWT.

## Technologies
- Next.js 
- Node.js
- Express.js
- PostgreSQL
- Docker
- Sequelize

## Challenges
- Writing the code execution engine.
- Handling the test cases.
- Managing code execution time.

## Code Execution Engine
- Created a Docker container to execute the code.
- Managed code execution time to prevent infinite loops.
- Maintained Docker to prevent memory leaks.

## On Progress
- Maintaining a queue for code execution.
- Tracking user activity.
- Tracking user code submissions.

## Future Plan
- Adding a leaderboard for users.
- Incorporating a discussion forum.
- Adding like and comment features for coding problems.
- Providing solutions for coding problems.

## Architecture
![Coding Playground](/arch.png)

<!-- add image -->
## Screenshots
![Coding Playground](/Screenshot%202024-03-07%20231247.png)
![Register](/register.png)
![Login](/login.png)