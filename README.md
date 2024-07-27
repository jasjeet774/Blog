# Blog Project

This is a Django-based blog application where users can create, edit, and delete posts, as well as add comments.

## Features

- User authentication (login, logout, signup)
- Create, edit, and delete blog posts
- Add comments to posts
- Tailwind CSS integration for styling

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/blog-project.
```
```bash
cd blog-project
```
Create virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
Install requirements
```bash
pip install -r requirements.txt
```
Run the migrations
```bash
python manage.py migrate
```
Create a superuser to access the admin panel:
```bash
python manage.py createsuperuser
```
Run the development server
```bash
python manage.py runserver
```
## Usage
- Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to access the blog.
- Login or sign up to create new posts and add comments.