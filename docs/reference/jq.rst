jq_
===

jq is like sed for JSON data - you can use it to slice and filter and map and transform structured data with the same ease that sed, awk, grep and friends let you play with text

Examples
--------

*takes an array of JSON data and returns the first element*

.. code-block:: bash

   http https://jsonplaceholder.typicode.com/users | jq '.[0]'

.. _jq: https://stedolan.github.io/jq/
