

# Student Management System

This project is a Student Management System that allows performing CRUD (Create, Read, Update, Delete) operations on student records. It is built using Flask for the backend, MongoDB for the database, Angular for the frontend, and Git for version control.

## Features

- **Create:** Add new student records to the database.
- **Read:** View existing student records with pagination support.
- **Update:** Update details of existing student records.
- **Delete:** Remove student records from the database.

## Technologies Used

- **Backend:** Flask, Python
- **Database:** MongoDB
- **Frontend:** Angular, HTML, CSS, JavaScript
- **Version Control:** Git, GitHub

## Getting Started

### Prerequisites

- Python installed on your machine
- MongoDB installed and running locally
- Git installed on your machine
- GitHub account for remote repository hosting

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/student-management-system.git
   ```

2. Install dependencies:

   ```bash
   cd student-management-system
   pip install -r requirements.txt
   ```

3. Start the Flask server:

   ```bash
   python app.py
   ```

4. Start the Angular frontend (assuming Angular CLI is installed):

   ```bash
   cd frontend
   npm install
   ng serve
   ```

5. Open your browser and navigate to `http://localhost:4200/` to access the application.

## Usage

- Use the frontend interface to perform CRUD operations on student records.
- The Flask server provides the API endpoints for interacting with the MongoDB database.

## Version Control

- Use Git for version control.
- Create new branches for features or bug fixes: `git checkout -b feature/new-feature`
- Commit changes to your branch: `git commit -am "Add new feature"`
- Push your branch to GitHub: `git push origin feature/new-feature`
- Create pull requests for code review and merging into the main branch.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

You can further customize this README to include specific Git commands or workflows relevant to your project.
