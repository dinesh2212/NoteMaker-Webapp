# NoteMaker-Webapp

This is a web application is used to take down notes in a markdown format. It implements the basic CRUD functinality.
One can create, view, edit, and delete notes in the app.

The backend was implemented using django REST framework and the frontend was built using React.

## Instructions to run:

### Backend:

The required python libraries are:

- django
- djangorestframework
- django-cors-headers

You can install them by running: 

```bash
	pip install django
	pip install djangorestframework django-cors-headers
```

To run the server:

```bash
	cd NoteMaker-backend
	python manage.py runserver
```

### Frontend:

You can install all the react dependancies by running:

```bash
	cd NoteMaker-backend
	npm install
```

You can then use the app by entering into http://localhost:3000 on your browser

### Note :

It is advised to use the CORS-Unblock browser extension when testing this app on your browser
