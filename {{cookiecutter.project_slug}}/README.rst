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

.. image:: https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg
   :target: .github/CODE_OF_CONDUCT.md
   :alt: Code of Conduct

.. image:: https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}/workflows/CI-CD/badge.svg
   :target: https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}/workflows/CI-CD
   :alt: GitHub Actions

.. image:: https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}
   :alt: Codecov

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/ambv/black
   :alt: Code Style Black

.. image:: https://readthedocs.org/projects/{{cookiecutter.project_slug}}/badge/?version=latest
   :target: https://{{cookiecutter.project_slug}}.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status

.. summary-start

{{cookiecutter.project_short_description}}

Post Template-Instantiation Steps
=================================

1. Start working with git.

   .. code-block:: console

       git init

2. Commit all the files.

   .. code-block:: console

       git add .
       git commit

3. Create a repository on `GitHub <https://github.com/>`_ if you haven't done
   so yet.
4. Browse through the architecture decision records (``docs/adr``) if you want
   to understand details of the package design.
5. Remove this section from the readme and describe what your package is all
   about.
6. When you're ready to make a release, perform the following steps.

   1. On `GitHub <https://github.com/>`_ set the secure environment
      variables ``PYPI_USERNAME`` and ``PYPI_PASSWORD`` to ``__token__`` and a respective PyPI API token.
   2. Tag your latest commit with the desired version and let GitHub handle
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

* Copyright © {{cookiecutter.year}}, {{cookiecutter.full_name}}.
* Free software distributed under the `Apache Software License 2.0
  <https://www.apache.org/licenses/LICENSE-2.0>`_.

.. summary-end
