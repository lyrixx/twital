``capture``
===========

This attribute act as ``set`` tag and allows to 'capture' chunks of text into a variable:

.. code-block:: xml+jinja

    <div id="pagination" t:capture="foo">
        ... any content ..
    </div>


All contents inside "pagination" div will be captured and saved inside a variable named `foo`.

.. note::

    For more information about ``set`` tag please refer to `Twig official documentation <http://twig.sensiolabs.org/doc/tags/set.html>`_.