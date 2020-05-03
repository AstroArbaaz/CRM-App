# Demo CRM-App
This is a Django project with a React front-end.
The REST API is created with Django REST framework and consumed with Axios.

# installation
> create a virtualenv "pip install virtualenv"
> clone this repository in your computer & open this directory in your terminal.
> now install the python requirements run "pip install -r requirements.txt"
> change directory to frontend and type "npm install"

# To run this app
> open the root directory and run "Python manage.py runserver" this will run the Django application which is the backend/server part of the app on "port:8000" i.e. "http://Localhost:8000"
> open a second terminal and run "npm start" this will start the frontend react app which is client part of the app on "port:3000" i.e "http://localhost:3000"

# To create a new customer
> locate to react app on port 3000 and click on the create customer link on the nav bar.

# To view the customer list in django
> http://localhost:8000/api/customers/ >> this page will show you the customers list in json format

# To access the admin site
> http://localhost:8000/admin/
>> username : administrator
>> password : administrator
