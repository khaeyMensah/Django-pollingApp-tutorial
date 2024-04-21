# Django Polling App Tutorial Project
## Description
This project is based on the Django documentation tutorial for beginners, focusing on building a polling web application. It guides users through the process of setting up a Django project and creating a simple app where users can view and vote on polls.

## Features
- User authentication
- Creating, viewing, and voting on polls
- Admin interface for managing polls

## Installation
1. Clone the repository to your local machine:
```bash
git clone https://github.com/khaeyMensah/Django-pollingApp-tutorial.git
```

2. Navigate to the project directory:
```bash
cd Django-pollingApp-tutorial
```

3. Install the project dependencies:
```bash
pip install -r requirements.txt
```
4. Apply database migrations:
```bash
python manage.py migrate
```

5. Run the development server:
```bash
python manage.py runserver
```

6. Access the application at http://localhost:8000 in your web browser.

## Usage
Once the project is set up, you can:
- Create a superuser to access the admin interface:
```bash
python manage.py createsuperuser
```

- Log in to the admin interface at http://localhost:8000/admin to manage polls.
- Interact with the polling app by creating, viewing, and voting on polls.

## Contributing
Contributions to this project are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your changes.

## Credits
- Django Documentation: https://docs.djangoproject.com/en/stable/intro/tutorial01/
- Open-source contributors to Django and related libraries

<!--
License
This project is licensed under the MIT License.
-->
