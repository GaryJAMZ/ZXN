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

en chroot

install2

#parametro 1 nombre del host

#parametro 2 letra de unidad de almacen o nombre completo si se usa nvme

#parametro 3 nombre de cryptsetup usado

#parametro 4 nombre de usuario

salir y reiniciar

Hasta aqui ya tienes un Arch linux instalado cifrado y limpio

para una interfaz grafica seguir los siguientes pasos

installgpu

la instalacion de los driver de gpu se uso parte del codigo del scrip de helmuthdu asi como sus funciones compartidas para este unico scrip

posterior 

install3

#pasar parametro nombre de usuario


y reiniciar

finalizar con

install4

#parametro nombre de usuario
y en root 
installrootcfg

NOTA: NO USAR SUDO PARA LANZAR EL SCRIPT
