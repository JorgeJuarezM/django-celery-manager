# django-celery-manager

[![License](https://img.shields.io/github/license/JorgeJuarezM/django-celery-manager)](https://github.com/JorgeJuarezM/django-celery-manager/blob/master/LICENSE)
[![GitHub Issues](https://img.shields.io/github/issues/JorgeJuarezM/django-celery-manager)](https://github.com/JorgeJuarezM/django-celery-manager/issues)

This repository contains a Django application called "django-celery-manager" that provides an administration interface for the Celery asynchronous task framework.

## Functionality

The "django-celery-manager" application facilitates the management and monitoring of asynchronous tasks in Django projects using Celery as the execution engine. Some of the key features include:

- Django-based administration interface that allows viewing the status of tasks in queue, running, and completed.
- Ability to stop and restart running tasks.
- Detailed view of each task, including its status, execution time, arguments, and result.
- Grouping of tasks by type and creation date for better organization and search.
- Search and filtering interface to quickly find specific tasks.

## Requirements

Before using "django-celery-manager," make sure you have the following installed:

- Python 3.x
- Django (version X.X.X)
- Celery (version X.X.X)
- Other requirements specified in the "requirements.txt" file

## Installation

Follow these steps to install and configure "django-celery-manager" in your Django project:

1. Clone this repository to your local machine or download it as a ZIP file.
2. Navigate to the project directory in your terminal.
3. Create and activate a virtual environment (optional but recommended).
4. Install the dependencies using the following command: `pip install -r requirements.txt`.
5. Add "django_celery_manager" to the list of installed applications in your Django configuration file (`settings.py`).
6. Run Django migrations to create the necessary tables in the database: `python manage.py migrate`.
7. Configure Celery in your project following the instructions in the official Celery documentation.
8. Start the Django development server: `python manage.py runserver`.
9. Open your web browser and go to the address `http://localhost:8000/admin/celery_manager/task/` to access the "django-celery-manager" administration interface.

## Contribution

If you wish to contribute to this project, follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bug fix: `git checkout -b branch-name`.
3. Make the necessary changes and commit your modifications: `git commit -am 'Description of the changes'`.
4. Push the branch to your forked repository: `git push origin branch-name`.
5. Open a pull request in this repository, and provide a detailed description of your changes.

## License

This project is licensed under the [MIT License](https://github.com/JorgeJuarezM/django-celery-manager/blob/master/LICENSE).
