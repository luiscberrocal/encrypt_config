==============
Encrypt Config
==============


.. image:: https://img.shields.io/pypi/v/encrypt_config.svg
        :target: https://pypi.python.org/pypi/encrypt_config

.. image:: https://img.shields.io/travis/luiscberrocal/encrypt_config.svg
        :target: https://travis-ci.com/luiscberrocal/encrypt_config

.. image:: https://readthedocs.org/projects/encrypt-config/badge/?version=latest
        :target: https://encrypt-config.readthedocs.io/en/latest/?version=latest
        :alt: Documentation Status


.. image:: https://pyup.io/repos/github/luiscberrocal/encrypt_config/shield.svg
     :target: https://pyup.io/repos/github/luiscberrocal/encrypt_config/
     :alt: Updates



Encrypt and decrypt information in configuration files.

Most programmers do not include their credentials in the code itself. But how many times have you beeng doing peer programing and you open by mistake your credentials. That embarassing moment when you expose a password with an inappropiate content... jajaja. 

I find my self using json and ini files to store user credentials for
temporary use.

Currently just supporting JSON files and Fernet encryption.



* Free software: Apache Software License 2.0
* Documentation: https://encrypt-config.readthedocs.io.


Features
--------

* Encrypt json file content.

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
