=============================
{{cookiecutter.project_name}}
=============================

.. image:: https://img.shields.io/pypi/v/{{cookiecutter.project_slug}}.svg
   :target: https://pypi.org/project/{{cookiecutter.project_slug}}/
   :alt: Current PyPI Version

.. image:: https://img.shields.io/pypi/pyversions/{{cookiecutter.project_slug}}.svg
   :target: https://pypi.org/project/{{cookiecutter.project_slug}}/
   :alt: Supported Python Versions

.. image:: https://img.shields.io/pypi/l/{{cookiecutter.project_slug}}.svg
   :target: https://www.apache.org/licenses/LICENSE-2.0
   :alt: Apache Software License Version 2.0

.. image:: https://img.shields.io/travis/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}/master.svg?label=Travis%20CI
   :target: https://travis-ci.org/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}
   :alt: Travis CI

.. image:: https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}
   :alt: Codecov

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/ambv/black
   :alt: Black

{{cookiecutter.project_short_description}}

Post Template-Instantiation Steps
=================================

1. Start working with git.

   .. code-block:: console

       git init

2. Check for an updated versioneer. The current one only works nicely with 
   pip<19.

   .. code-block:: console
   
       pip install versioneer
       versioneer install

   You probably have to remove the mess in ``src/{{cookiecutter.project_module}}/__init__.py``.

3. Commit all the files.

   .. code-block:: console

       git add .
       git commit

4. Create a repository on `GitHub <https://github.com/>`_ if you haven't done
   so yet and link it to `Travis CI <https://travis-ci.org/>`_.
5. Browse through the architecture decision records (``docs/adr``) if you want
   to understand details of the package design.
6. Remove this section from the readme and describe what your package is all 
   about.
7. When you're ready to make a release, perform the following steps.

   1. On `Travis CI <https://travis-ci.org/>`_ set the secure environment 
      variables ``PYPI_USERNAME``, ``PYPI_PASSWORD``, and ``GITHUB_TOKEN``.
   2. Tag your latest commit with the desired version and let Travis handle 
      the release.

      .. code-block:: console

          git tag 0.1.0
          git push origin 0.1.0

Install
=======

It's as simple as:

.. code-block:: console

    pip install {{cookiecutter.project_slug}}

Copyright
=========

* Copyright (c) {{cookiecutter.year}}, {{cookiecutter.full_name}}.
* Free software distributed under the `Apache Software License 2.0 
  <https://www.apache.org/licenses/LICENSE-2.0>`_.