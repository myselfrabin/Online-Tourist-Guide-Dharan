# Online Tourist Guide Dharan - Final Year College Project

Online Tourist Guide Dharan is a web application designed as part of a final year college project. It is built using modern web development technologies and follows best practices for scalability, maintainability, and performance. The project includes both frontend and backend components, making it a full-stack application.

---

## Features

- **Frontend**:
  - Built with React and TypeScript for a robust and scalable user interface.
  - Tailwind CSS for modern and responsive styling.
  - Modular structure with reusable components.
  - Integration with `react-router-dom` for seamless navigation.

- **Backend**:
  - Node.js server with Express.js for handling API requests.
  - Database configuration for managing data (e.g., MongoDB or other DBs).
  - Middleware for authentication, error handling, and logging.
  - Utility functions for common backend operations.

- **Other Features**:
  - Environment-based configuration using `.env` files.
  - Email testing functionality for notifications.
  - AI configuration for potential integrations.

---

## Project Structure

The project is organized into the following directories:

### **Frontend (`src/`)**
- `assets/`: Contains images, icons, and other static assets.
- `components/`: Reusable React components.
- `hooks/`: Custom React hooks.
- `i18n/`: Internationalization setup for multi-language support.
- `lib/`: Utility libraries for frontend logic.
- `pages/`: Page-level components for routing.
- `styles/`: Global and shared styles.

### **Backend (`server/`)**
- `config/`: Configuration files for the app, database, and AI integrations.
- `controllers/`: Handles business logic for API endpoints.
- `middleware/`: Custom middleware for authentication, logging, etc.
- `models/`: Database models for data management.
- `utils/`: Utility functions for backend operations.

### **Public (`public/`)**
- Contains static files such as `favicon.ico`, `robots.txt`, and placeholder assets.

---

## Installation and Setup

### Prerequisites
- Node.js (v16+)
- npm or yarn
- MongoDB (if using a database)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/myselfrabin/final_year_college_project.git
   cd Online-Tourist-Guide-Dharan
