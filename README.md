= Flask Mega-Tutorial

This repo will be used to follow the Flask Mega-Tutorial, along with any additions or experimentation along the way:

https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

== To Do

=== Tasks & Research

This will carry a list of tasks and questions for research, that are outside the scope of what the tutorial covers.

* Verify that AsciiDoc syntax is playing nice as the README's markdown language.
* IDE? PyCharm Community is nice, but how does VSCode stack up?
Also investigate PyCharm Professional, which has Flask support built-in.
* Python virtual environments:
** Learn more about Python virtual environments.
** Provide a summary / write-up on Python virtual environments.
* Flask
** Learn more about Flask.
** Provide a summary / write-up on Flask.
* Is it worthwhile to keep a chapter by chapter summary in the README?
(will do so at the start; determine later if there's value, delete if not)


=== Course Outline

In addition to the above, the following is the status of my progress on this tutorial:

* Chapter 1: Hello, World! *- in progress*
* Chapter 2: Templates
* Chapter 3: Web Forms
* Chapter 4: Database
* Chapter 5: User Logins
* Chapter 6: Profile Page and Avatars
* Chapter 7: Error Handling
* Chapter 8: Followers
* Chapter 9: Pagination
* Chapter 10: Email Support
* Chapter 11: Facelift
* Chapter 12: Dates and Times
* Chapter 13: I18n and L10n
* Chapter 14: Ajax
* Chapter 15: A Better Application Structure
* Chapter 16: Full-Text Search
* Chapter 17: Deployment on Linux
* Chapter 18: Deployment on Heroku
* Chapter 19: Deployment on Docker Containers
* Chapter 20: Some JavaScript Magic
* Chapter 21: User Notifications
* Chapter 22: Background Jobs
* Chapter 23: Application Programming Interfaces (APIs) 



== Getting Started

The following are required for this tutorial:

- Python 3
- A Python 3 virtual environment
- Flask


=== Python 3

In new enough versions of Fedora, Python 3 is the default: `dnf install python`.
Additional Python packages should be installed via `pip`.

A Python interpreter, useful for testing out quick commands, can be opened using the `python` command from the CLI.
Use `exit()` when finished.

.Python Interpreter
[source, python]
----
$ python
Python 3.9.2 (default, Feb 20 2021, 00:00:00) 
[GCC 10.2.1 20201125 (Red Hat 10.2.1-9)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 1+1
2
>>> exit()
----



=== Python 3 Virtual Environment

Run the following command from the top-level of the project:

`python -m venv venv`

Once the virual environment is created, activate it:

`source venv/bin/activate`



=== Flask

To install Flask: `pip install Flask`

NOTE: Ensure that a virtual environment has been created and activated before running this step.

Once Flask is installed, verify it using the Python interpreter:

.Verify the Flask installation
[source, python]
----
>>> import flask
>>>
---


If Flask failed to install correctly, an error will occur on attempting to import:

.Flask installation failure: error message
[source, python]
----
>>> import flask
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ModuleNotFoundError: No module named 'flask'
>>>
----


== Chapter 1: Hello, World!

TODO

