# Issue-tracker
The Issue Tracker is a Node.js application designed to help manage and track issues/bugs for projects. It features a clean and intuitive user interface powered by EJS templates and Bootstrap for styling. The backend is built using Express.js and MongoDB for data storage, providing a robust and scalable solution for issue tracking.

## Features
### Home Page
- Displays a list of projects.
- Button to create a new project.

### Create Project Page
- Form to create a new project with fields for:
 - Name
 - Description
 - Author

### Project Detail Page
- Shows the details of a selected project.
- Displays a list of issues/bugs related to the project.
- Provides filtering options:
   - By multiple labels.
   - By author.
   - By title and description search.
- Button to create a new issue.

### Create Issue Page
- Form to create a new issue for a project with fields for:
  - Title
  - Description
  - Labels 
  - Author

## Tech Stack
### Frontend
- EJS (Embedded JavaScript templates)
- Bootstrap (for styling)

### Backend
- Node.js
- Express.js
- MongoDB (with Mongoose for ORM)
