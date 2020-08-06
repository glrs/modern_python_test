The Modern Python Test project
==============================

.. toctree::
   :hidden:
   :maxdepth: 1

   license
   reference

The example project of
`Hypermodern Python <https://medium.com/@cjolowicz/hypermodern-python-d44485d9d769>`_
article series.
The command-line interface prints random facts to your console,
using th `Wikipedia API <https://en.wikipedia.org/api/rest_v1/#/>`_.


Installation
____________

To install the Modern Python Test project,
run this command in your terminal:

.. code-block:: console

   $ pip install modern-python


Usage
_____

Modern Python Test's usage looks like:

.. code-block:: console

   $ modern-python [OPTIONS]

.. option:: -l <language>, --language <language>

   The Wikipedia language edition,
   as identified by its subdomain on
   `wikipedia.org <https://wikipedia.org/>`_.
   By default, the English Wikipedia is selected.

.. option:: --version

   Display the version and exit.

.. option:: --help

   Display a short usage message and exit.
