# Expense Management System

The **Expense Management System** is a comprehensive web-based application designed to help users efficiently manage and track their expenses. The project is built using a **Streamlit frontend** and a **FastAPI backend**, ensuring a clear separation between user interface and backend logic. With features like data visualization, expense tracking, and a modular architecture, it serves as a practical tool for individuals and small businesses.

---

## Features

### 1. **Streamlit Frontend**
- Provides a user-friendly interface for interacting with the system.
- Features include:
  - Adding, editing, and deleting expense records.
  - Viewing interactive data visualizations (monthly/yearly expense summaries).
  - Exporting or analyzing data easily.

### 2. **FastAPI Backend**
- Acts as the central server handling data processing and storage.
- Features include:
  - Validating and storing expense data.
  - Efficient communication between the frontend and the database.
  - Scalability for future enhancements.

### 3. **Automated Testing**
- Comprehensive test cases for both frontend and backend.
- Ensures the system runs reliably under various scenarios.
- Testing tools like `pytest` are used for quick debugging.

---

## Project Structure

The repository is organized as follows:

- **frontend/**: Contains the Streamlit application code (user interface).
- **backend/**: Contains the FastAPI backend server code (business logic and database communication).
- **tests/**: Includes test cases for the frontend and backend components.
- **requirements.txt**: A file listing all required Python libraries.
- **README.md**: This file, providing an overview of the project and setup instructions.

---

## Getting Started

###  Clone the Repository
Run the following commands in your terminal to clone the repository and navigate into it:
```bash
git clone https://github.com/SiddhartNema/expense-management-system.git
cd expense-management-system

## Technologies Used
- Frontend: Streamlit (for building the user interface)
- Backend: FastAPI (for handling API requests and backend logic)
- Database: SQLite (or other supported databases like MySQL/PostgreSQL)
- Testing: Pytest (for writing and running automated tests)
- Server Deployment: Uvicorn (for running the FastAPI server)


### Changes/Additions:
1. **"How It Works" Section**: Explains the interaction between frontend, backend, and database.
2. **"Technologies Used"**: Lists the main tools and frameworks used in the project.
3. **"Future Enhancements"**: Highlights potential future developments.

