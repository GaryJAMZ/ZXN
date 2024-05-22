# ZXN
Work

Este repositorio esta destinado a guardar mi configuracion de instalacion de Archlinux segun mis requerimientos.

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

NOTA: NO USAR SUDO PARA LANZAR EL SCRIPT Y TENER EN CUENTA QUE AFTER PREGUNTARA SI SE DESEA UNA CONFIGURACION PERSONALIZADA TOMARA MAS TIEMPO YA QUE INSTALA APLICACIONES QUE SUELO UTILIZAR, ADEMAS DE HABILITAR PARU Y BLACKARCH REPOS, DE ELEGIR "NO" O DEJAR POR DEFECTO CON ENTER SE BORRARAN LOS ARCHIVOS DE INSTALCION PERSONALIZADOS.


y reiniciar

finalizar la instalacion en path root como root

rootinstaller
este es opcional e innecesario solo es para isntalar nvchad y powerlvl10k para zsh del usuario root
