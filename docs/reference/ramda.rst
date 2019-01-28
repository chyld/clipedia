ramda_
======

A tool for processing data with functional pipelines. In the command-line or interactively in browser.

Examples
--------

*opens interactive browser during ramda use to visualize output*

.. code-block:: bash

   cat file.json | ramda --interactive

*create sequence of values, convert to integers and sum*

.. code-block:: bash

   seq 10 | ramda --raw-input --slurp 'map parse-int' sum

.. _ramda: https://github.com/raine/ramda-cli
