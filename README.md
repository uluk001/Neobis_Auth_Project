# Neobis_Auth_Project

The "Neobis_Python_Auth_Project" project is an API for user basic authentication. It provides the ability to register, log in, log out, and view the user's profile. The project is implemented using Django REST framework and libraries such as dj_rest_auth and allauth.

## Installation

1. Make sure that you have Python version 3.x and poetry installed on your computer. If not, you can download it from the official website: https://www.python.org/downloads/ and https://python-poetry.org/docs/#installation
2. Clone the repository from GitHub:

```bash
git clone https://github.com/uluk001/Neobis_Auth_Project.git
```

bash
Go to the project folder:
```bash
cd Neobis_Auth_Project
```

Install dependencies:
```bash
poetry install
```

Set up the environment variables:
```bash
cp .env.example .env
```

Perform database migrations:
```bash
python manage.py migrate
```

Start the development server:
```bash
python manage.py runserver
```

Now your project is available at http://127.0.0.1:8000/


## Using

The project provides such endpoints as register, login, etc. You can see the full list of available endpoints in the documentation. To access the documentation, you need to go to the swagger page at http://127.0.0.1:8000/swagger/


## Contribution
<br>

Pull requests: If you have a desire to fix a bug, add a new feature or improve an existing one, or you can improve the current interface, you can fork the project, make your changes in a separate branch and invite us to make a pull request with your changes. We will look at your contribution and, if everything is in order, we will add it to the main project.
<br>


## Author

[GitHub](https://github.com/uluk001)  
[LinkedIn](https://www.linkedin.com/in/ismailov-uluk-92784a233/)
