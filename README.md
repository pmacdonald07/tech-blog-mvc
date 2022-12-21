# Tech-Blog-MVC
  
  This application is live here:

## Description
This is a full-stack application that serves as a blog-style website where users can post an comment on other user's posts. Tech Blog follows the MVC paradigm (Model, View, Controller), uses Handlebars as the templating language for server-side rendering, and uses Sequelize as the ORM.
  ## Table of Contents
  [Installation](#installation)

  [Usage](#usage)

  [Functionality](#functionality)

  [License](#license)

  [Contributing](#contributing)

  [Tests](#tests)
  
  [Questions](#questions)

  ## Instillation
  If a user wanted to install the dependencies required for this application, they would first need to clone the GitHub repository. Then, they would need to run the command "npm install" at the root directory of the application. The dependecies that are required for this application are: Bcrypt, Connect-Session-Sequelize, Dotenv, Express, Express-Handlebars, Express-Session, MySQL2, and Sequelize.

  ## Usage
  The primary function of this application is to be a blog-style website for users to share tech related news and opinions. Fellow developers could use this application as an example of a full-stack web app.

  ## Functionality
  This application uses a MySQL database, created with MySQL2 and Sequelize. When users sign up, bcrypt hashes their passwords. Express-Session stores the session data on the client in a cookie and provides authentication. The app uses Handlebars for templating, and conditionally renders nav links based on whether or not a user is logged in, along with users' posts if they have any.
  The app handles users' posts (created, editing, and deleting), and comments with API routes.
  The homepage displays all posts:
  ![tech-blog-homepage](https://user-images.githubusercontent.com/108894754/209006128-3d05cf26-4cc6-49f5-bd16-71a37306d84e.png)

  A user's dashboard gives them the option to create new posts and shows their existing posts:
  ![tech-blog-dashboard](https://user-images.githubusercontent.com/108894754/209006265-2e3391bf-50c8-4fe8-9eef-6f766daa5541.png)

  When a user clicks on the title of another user's posts, they are taken to that post and given the option to comment on it:
  ![tech-blog-posts](https://user-images.githubusercontent.com/108894754/209006455-cdfc6613-23ca-46e0-883d-831bdde3c417.png)

  ## License
  There are no licenses associated with this project.

  ## Contributing
  Guidelines for contributing to this project:
  There are currently no guidelines for contributing to this project.

  ## Tests
  There are currently no tests for this application.

  ## Questions
  If you have any questions about the project, please reach out via the following:

  [Github Profile](https://github.com/pmacdonald07)

  patrickmacdonald07@gmail.com
