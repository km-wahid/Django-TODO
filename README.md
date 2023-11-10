# Django Todo Application

This is a simple Todo application built with Django. It allows users to create, update, and delete tasks.

## Features

- Create new tasks with a title and optional description.
- Mark tasks as completed or uncompleted.
- Edit existing tasks.
- Delete tasks.
- Responsive design for a seamless experience on different devices.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/km-wahid/django-todo.git
    ```

2. Navigate to the project directory:

    ```bash
    cd django-todo
    ```

3. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply the database migrations:

    ```bash
    python3 manage.py migrate
    ```

5. Create a superuser account:

    ```bash
    python3 manage.py createsuperuser
    ```

6. Start the development server:

    ```bash
    python3 manage.py runserver
    ```

7. Open your browser and go to [http://localhost:8000](http://localhost:8000) to access the application.

## Usage

1. Log in using the superuser account created during installation.

2. Navigate to the "Tasks" section to manage your tasks.

3. Use the "Add Task" button to create new tasks.

4. Edit or delete tasks as needed.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch:

    ```bash
    git checkout -b feature/new-feature
    ```

3. Make your changes and commit them:

    ```bash
    git commit -m 'Add new feature'
    ```

4. Push to the branch:

    ```bash
    git push origin feature/new-feature
    ```

5. Open a pull request on GitHub.

