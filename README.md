# bookStore
A bookStore project with django. Added payment functionalities.
This is a complete bookstrore project build on django. 
Installation Instructions
Clone the project.

$ git clone https://github.com/PrantaChakraborty/bookStore.git
cd into the project directory

$ cd bookStore
Create a new virtual environment using Python 3.7 and activate it.

$ python3 -m venv env
$ source env/bin/activate
Install dependencies from requirements.txt:

(env)$ pip install -r requirements.txt
Migrate the database.

(env)$ python manage.py migrate
(Optionally) load sample fixtures that will populate the database with a handful of users and tweeters.

Note: If fixtures are loaded, a sample user named 'Bob' will always be logged in by default.

(env)$ python manage.py loaddata initial_data
Run the local server via:

(env)$ python manage.py runserver
Done!
The local application will be available at http://localhost:8000, and the browsable api will be available at http://localhost:8000/api

If you need to update static assets, make sure to run collect static.

(env) $ python manage.py collectstatic
