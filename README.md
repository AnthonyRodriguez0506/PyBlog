# PyBlog - A Flask Blog Project
PyBlog is a simple web blog application developed in Flask, a popular Python web framework. This application allows you to create, view, and delete blog posts from an SQLite database. Below are instructions on how to use this project.

## Prerequisites
Before you begin, make sure you have Python installed on your system. If you don't have it installed, you can download it from python.org.

## Usage 

Clone the project

```bash
  git clone https://github.com/AnthonyRodriguez0506/PyBlog.git
```

Install dependencies

```bash
cd PyBlog
pip install -r requirements.txt
```

Start the Development Server
Run the following command to start the Flask development server:

```bash
  python3 main.py
```

## Access the Application
Open your web browser and visit http://localhost:5000 to access the PyBlog application.

## Using the Application
Home (/): On the home page, you can view existing blog posts.
Add Post (/add): You can add new posts by providing a title and text content.
Delete Post: On the home page, each post has a "Delete" button. Click this button to delete a post.