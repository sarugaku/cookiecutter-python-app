============================================
Cookiecutter Template for Python Application
============================================


Usage
=====

::

    cookiecutter https://github.com/sarugaku/cookiecutter-python-app


Features
========

Pipfile for dependency management
---------------------------------

We recommend using Pipenv_ to work with the Pipfile.

Run this inside the project after generation::

    pipenv install --dev

All dependencies (including the in-development package itself) are already
listed in the generated Pipfile.

Invoke_ for automation
----------------------

Add tasks in ``tasks`` directory, and you can run them with ``pipenv run inv``.


.. _Pipenv: https:://pipenv.org
.. _Invoke: http://www.pyinvoke.org/
