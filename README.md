# Todo App

The Todo App is a simple Flask-based web application for managing your to-do list. This application allows you to add, update, mark as completed, and delete tasks from your to-do list.

## Features

- Task Management: Easily add tasks with titles and descriptions, update them, mark them as completed, and delete tasks when needed.
- Database Storage: Utilizes an SQLite database to store and manage tasks, ensuring data persistence.

## Usage

1. Ensure you have Python and Flask installed on your system.
2. Clone or download the repository from GitHub: https://github.com/Vipul-Pinto/Todo_App
3. Navigate to the project directory in your terminal.
4. Install the required packages by running the following command:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the Flask app by executing the following command:
   ```bash
   python app.py
   ```
6. Open your web browser and go to http://127.0.0.1:5000/ to access the Todo App.
7. Use the web interface to manage your tasks:
   - Add new tasks by entering a title and description and clicking the "Add Task" button.
   - Update tasks by clicking the "Edit" button, modifying the title and description, and saving the changes.
   - Mark tasks as completed by clicking the "Complete" button.
   - Delete tasks by clicking the "Delete" button.

## Folder Structure

- app.py: The Flask application script containing the main logic and routes.
- templates/: Directory containing the HTML templates.
  - base.html: The base HTML template used for layout and inheritance.
  - index.html: The main HTML template for displaying tasks and managing them.
  - update.html: The HTML template for updating a task.
- todo.db: SQLite database file storing task information.
- requirements.txt: List of required Python packages.

## Technologies Used

- Python: Back-end scripting language used for building the Flask application.
- Flask: Web framework used for creating the web application.
- SQLite: Database system used for storing and managing task data.

## Credits

This web application was created by Vipul Joseph Pinto. Feel free to modify, customize, and enhance the code to suit your needs.
