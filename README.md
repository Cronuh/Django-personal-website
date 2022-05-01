# Django-personal-website

This is a Django-based portfolio I created for myself.
Live example is [here](https://http://k-digital.tech/)

# Installation and Running

* Run the command `git clone <repository-url>` to have this repository locally in your computer
* change into the new directory
* Run the command `python manage.py runserver --insecure` (otherwise you will get GET 404 - https://stackoverflow.com/a/58291398)
* Open your web browser and enter the adress of your local server (usually its http://127.0.0.1:8000 )


# Other tips and tricks
* If you deployed Django app onto cloud and want to keep your website alive even after loggin out do following: type `screen` > type `python manage.py runserver 0.0.0.0:8000`.
** If you will want to return type `screen -r` 