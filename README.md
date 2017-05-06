# Progress - a Flask micro-app

Progress was a small investigation into Flask - a Python web framework. I am co-opting it for a team action items app that can run in the cloud.

## Todo
- [] Clean up data formatting
- [] Add delete task button
- [] Add database ability to assign people tasks (so another database for users and link to tasks)
- [] Add Twilio reminders for tasks
- [] Add Alexa insert task (for doing that during a meeting)

## Install

Install flask in a virtualenv, check out the app and run:

    # Create a virtualenv (you'll need setuptools/pip and virtualenv first)
    $ virtualenv ENV
    $ cd ENV
    $ source bin/activate

    # Install flask
    $ pip install flask

    # Get the progress app
    $ git clone git://github.com/rmasters/progress-flask.git progress

    # Configure the application
    $ cp config.py.original config.py
    $ vim config.py

    # Run the development server
    $ cd progress
    $ python progress.py


