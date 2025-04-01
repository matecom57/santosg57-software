Comados útiles
==============

Copiar un folder local ``ff`` a un sitio remoto:

.. code:: Bash

   scp -r ff test@132.248.248.189:/home/test/.

Donde:

``ff`` - es el folder que se desea enviar a máquina remota

``test`` - usuario definido en la maquina remota

``/home/test/`` - es el folder donde se guardará el folder ``ff``

``132.248.248.189`` - es la dirección ``IP`` de la máquina remota

