# Afrimat-final
AfriMat is an E-commerce application.
Afrimat has two different type of profiles: a dealer profile, and a costumer profile.
Costumers and dealers will be able to create an account and login/logout into their account.
Dealers will go through a vetting process to confirm they are genuine. 
Dealers will be able to add a product, delete a product or modify it.
Customers will be able to access a variety of products, view product and/or checkout products.

USER-INSTALLATION-GUIDE

Prerequisites
You will need the following things properly installed on your computer.

    Git
    Node.js (with NPM)
    Bower
    Ember CLI
    PhantomJS

Installation

    git clone <repository-url> this repository
    cd afrimat-final
    npm install
    bower install
    install django, e.g. pip install Django
    pip install djangorestframework
    pip install djangorestframework-filters
    pip install djangorestframework-jsonapi
    pip install markdown

Running the app
    ember serve
    Visit your app at http://localhost:4200.
    cd to the django directory, e.g. ../8470-demo-server-side/
    Launch runserver python manage.py runserver
    View the app in your browser at localhost:8000

    

Code Generators

Make use of the many generators for code, try ember help generate for more details
Running Tests

    ember test
    ember test --server

Building

    ember build (development)
    ember build --environment production (production)

Deploying

Specify what it takes to deploy your app.
Further Reading / Useful Links

    ember.js
    ember-cli
    Development Browser Extensions
        ember inspector for chrome
        ember inspector for firefox

