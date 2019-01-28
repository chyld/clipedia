touch
=====

Creates empty file and change file timestamps.

Examples
--------

*creates a new foo.py file*

.. code-block:: bash

   touch foo.py

*creates file1.py, file1.js in steps of 2 to file9.py and file9.js*

.. code-block:: bash

   touch file{1..10..2}.{py,js}
