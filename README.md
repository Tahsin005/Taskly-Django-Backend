
# Taskly Backend API


Taskly is a task management application where users can create accounts, log in, and manage their tasks. The backend is built using Django REST Framework (DRF) and PostgreSQL for the database. This RESTful API provides endpoints for user authentication, task creation, and management, ensuring secure and efficient data handling.
## Features

- **User Authentication:** Secure user authentication using Django's token-based authentication for accessing API endpoints.
- **Task Management:** Create, update, and delete tasks. Fetch all tasks for the authenticated user.
- **Database:** PostgreSQL is used for storing user and task information. Each user has a separate set of tasks, ensuring privacy and isolation.

## Getting Started

1. Clone Repository: Clone this repository to your local machine using git clone https://github.com/Tahsin005/Taskly-Django-Backend

2. Install Dependencies: Navigate to the project directory and install the required dependencies using pip install -r requirements.txt.

3. Database Setup: Configure your database settings in the settings.py file. By default, the project is configured to use PostgreSQL, but you can change it to use SQLite or MySQL as per your preference.

4. Migrations: Run database migrations to create the necessary database schema using python manage.py migrate.

5. Create Superuser: Create a superuser account to access the Django admin panel and manage users and product listings using python manage.py createsuperuser.

6. Run Server: Start the Django development server using python manage.py runserver.

7. Explore API Endpoints: Explore the available API endpoints by navigating to http://127.0.0.1:8000/ in your web browser or API client.
## Technology used



**Backend:** Django REST API, PostgreSQL



## Live Link

[Live Link](https://taskly-blue.vercel.app/)


