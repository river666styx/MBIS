Usage
=====

.. _searching:

Searching Posts
--------------

.. _threads:

Threads
------

.. _notifications:

Notifications
------------

.. _mute:

Muting/Unmuting Channels
----------------------

.. _imgur:

Sharing Imgur Albums
-------------------

.. _censor:

Censoring Content
-----------------

.. _reactions:

Viewing Reactions
-----------------

.. _username:

Username & Online Status
------------------------

.. _edit:

Edit & Delete Messages
----------------------

.. _format:

Formatting Text
---------------

To *italicize* your text, use asterisks as follows:

``*This sentence will send in italics.*``

To **bold** your text:

``**This sentence will send in bold.**``

.. _moveimage:

Moving Images Between Channels
------------------------------

.. _dms:

Sending Private Messages
------------------------

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

.. _chree

Chree
-----



Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

