# TechTalesBlog


Tech Tales Blog is a CMS-style blog site where developers can publish their thoughts, blog posts, and comment on other developers’ posts. This application is built following the Model-View-Controller (MVC) paradigm using Handlebars.js for templating, Sequelize as the ORM, and the express-session npm package for authentication.

## Features

This project allows users to:
- Create an account and log in
- Post blog entries
- Comment on other blog posts
- Edit and delete their own posts and comments

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

To install and run this application locally, follow these steps:

1. Clone the repository:

    git clone https://github.com/ktcv31/techtalesblog.git
    cd techtalesblog
    

2. Install the required dependencies:
    
    npm install
    

3. Set up the environment variables:

    Create a `.env` file in the root directory and add the following variables:

    DB_NAME=tech_talesblog_db
    DB_USER=your_database_user
    DB_PASSWORD=your_database_password
    DB_HOST=localhost
    DB_PORT=5432


4. Initialize the database:
    - npx sequelize db:migrate
    - npm run seed


5. Start the server:

    npm start
    

6. Open your browser and navigate to `http://localhost:3002` to view the application.

## Usage

- Upon visiting the homepage, users can view existing blog posts and comments.
- To create a post or comment, users need to sign up and log in.
- Once logged in, users can create, edit, and delete their blog posts and comments.
- The dashboard allows users to manage their posts and see comments from others.

## Screenshots


1. Homepage

    ![Homepage Screenshot](./Screenshot%202024-09-09%20at%2010.04.46 PM.png)

2. Dashboard

    ![Dashboard Screenshot](Screenshot%202024-09-09%20at%2010.05.33 PM.png/Screenshot 2024-09-09 at 10.05.33 PM.png)



## Technologies Used

- **Node.js**: JavaScript runtime environment
- **Express.js**: Web framework for Node.js
- **Sequelize**: ORM for interacting with PostgreSQL database
- **PostgreSQL**: SQL database for data storage
- **Handlebars.js**: Templating engine
- **bcrypt**: For password hashing
- **express-session**: For managing user sessions
- **dotenv**: To manage environment variables

