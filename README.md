## **Django CRUD Operation Project**
This Django project implements CRUD (Create, Read, Update, Delete) operations for an Employee Management System.

**Getting Started**
Follow these steps to set up and run the project locally:

**1. Clone Repository or Download Code**
Clone the repository or download the code from GitHub Repository Link.

**2. Install Django and Required Libraries**
Install Django and other necessary dependencies.

**3. Create Database 'EmployeeDB' on pgAdmin**
Create a PostgreSQL database named EmployeeDB using pgAdmin or another PostgreSQL management tool.

**4. Configure Database Connection**
Add the database connection details to the Settings.py file in your Django project.

### settings.py

**5. Run Migrations
Run the following commands to migrate the database:


python manage.py migrate
python manage.py sqlmigrate employee_register 0001
python manage.py migrate
**6. Run the Application
Start the Django development server by running:

python manage.py runserver
Access the application at http://127.0.0.1:8000/ in your web browser.
