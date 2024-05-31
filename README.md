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

## Installation

1. **Clone the Repository**:
   ```sh
   git clone <starter-code-repository-url>
   cd <repository-name>
   ```

2. **Install Dependencies**:
   ```sh
   npm install
   ```

3. **Configure Environment Variables**:
   Create a `.env` file in the root directory and add your PostgreSQL database credentials:
   ```
   DB_NAME=your_database_name
   DB_USER=your_database_username
   DB_PASSWORD=your_database_password
   DB_HOST=your_database_host
   DB_PORT=your_database_port
   ```

4. **Set Up the Database**:
   ```sh
   npx sequelize-cli db:create
   npx sequelize-cli db:migrate
   npx sequelize-cli db:seed:all
   ```

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

For a detailed walkthrough of the project's functionality, watch the [walkthrough video](<link-to-video>).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This README provides a comprehensive overview of the project, including installation instructions, usage, and acceptance criteria. Ensure you replace placeholders like `<starter-code-repository-url>`, `<repository-name>`, and `<link-to-video>` with the actual values for your project.