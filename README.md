## Social Media Application


User Credentials for Testing

To test the application, you can use the following sample user accounts:

Regular User Accounts:

- Username: tutul1Password: 143143aa

- Username: tutul2Password: 143143aa

Setup and Installation Instructions

Follow these steps to set up and run the application on local system:

### 1. Install Pipenv (if not installed)

pip install pipenv

### 2. Activate Pipenv Shell

pipenv shell

### 3. Install Django

pip install django

### 4. Apply Migrations

python manage.py migrate

### 5. Run the Development Server

python manage.py runserver

Once the server is running, open your browser and visit:

http://127.0.0.1:8000/

This will direct you to the homepage of the application.

Summary of Implemented Features

This social media application includes the following features:

- Homepage: Displays all posts created by users.

- Category Filter: Users can filter posts based on selected categories.

### User Authentication:

- Registration

- Login

- Logout

### Post Management:

- Create new posts

- Update existing posts

- Delete posts

User-Specific Posts: Users can view posts created by themselves separately.

### ER Diagram

The Entity Relationship Diagram (ERD) for the database structure is available in the repository.

### File Name: erd.jpg

