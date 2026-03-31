netstat -aon | findstr :<port># Project Setup

## Prerequisites
- Node.js and npm installed on your Windows system.

## Installation Steps
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install all dependencies.

## Running the Application
1. Start the frontend server:
   ```bash
   npm run dev
   ```
   Access the application at `http://localhost:3000/`.

2. Start the backend server:
   ```bash
   cd server
   npm start
   ```
   Ensure the backend is running at `http://localhost:3001/`.

---

# Coding Techniques and Styles

## Frontend
- **React**: Used for building dynamic and responsive user interfaces.
- **MUI**: Material-UI components for consistent design and styling.
- **React Router**: For managing navigation and routing within the application.

## Backend
- **Node.js**: Provides a scalable and efficient server-side environment.
- **Express.js**: Simplifies API creation and request handling.

## Recommended VS Code Extensions
- **ESLint**: Integrates ESLint JavaScript into VS Code.
- **Prettier**: Code formatter for consistent style.
- **Material Icon Theme**: Provides a set of icons for file and folder.
- **npm Intellisense**: Autocompletes npm modules in import statements.
- **Path Intellisense**: Autocompletes filenames.
- **CSS-in-JS**: Utilized for component-level styling with MUI's `sx` prop.
- **Responsive Design**: Ensures the application is accessible on various devices.

## File Upload
- **Drag-and-Drop**: Implemented for intuitive file uploads.
- **Validation**: Ensures only PDF files are uploaded and checks file size.

These techniques and styles were chosen to create a modern, efficient, and user-friendly application.