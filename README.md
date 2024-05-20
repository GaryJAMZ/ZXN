# ZXN
Work

Este repositorio esta destinado a guardar mi configuracion de instalacion de Archlinux segun mis requerimientos.

Nota: archivo installblack es experimental pero no afecta en nada si esta aqui ya que no se utiliza nunca por ningun script listado a continuación.

orden de ejcutcion

si se usa sd y no un nvme o algun otro tipo de unidad difernte usar installsd1 e installsd2, para unidades nvme o diferentes usar install1 e install2 agregando el nombre del disco completo no solo la letra

install1

#pasar 3 parametros

#parametro 1 letra del disco a instalar o nombre completo si se usa nvme

#parametro 2 nombre para el cifrado

#parametro 3 amd-ucode o intel-ucode

#parametro 4 Nombre del Host

#parametro 5 Nombre del usuario

Reiniciara el sistema.

Hasta aqui ya tienes un Arch linux instalado cifrado y limpio

Para instalar la interfaz grafica deben buscarse manualmente los comandos dependiendo de la gpu.
una vez tengas los drivers de tu GPU puedes proceder con install3

install3

#pasar parametro nombre de usuario


y reiniciar

finalizar con root

installrootcfg

NOTA: NO USAR SUDO PARA LANZAR EL SCRIPT
