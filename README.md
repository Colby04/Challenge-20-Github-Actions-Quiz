# **Challenge-20-Github-Actions-Quiz**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Mongo](https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white)
![ReactJS](https://img.shields.io/badge/-ReactJs-61DAFB?logo=react&logoColor=white&style=for-the-badge)
![CYPRESS](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)

---

# Table of Contents

- [Project Description](#project-description)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Demonstration](#demonstration)
- [Tests](#Tests)
- [Questions](#questions)
- [License](#license)

---

## Project Description

In today's dynamic development environment, testing is not just an afterthought but a critical part of the development process that ensures applications meet user demands and perform efficiently under various conditions. Coding Quiz is an a MERN stack allows users to take a quiz of ten random questions and view their final score. This has got tests implemented using Cypress.
This project has *Github Actions* implemented, where one yml file is dedicated for testing Cypress tests and the other for deployment on Render

---

## Technologies Used

- **FrontEnd**: React.js, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose ORM
- **Tests**: Cypress, @testing-library/cypress
- **CI/CD**: Github Actions

---

## Setup and Installation

Follow these steps to get the application running on your local machine:

1. Clone the Repository

   ```bash
    git clone <repository-url>
    cd coding-quiz
   ```

2. Install Dependencies

   ```bash
   npm install
   ```

3. Access the App

   Setup the environment variables

   ```bash
    MONGO_URI=<your-mongodb-connection-string>
   ```

4. Run the application

   You need the app running and then open another terminal to run cypress and see the tests pass!

   ```bash
   npm run start:dev
   npm run cypress
   ```

---

## Tests

Component Test: Verifies the isolated behavior of React components using Cypress.

## Questions and Links 

For any questions please reach out by email, and feel free to check my github:
- Github: https://github.com/Colby04/Challenge-20-Github-Actions-Quiz.git
- Email: cjcodes2024@gmail.com
- Render: https://challenge-20-github-actions-quiz.onrender.com

 
---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).