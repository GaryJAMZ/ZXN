# ZXN
Work

Este repositorio esta destinado a guardar mi configuracion de instalacion de Archlinux segun mis requerimientos.

Nota: archivo installblack es experimental pero no afecta en nada si esta aqui ya que no se utiliza nunca por ningun script listado a continuación.

orden de ejcutcion

Primero hacer chmod de install y ejecutar
#pasar 3 parametros al script

#parametro 1 nombre de la unidad (sda,sdb,nvme) identificar exactamente la unidad donde instalar

#parametro 2 nombre para el cifrado

#parametro 3 amd-ucode o intel-ucode

#parametro 4 Nombre del Host

#parametro 5 Nombre del usuario

Reiniciara el sistema.

Hasta aqui ya tienes un Arch linux instalado cifrado y limpio

para vmware o nvidia al ejecutar after los detectara si no se deben instalar antes de ejecutar los drivers correspondientes

una vez eso en cuenta ejecutar after

#pasar parametro nombre de usuario


y reiniciar

finalizar con root

installrootcfg

NOTA: NO USAR SUDO PARA LANZAR EL SCRIPT
