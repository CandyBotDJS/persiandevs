Usage
=====

.. _installation:

Installation
------------

To use persiandevs, First Install It With NPM:

.. code-block:: console

   $ npm install persiandevs

Posting Bot Stats
----------------

to post your bot stats
you can use the ``post_stats()`` function:

.. autofunction:: post_stats

The ``servers`` parameter should be your bots server count 

For example:

.. javascript:: 
     const persiandevs = require('persiandevs');
     persiandevs.post_status(69);
