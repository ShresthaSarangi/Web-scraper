# Web Scraper

A simple web-based site scraper built with **Django**. It allows users to scrape website links and store the extracted information in a database.

## Features

* Scrape links from websites
* Store scraped links in the database
* View scraped data through the Django admin panel
* Simple and easy-to-use web interface
* Built with Django and Python

## Tech Stack

* Python
* Django
* HTML/CSS
* SQLite
* BeautifulSoup
* Requests

## Installation

Clone the repository:

```bash
git clone <your-repository-url>
cd <project-folder>
```

Create and activate a virtual environment:

```bash
python -m venv env
```

Windows:

```bash
env\Scripts\activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run migrations:

```bash
python manage.py migrate
```

Start the development server:

```bash
python manage.py runserver
```

Open the project in your browser at:

```text
http://127.0.0.1:8000/
```
