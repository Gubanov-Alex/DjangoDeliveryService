# CATERING API

# TECH STACK

- Python - programming language
- Django -web framework
- DRF (Django REST Framework) - data validation
- PostgreSQL - Database (RDBMS)
  - tables
- Redis/MongoDB - Key-value Storage
  - json {"any-key": value}
- Manage dependencies...

# SETUP

```shell
# activate virtual environment
pipenv shell --python python3.12
# generate `Pipfile.lock` file after adding dependencies
pipenv lock
# install dependencies form `Pipfile.lock` file
pipenv sync
```
**How to Run**:
1. Clone the repository to your local machine.
2. Create a virtual environment and install the dependencies listed in `requirements.txt`.
3. Run database migrations using `python manage.py migrate`.
4. Start the development server with `python manage.py runserver`.
5. Access the application in your browser at `http://127.0.0.1:8000/`.


Instrument Stack:
1. `flake8` - A tool for checking Python code style and linting, ensuring it complies with PEP 8 and identifying common errors.
2. `black` - An uncompromising Python code formatter that enforces consistent style throughout the codebase.
3. `isort` - Automatically sorts and organizes import statements in Python files.
4. `mypy` - A static type checker for Python, helping validate type annotations and prevent type-related errors.
5. `bandit` - A security analysis tool for Python code, detecting common security issues and vulnerabilities.
6. `pytest` (`pytest-django`) - A robust testing framework with `pytest-django` plugin for simplifying Django application testing.
7. `coverage` - A tool for measuring test coverage, showing how much of your code is exercised by tests.

Instrument Stack with Commands:
1. `flake8` - Command: `flake8 path/to/your/code`
2. `black` - Command: `black path/to/your/code`
3. `isort` - Command: `isort path/to/your/code`
4. `mypy` - Command: `mypy path/to/your/code`
5. `bandit` - Command: `bandit -r path/to/your/code`
6. `pytest` (`pytest-django`) - Command: `pytest path/to/your/tests`
7. `coverage` - Command: `coverage run -m pytest` (followed by `coverage report` or `coverage html`)