Usage
=====

.. _installation:

Installation
------------

To use PrYmes, first install it using pip:

.. code-block:: console

   $ pip install prymes

Primality Test
----------------

To test if a number ``n`` is prime,
you can use ``is_prime(n)``:

.. autofunction:: prymes.is_prime

Alternatively you can also use ``n in P``, which is essentially the same.

For example:

>>> from prymes import *
>>> is_prime(998_244_353)
True
>>> 1_000_000_007 in P
True
