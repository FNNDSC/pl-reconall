################################
pl-reconall
################################


Abstract
********

A plugin app for Freesurfer reconstruction of brain surfaces

Run
***

Using ``docker run``
====================

Assign an "input" directory to ``/incoming`` and an output directory to ``/outgoing``

.. code-block:: bash

    docker run -v $(pwd)/in:/incoming -v $(pwd)/out:/outgoing   \
            fnndsc/pl-reconall reconall.py            \
            /incoming /outgoing

This will ...

Make sure that the host ``$(pwd)/out`` directory is world writable!







