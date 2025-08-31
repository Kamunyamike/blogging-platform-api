# blogging-platform-api
# Simple Django Blog
A lightweight and user-friendly blogging platform built with Django. This project serves as a foundation for a fully functional blog, demonstrating core web development principles including user authentication, content management, and a robust testing environment.

# Key Features
Content Management: Create, edit, and delete blog posts.

User Authentication: Secure user sign-up, log-in, and log-out functionality.

Dynamic Routing: Individual pages for each blog post.

Testing Suite: Comprehensive unit tests for models and views to ensure application stability.

# Technologies Used
Backend: Python, Django

Database: SQLite3

Frontend: HTML, CSS

Testing: Django's built-in TestCase framework

# Getting Started
Follow these steps to get the project up and running on your local machine.

# Prerequisites
You will need the following installed on your system:

Python 3.10 or higher

pip (Python's package installer)

Git

# Installation
git clone https://github.com/Kamunyamike/blogging-platform-api.git
cd blogging-platform-api.git

## Create and activate a virtual environment:

# On Windows
python -m venv venv
.\venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate

### Install project dependencies:

pip install -r requirements.txt

### Run database migrations:

python manage.py migrate

### Create a superuser to access the admin panel:

python manage.py createsuperuser

### Running the Server
## Start the Django development server:

python manage.py runserver

Open your web browser and navigate to http://127.0.0.1:8000 to view the application.

Clone the repository:
