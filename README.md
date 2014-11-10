LunchPY
=======

An entirely necessary web app for voting on where you should go for lunch written in Python and using the Django framework.

This app comes complete with a not so beautiful UI, automated tests, User authentication, and a real solution to the lunch problem.

You can use the existing db.sqlite3 file or create your own.

With the existing file, you'll want to log in with username: `admin` and password: `admin`.

If you use your own, you'll need to run through the migrations : `python manage.py migrate` and setup a user: `python manage.py createsuperuser`.

Then you can run the server locally with `python manage.py runserver`.

Probem solved, never debate on where you'll eat lunch with your friends again.
