===================
DesignPatternsPHP
===================

.. image:: https://github.com/domnikl/DesignPatternsPHP/workflows/CI/badge.svg
   :target: https://github.com/domnikl/DesignPatternsPHP/actions
.. image:: https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square
   :target: https://paypal.me/DominikLiebler

`Read the Docs of DesignPatternsPHP <http://designpatternsphp.readthedocs.org>`_ or 
`Download as PDF/Epub <https://readthedocs.org/projects/designpatternsphp/downloads/>`_

This is a collection of known design patterns and some sample codes on how to implement them in PHP. Every pattern has a small list of examples.

I think the problem with patterns is that often people do know them but don't know when to apply which.

Installation
------------

You should look at and run the tests to see what happens in the example.
To do this, you should install dependencies with `Composer` first::

   $ composer install

Read more about how to install and use `Composer` on your local machine `here <https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx>`_.

To run the tests use `phpunit`::

   $ ./vendor/bin/phpunit

Using Docker (optional)
-----------------------

You can optionally build and browse the documentation using `Docker for Mac, Windows or Linux <https://docs.docker.com/compose/install/>`_.

Just run::

   $ docker-compose up --build

Go to `http://localhost:8080/ <http://localhost:8080/>`_ to read the generated documentation.

If you want to localize your documentation you can pass the locale as an argument to the docker build::

   $ docker-compose build --build-arg language=de
   $ docker-compose up
