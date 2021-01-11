## PROJECT NAME 
Personal-gallery


## Github link
https://github.com/Fridah-Alwanga/Personal-gallery


## Description
This is an online platform where I display my photos for others to see.A user can click on an image to view the image details. A user can also copy an image link.


##  Setup and installations
1. Fork the data onto your own personal repository.
2. Clone Project to your machine
3. Activate a virtual environment on terminal: <code>source virtual/bin/activate</code>
4. Install all the requirements found in requirements file.
5. On your terminal run <code>python3.7 manage.py runserver</code>
6. Access the live site using the local host provided



## Technologies used
<pre><code>
- Python3.6
- HTML
- Bootstrap 4
- Heroku
- Postgresql
- Django 1.11
</code></pre>


## Install dependancies
Install dependancies that will create an environment for the app to run <code>pip install -r requirements.txt</code>

## Make and run migrations
<pre><code>
python3.7 manage.py check
python manage.py makemigrations gallery
python3.7 manage.py sqlmigrate gallery 0001
python3.7 manage.py migrate
</code></pre>