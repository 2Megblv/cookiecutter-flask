cookiecutter-flask - Template
====================================

A(nother) Flask template for cookiecutter.

[cookiecutter](https://github.com/audreyr/cookiecutter)

Modified from the version authored by Github user: [sloria](https://github.com/sloria/cookiecutter-flask.git)

Goals
-----

The primary goal is to have a different logical split of files (models, views and services instead of public, user, etc), which
is purely personal preference.

Secondary is a slight expansion in scope to include other common pages and functionality, which is in progress. So far we
have completed:

 * Forgotten password handling
 * Username change
 * Password change
 * Unsubscribe
 * Google Analytics Integration
 * Heroku Integration
 
In progress are:

 * Simple text and external image blog powered by markdown

For the future are:

 * Sample contact form and page
 * Basic Admin UI
 * Example T\&Cs
 * Social Links/Integration
 * Login outside of the header (maybe modal)
 * Commenting on blog via discus or similar
 * Etc.

A live example can be found here: [CookieCutter Flask Demo](https://cookiecutterflask.herokuapp.com)

Contributing
------------

If you are interested in contributing please let me know, any of the future goals listed above would be great to help with.

Use it now
----------

    $ pip install cookiecutter
    $ cookiecutter https://github.com/wdm0006/cookiecutter-flask.git

You will be asked about your basic info (name, project name, app name, etc.). This info will be used in your new project.

Full example for pushing app to Heroku `here <http://willmcginnis.com/2015/09/28/cookiecutter-flask-and-some-other-stuff/>`_

![screenshot](https://github.com/wdm0006/cookiecutter-flask/blob/master/screenshots/cookiecutterflask.png "Template Screenshot")

Features
--------

 * Bootstrap 3 and Font Awesome 4 with starter templates
 * 3 Bootstrap themes included (standard, dark, and paper)
 * Flask-SQLAlchemy with basic User model
 * Easy database migrations with Flask-Migrate
 * Flask-WTForms with login and registration forms
 * Flask-Mail for forgotten password emails
 * Username/Password reset and unsubscribe functionality baked in
 * Flask-Login for authentication
 * Flask-Bcrypt for password hashing
 * Out-of-the-box ready for deploying to a PaaS (e.g. Heroku)
 * pytest and Factory-Boy for testing (example tests included)
 * A simple ``manage.py`` script.
 * CSS and JS minification using Flask-Assets
 * Caching using Flask-Cache
 * Useful debug toolbar
 * sitemap.xml and robots.txt built in
 * Utilizes best practices: [Blueprints](http://flask.pocoo.org/docs/blueprints/) and [Application Factory](http://flask.pocoo.org/docs/patterns/appfactories/) patterns


Inspiration
-----------

- [Sloria](https://github.com/sloria/cookiecutter-flask.git)

License
-------

BSD licensed.
