# Bobu Chatbot - MERN Stack
This repository contains my solution for the challenge of creating a chatbot using the MERN stack and integrating with the OpenAI API.

## Features
 - User registration and login functionality.
 - Homepage where users can interact with the Bobu chatbot.
 - Clean code implementation following best practices.


## Installation
To run this project, please follow these steps:

1. Clone the repository to your local machine.
2. In order to run the application successfully, make sure you have a .env file in both backend and frontend folder with the configuration like this(For '', fill in appropriate content. Specific content is not provided here for security reasons):
``` plaintext
API_KEY='chatGPT API key'
DB_USER='database username'
DB_PASS='database password'
JWT_SECRET='jwt secrter'
```
3. Navigate to the chatbot-frontend directory and run the following command in your terminal to install dependencies:
```bash
cd chatbot-frontend
```
```bash
npm install
```
4. After the installation is complete, start the development server by running the command:
```bash
npm run dev
```
5. Open a separate terminal window, navigate to the chatbot-backend directory, and run the following command to install dependencies:
```bash
cd chatbot-backend
```
```bash
npm install
```
6. Once the installation is finished, start the backend server by running the command:
```bash
npm start
```
7. After both frontend and backend servers are up and running, access the URL shown in the frontend terminal to use the application.

## Frontend Dependencies
The following dependencies were used in the frontend:
- React

## Backend Dependencies
The following dependencies were used in the backend:
- Express
- Node.js
- MongoDB

## API
This project consists of a custom API and integration with the OpenAI API.
1. The Custom API is mainly used for logging in, registering, storing user information, and storing information about chat recipients. It provides the following functions:
- User Registration
- User Login
- Storing user information
- Storing chat object information
2. The OpenAI API is used to generate images and dialogues.
3. Make sure you have obtained an OpenAI API key (but don't worry, in this project we have already set up the key and don't need to do anything with it). 
- Visit the official OpenAI API website, link: https://platform.openai.com/docs/overview
- Register for an account and follow the instructions to obtain an API key.
4. To ensure that the OpenAI API would meet our needs, we customised a specific template in advance. This tailored template goes a long way to ensuring that the content generated meets our expectations as well as being more contextual, providing a more personalised and effective service to our users.


## Testing
For testing purposes, you can use the following credentials to register in the backend:

- Email: bao@123.com
- Password: bao

This application includes some frontend test files, primarily based on the Jest and Babel environment to complete the testing. To run the test files, please navigate to the frontend folder using the following statement:
```bash
cd chatbot-frontend
```

Once successfully navigated, input the following statement in the console to download dependencies:
```bash
npm install --save-dev jest jsdom babel-jest @babel/core @babel/preset-env typescript ts-jest
```

After all dependencies are downloaded, input the following command to run the test files:
```bash
npm test
```

## Deployment
The deployment of this application is separated into frontend and backend. The frontend deployment relies on Netlify, while the backend deployment relies on Heroku. The database is hosted on MongoDB Atlas. You can access the deployed software and test its functionality through the following links

```bash
https://mellow-monkeys.netlify.app/
```
## Project Management and Documentation with Notion 
Notion serves as our central hub for both task management and project documentation. It provides a collaborative environment where team members can efficiently create and assign tasks, set deadlines, and track progress throughout the project lifecycle. Additionally, Notion allows for the organization and sharing of a wide range of documents, including meeting minutes, design specifications, technical documentation, and user guides. As a versatile platform, it ensures that all essential project information and tasks are easily accessible and well-managed, facilitating communication among team members.
```bash
https://www.notion.so/8b6660ce81b245d9821524f6da1ac444?v=221ddcc5d9ee4405a77a14c518783d0f
```
## UI design with Figma
During the initial stages of the project, we leveraged Figma to conceptualize and design the user interface and user experience. Figma's cloud-based platform supports real-time collaboration, enabling multiple team members to simultaneously work on designs and provide immediate feedback in a visually engaging environment.
```bash
https://www.figma.com/file/1DOO2SUwypMP8JaEsYBsVp/Chatboat-(Community)?type=design&node-id=0-1&mode=design&t=zJFRnFMNk78Dok8S-0
```
## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.

Feel free to reach out to me if you have any questions or need further assistance. Happy coding!
