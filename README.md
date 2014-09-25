Mitro Emailer
=============

An alternative to emailer2 packaged with Mitro. Like the original script, this also polls a table in the Postgres database to send email.

Why It's Better
---------------
* Configurable
* Supports SMTP, Mailgun, and Mandrill
* Handles system interrupts
* Better templates
* Intended to be managed by Supervisor

What's Missing
--------------
* A number of templates
* Unit tests

Requirements
------------
Python 2.7 (not tested on 3+)
Postgres with the development libraries

Install
-------
```
pip install virtualenv
```

```
./build.sh to set up Python virtualenv with dependencies. You may need run
```

Configure
---------
Simply edit config.ini

Run
---
build/venv/bin/python emailer.py
