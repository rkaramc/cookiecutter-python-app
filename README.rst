===================================
Python Application Project Template
===================================

.. _travis: https://travis-ci.org/rkaramc/cookiecutter-python-app
.. |travis.png| image:: https://travis-ci.org/rkaramc/cookiecutter-python-app.svg?branch=master
   :alt: Travis CI build status
   :target: `travis`_

|travis.png|

.. _Cookiecutter: http://cookiecutter.readthedocs.org
.. _Python Packaging User Guide: https://packaging.python.org/en/latest/distributing.html#configuring-your-project
.. _Packaging a Python library: http://blog.ionelmc.ro/2014/05/25/python-packaging
.. _Python App Template: https://github.com/mdklatt/cookiecutter-python-app

This is a `Cookiecutter`_ template for creating a Python application project.
It has been forked from Michael Klatt's `Python App Template`_.

The project layout is based on the `Python Packaging User Guide`_. The current
conventional wisdom forgoes the use of a source directory, but moving the
package out of the project root provides several advantages (*cf.*
`Packaging a Python library`_).


.. _py27: https://github.com/mdklatt/cookiecutter-python-app/tree/py27

The `py27`_ branch is for Python 2.7 compatibility; it is no longer actively
maintained.


Template Project Features
=========================

.. _pytest: http://pytest.org
.. _Sphinx: http://sphinx-doc.org
.. _MIT License: http://choosealicense.com/licenses/mit

- Python 3.4+
- `MIT License`_
- `pytest`_ test suite
- `Sphinx`_ documentation


Template Application Features
=============================

.. _YAML: http://pyyaml.org/wiki/PyYAML

- CLI with subcommands
- Logging
- Hierarchical `YAML`_ configuration


Usage
=====

.. _GitHub: https://github.com/rkaramc/cookiecutter-python-app


Install Python requirements for using the template:

.. code-block:: console

    $ python -m pip install --requirement=requirements.txt --user


Create a new project directly from the template on `GitHub`_:

.. code-block:: console

    $ cookiecutter gh:rkaramc/cookiecutter-python-app
