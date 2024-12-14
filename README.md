# Dunbar: Meaningful Connections

## Overview

Dunbar is an interactive full-stack web application designed to help users foster deeper and more meaningful connections with others. The platform enables users to log in, create notes, and manage their profiles while offering a sleek, responsive design. Built with modern web development technologies, Dunbar ensures a seamless and secure user experience. This version is just the MVP. We will be looking to add more featuers in the future 🚀

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Features

- **User Authentication**: Secure login and signup functionality with session management.
- **Profile Management**: Users can view and manage their profiles, including creating and deleting notes.
- **Responsive Design**: A sleek and mobile-friendly interface with a focus on simplicity and usability.
- **Dynamic Note Creation**: Users can create personalized notes to store their thoughts and ideas.
- **Seamless Navigation**: Easy transitions between login, signup, and profile pages.
- **Enhanced Security**: User passwords are hashed using bcrypt, and sensitive data is protected using environment variables.

## Technologies Used

### Back-End

- **Node.js**: A JavaScript runtime for building the server-side application.
- **Express.js**: A web framework for building RESTful APIs and handling server requests.
- **Sequelize**: An ORM (Object-Relational Mapping) tool to interact with the PostgreSQL database.
- **PostgreSQL**: A relational database for storing and managing application data.
- **dotenv**: For managing environment variables securely.
- **connect-session-sequelize**: For storing session data in the database.
- **bcrypt**: For hashing and securely storing user passwords.

### Front-End

- **HTML5**: For structuring the content with semantic elements.
- **CSS3**: For styling and layout, ensuring a responsive and visually appealing design.
- **Handlebars.js**: A templating engine used to dynamically generate HTML based on server-side data.
- **JavaScript (ES6)**: Used on the client side for interactivity and sending API requests.

### Development Tools

- **Prettier**: For consistent code formatting.
- **ESLint**: For identifying and fixing JavaScript coding issues.

## Installation

To set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/dunbar.git

   ```

2. Navigate to the project directory:

   ```bash
   cd dunbar

   ```

3. Install dependencies:

   Run the following command to install all required packages:

   ```bash
   npm install

   ```

4. Set up the database:

   - Create a `.env` file in the root directory with the following variables:

     ```env
     DB_NAME='your_database_name'
     DB_USER='your_database_user'
     DB_PASSWORD='your_database_password'
     ```

   - Run the database schema to set up the database structure:

     ```bash
     npm run db:schema
     ```

5. Start the server:

   Use the following command to start the application:

   ```bash
   npm start

   ```

6. Open your browser and navigate to:

   ```plaintext
   http://localhost:3001
   ```

## Usage

- **Sign Up**: Navigate to the signup page to create a new user account.
- **Log In**: Use your email and password to log in to your account.
- **Create Notes**: From your profile page, fill out the form to create new notes and save them.
- **View Notes**: Access and view all your saved notes on your profile page.
- **Delete Notes**: Use the delete button next to any note to remove it from your profile.

## License

This project is licensed under the MIT License. See the `LICENSE` file in the repository for more details.
