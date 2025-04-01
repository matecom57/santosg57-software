Comados útiles
==============

scp
---

Copiar un folder local ``ff`` a un sitio remoto:

.. code:: Bash

   scp -r ff test@132.248.248.189:/home/test/.

Donde:

``ff`` - es el folder que se desea enviar a máquina remota

``test`` - usuario definido en la maquina remota

``/home/test/`` - es el folder donde se guardará el folder ``ff``

``132.248.248.189`` - es la dirección ``IP`` de la máquina remota


sshfs
-----

Aloja un folder remoto en el home local.

.. code:: Bash

   sshfs velasco@172.24.80.90:/ParKini ./parkinos

Donde:

``velasco@172.24.80.90:/ParKini`` - es el folder remosto que se quiere alojar localmente

``parkinos`` - es el folder local que será un alias al folder remoto, es decir, si modificamos un archivo localmente, se actualizara 
remotamente también. 


