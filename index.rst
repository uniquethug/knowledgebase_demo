.. demo documentation master file, created by
   sphinx-quickstart on Fri Apr 28 13:38:45 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to demo's documentation!
================================
.. versionadded:: 2.5
   The *spam* parameter.

.. toctree::
   :maxdepth: 2
   :titlesonly:
   :numbered:
   :caption: Getting Started Guide

   started_guide/hpm_sdk_setup
   started_guide/guide2

.. code-block:: python
   :emphasize-lines: 3,5

   print("hello world")

.. note::

   This function is not suitable for sending spam e-mails.


.. seealso::

   Module :py:mod:`zipfile`
      Documentation of the :py:mod:`zipfile` standard module.

   `GNU tar manual, Basic Tar Format <http://link>`_
      Documentation for tar archive files, including GNU tar extensions.

.. centered:: LICENSE AGREEMENT


.. hlist::
   :columns: 3

   * A list of
   * short items
   * that should be
   * displayed
   * horizontally


.. glossary::

   environment
      A structure where information about all documents under the root is
      saved, and used for cross-referencing.  The environment is pickled
      after the parsing stage, so that successive runs only need to read
      and parse new and changed documents.

   source directory
      The directory which, including its subdirectories, contains all
      source files for one Sphinx project.

.. glossary::

   term 1
   term 2
      Definition of both terms.

.. sectionauthor:: Guido van Rossum <guido@python.org>


.. index::
   single: execution; context
   pair: module; __main__
   pair: module; sys
   triple: module; search; path



.. hello::

..  youtube:: 273281718


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
