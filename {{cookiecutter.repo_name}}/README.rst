****************************
{{ cookiecutter.dist_name }}
****************************

.. image:: https://img.shields.io/pypi/v/{{ cookiecutter.dist_name }}.svg
    :target: https://pypi.org/project/{{ cookiecutter.dist_name }}/
    :alt: Latest PyPI version

.. image:: https://img.shields.io/circleci/project/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/master.svg
    :target: https://circleci.com/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}
    :alt: CircleCI build status

.. image:: https://img.shields.io/codecov/c/github/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/master.svg
    :target: https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}
    :alt: Test coverage

{{ cookiecutter.short_description }}


Installation
============

Install by running::

    python3 -m pip install {{ cookiecutter.dist_name }}

Or, if available, install the Debian/Ubuntu package from
`apt.mopidy.com <https://apt.mopidy.com/>`_.


Configuration
=============

Before starting Mopidy, you must add configuration for
{{ cookiecutter.dist_name }} to your Mopidy configuration file::

    [{{ cookiecutter.ext_name }}]
    # TODO: Add example of extension config


Project resources
=================

- `Source code <https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.dist_name|lower }}>`_
- `Issue tracker <https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.dist_name|lower }}/issues>`_
- `Changelog <https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.dist_name|lower }}/blob/master/CHANGELOG.rst>`_


Credits
=======

- Original author: `{{ cookiecutter.author_full_name }} <https://github.com/{{ cookiecutter.github_username }}>`__
- Current maintainer: `{{ cookiecutter.author_full_name }} <https://github.com/{{ cookiecutter.github_username }}>`__
- `Contributors <https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.dist_name|lower }}/graphs/contributors>`_
