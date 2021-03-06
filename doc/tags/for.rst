``for``
=======

The Twital instruction for Twig's ``for`` tag is the ``t:for`` attribute.


Loop over each item in a sequence. For example, to display a list of users
provided in a variable called ``users``:

.. code-block:: xml+jinja

    <h1>Members</h1>
    <ul>
        <li t:for="user in users">
            {{ user.username }}
        </li>
    </ul>

.. note::

    For more information about ``if`` tag please refer to `Twig official documentation <http://twig.sensiolabs.org/doc/tags/for.html>`_.