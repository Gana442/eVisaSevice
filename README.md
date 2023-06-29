# eVisa Service

The eVisa Service is a web-based project that utilizes the MERN (MongoDB, Express.js, React.js, Node.js) stack for development. It provides a platform for managing and processing electronic visa applications. The project consists of three main modules: Admin, HR Executive, and User/Applicant.

## Features

- **Admin Module**
  - Manage system settings and configurations.
  - View and manage user accounts and roles.
  - Generate reports and analytics on visa application data.

- **HR Executive Module**
  - Process and review visa applications submitted by users/applicants.
  - Approve or reject visa applications based on defined criteria.
  - Communicate with applicants and request additional documentation if required.

- **User/Applicant Module**
  - Create an account and submit visa applications.
  - Track the status of submitted applications.
  - Receive notifications and updates regarding application progress.

## Prerequisites

Before running the eVisa Service, ensure that you have the following prerequisites installed:

- Node.js and npm (Node Package Manager)
- MongoDB database server

## Installation and Setup

Follow these steps to set up and run the eVisa Service:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd eVisa-Service
   ```

3. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

4. Configure backend settings:
   - Create a `.env` file in the backend directory.
   - Set up environment variables for database connection, server port, etc. Refer to the provided `env.example` file for necessary variables.

5. Start the backend server:
   ```
   npm start
   ```

6. Install frontend dependencies:
   ```
   cd ../frontend
   npm install
   ```

7. Configure frontend settings:
   - Create a `.env` file in the frontend directory.
   - Set up environment variables for backend API URL, etc. Refer to the provided `env.example` file for necessary variables.

8. Start the frontend development server:
   ```
   npm start
   ```

9. Access the eVisa Service in your browser at the specified URL (default is `http://localhost:3000`).

## Folder Structure

The project's folder structure is as follows:

- `backend/`: Contains the server-side code, including routes, controllers, and models.
- `frontend/`: Contains the client-side code, including React components and styles.
- `public/`: Holds static files that are served publicly.
- `config/`: Includes configuration files for the backend.
- `utils/`: Contains utility functions and modules.

## Testing

Testing modules can be found in the `backend/tests/` directory. To run the tests, use the following command from the backend directory:

```
npm test
```

Customize the tests as per your project requirements.

## Contributing

Contributions to the eVisa Service project are welcome. If you want to contribute, please follow the guidelines and best practices defined in the repository. Create an issue or contact the project maintainers for major changes or additions.

## License

Include the license information and any relevant details regarding the licensing of the project.

## Additional Information

Feel free to include any additional information, instructions, or details that are specific to your eVisa Service project and would be helpful for other developers working with the code.