# E-commerce Back End

## Description

This project involves building the back end for an e-commerce site using Express.js and Sequelize to interact with a PostgreSQL database. The application provides a functional API for managing categories, products, and tags, meeting the latest industry standards.

## User Story

As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies so that my company can compete with other e-commerce companies.

## Acceptance Criteria

- **Database Connection**: The application connects to a PostgreSQL database using Sequelize with credentials specified in an environment variable file.
- **Database Schema and Seeding**: Schema and seed commands create and populate a development database with test data.
- **Server Initialization**: The server starts with Sequelize models synced to the PostgreSQL database.
- **API Routes**:
  - **GET Routes**: Retrieve categories, products, and tags, displaying data in formatted JSON.
  - **POST, PUT, DELETE Routes**: Create, update, and delete data in the database successfully.


## Usage

1. **Start the Server**:
   ```sh
   npm start
   ```

2. **Test API Routes**:
   - Use tools like Insomnia Core or Postman to test the API routes.
   - Example endpoints:
     - GET /api/categories
     - GET /api/products
     - GET /api/tags
     - POST /api/categories
     - PUT /api/products/:id
     - DELETE /api/tags/:id

## Walkthrough Video

For a detailed walkthrough of the project's functionality, watch the [walkthrough video](<https://drive.google.com/file/d/1oE3xIB8I8fUrFFZuVAN2IVBp0jLibmB6/view>).

## GitHub Repository

https://github.com/RinjeeG/E-commerce-Backend.git

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

