chumod (o+w ejemplo) para aportar permisos - quitar, +añadir, se puede escribir todo en la misma linea ej: chmod u-w, g+x, o+w
w-escritura  u-usuario
r-lecura       o-otros
x-meterte dentro  g-grupos
; separar comandos en  una misma linea
echo $? ver si el codigo anterior ha sido correcto (0 correcto)
&& separa comandos pero solo se ejecuta si el primero es correcto
| | separa comados y se ejecuta aunque el primero no sea correcto
(comando incorrecto) 2>/dev/null te lo envia a papelera
&>/dev/null ocultar el output del script