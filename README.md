# E-commerce API 
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
A back end E-commerce site application that utilizes an **Express.js API**, **Sequelize**, and a **PostgreSQL database**. The API works with an E-commerce database which includes a Category, Product, Tag, and Product Tag table. The API routes allow users to use the GET, GET by id, POST, PUT, and DELETE methods to retrieve and manipulate the database. 

## Table of Contents
- [Walkthrough](#walkthrough)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Walkthrough
[Click here](https://drive.google.com/file/d/1mIZZr-VXoVhR_HHWzE0q7uiPBRYnat5V/view) to watch a demonstration video of the API's functionality.

## Installation
Install dependencies:

```bash
npm install
```

## Usage
1. User will need to install all dependencies in their local environment. 
2. Change directory to 'db':
    ```bash
    cd db
    ```
3. Run 
    ```bash
    psql -U postgres 
    ```
    then run 
    ```bash 
    \i schema.sql 
    ``` 
    from the db directory. 
4. Return to the main project directory and seed the database with data by running:
    ```bash
    npm run seed
    ```
5. Then run:
    ```bash
    npm run start
    ```
6. Before running the application, make sure to change the **sequelize sync force** in the server from **true** to **false**. 
7. The API responses can be viewed by using software like **Insomia** or **Postman**.

## License
### MIT License

## Contributing
Any one can contributing or use this repository.

## Tests
No tests specified for this application.

## Questions
If you have any questions about the project, please feel free to visit my [GitHub](https://github.com/MichelleBell0) or [email me](mailto:michbesch0@outlook.com)!

