Installing Rails
================

In Windows
----------

- Use [RailsInstaller](http://railsinstaller.org/)

In Linux (on Ubuntu)
--------------------

- Open a terminal:
    $ sudo apt-get install apache2 curl git libmysqlclient-dev mysql-server nodejs
    $ sudo apt-get install ruby1.9.3
    $ sudo gem install rails

Setting Up Your Development Environment
=======================================

What Text Editor Should I Use?
------------------------------

- We reccommend using Vim. It supports many features
- Other options include: E-TextEditor, Aptana RadRails, Netbeans, jEdit, Komodo

Local API Documentation
-----------------------

    $ rails new dummy
    $ cd dummy
    $ rake doc:rails

- Now move the doc/api folder somewhere safe and delete the dummy/ folder
- You can view the API from doc/api/index.html
