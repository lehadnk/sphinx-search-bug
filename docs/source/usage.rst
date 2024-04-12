Usage
=====

Installation
------------

To build documentation:

.. code-block:: console

   (.venv) $ make build

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. py:function:: lumache.get_random_ingredients(kind=None)

   Return a list of random ingredients as strings.

   :param kind: Optional "kind" of ingredients.
   :type kind: list[str] or None
   :return: The ingredients list.
   :rtype: list[str]

Creating recipes auto
---------------------

To retrieve a list of random ingredients,
you can use the ``src.main.get_random_ingredients()`` function:

.. autofunction:: src.main.get_random_ingredients