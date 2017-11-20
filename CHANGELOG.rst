=========
Changelog
=========

All notable changes to this project will be documented in this file.

The format is based on `Keep a Changelog <http://keepachangelog.com/en/1.0.0/>`_
and this project adheres to `Semantic Versioning <http://semver.org/spec/v2.0.0.html>`_.

.. note::

    The library **"Python-Deprecated"** was renamed **"Deprecated"**, simply!
    This project is more consistent because now, the name of the library is the same as the name of the Python package.

    - In your ``setup.py``, you can replace the "Python-Deprecated" dependency with "Deprecated".
    - In your source code, nothing has changed, you will always use ``import deprecated``, as before.
    - I decided to keep the same version number because there is really no change in the source code
      (only in comment or documentation).


v1.1.0 (2017-11-06)
===================

Minor release

Added
-----

- Change in :func:`deprecated.deprecated` decorator: you can give a "reason" message
  to help the developer choose another class, function or method.
- Add support for Universal Wheel (Python versions 2.6, 2.7, 3.3, 3.4, 3.5, 3.6 and PyPy).
- Add missing ``__doc__`` and ``__version__`` attributes to :mod:`deprecated` module.
- Add an extensive documentation of Deprecated Library.

Other
-----

- Improve `Travis <https://travis-ci.org/>`_ configuration file (compatibility from Python 2.6 to 3.7-dev, and PyPy).
- Add `AppVeyor <https://www.appveyor.com/docs/>`_ configuration file.
- Add `Tox <https://tox.readthedocs.io/en/latest/>`_ configuration file.
- Add `BumpVersion <https://github.com/peritus/bumpversion>`_ configuration file.
- Improve project settings: add a long description for the project.
  Set the **license** and the **development status** in the classifiers property.
- Add the :file:`CONTRIBUTING.rst` file: "How to contribute to Deprecated Library".


v1.0.0 (2016-08-30)
===================

Major release

Added
-----

- **deprecated**: Created **@deprecated** decorator