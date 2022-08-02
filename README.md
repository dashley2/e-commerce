# E-commerce Back End

## Description
Back end code that uses Express.js API and Sequelize to interact with a MySQL database.

## Table of Contents
- [Installation](#installation)
- [Links](#links)
- [Usage](#usage)
- [License](#license)
- [How to Contribute](#how-to-contribute)
- [Questions](#questions)

## Installation
Access the GitHub repository e-commerce-back-end, to fork and clone the repository.

Install necessary dependencies using:
````````````
npm install
````````````
Before using the application, create a .env file in the root directory with the following code and user data for the values:
``````````````````````````````
DB_NAME="user's database"
DB_USER="root"
DB_PASSWORD="userpassword"
``````````````````````````````
To source the database, enter into the MySQL shell using `mysql -u root -p` and run:
```````````
source db/schema.sql
````````````
The seeds folder will contain data to populate the database. Run the database seeding using:
```````````
npm run seed
```````````
## Links
- [GitHub Repository](https://github.com/dashley2/e-commerce-back-end.git)
- [Walkthrough Video 1 - Setup ](https://drive.google.com/file/d/1dLEAtY4voJIEuvOCJ7GZrAxcjrWECjST/view)
- [Walkthrough Video 2 - Categories GET/POST/PUT/DELETE routes ](https://drive.google.com/file/d/1gKvC8ebaEgv18hJ2yplU4pO4UJJOFKl0/view)
- [Walkthrough Video 3 - Products GET/POST/PUT/DELETE routes](https://drive.google.com/file/d/1tCF57t9I5LxapUreFFu-hrYiEumi_8wP/view)
- [Walkthrough Video 4 - Tags GET/POST/PUT/DELETE routes](https://drive.google.com/file/d/1fSzMDUGq6mMsSE5D58zLaD8vxUErUG7a/view)
## Usage
Use `node server.js` in the integrated terminal to run the application.

## License
The badge at the top of the page shows that this project is licensed under MIT. The link for that license is shown below.
- [License: MIT](https://opensource.org/licenses/MIT)
## How to Contribute
Please feel free to fork and clone the repository! Push changes to your fork, and then make a pull request to add to the current repository.

## Questions
Please direct any questions to a.darrmedia@gmail.com. To see more projects, visit the link below for dashley2's respository:
- [GitHub Repository](https://github.com/dashley2)