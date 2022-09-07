# AnalisisDatosApuestas


NOTA: Como añadir nueva casa

### FICHEROS A MODIFICAR PARA AÑADIR NUEVA CASA: ###

En Ficheros de texto plano:
CuentasM.txt: *nombre* de la casa y "ZEN JUEGO *NOMBRE*"
casas.txt: *nombre* y "zen *nombre*"

lista_opciones.txt: nombre de la casa

En archivo "comun.module":

Añadir condicional para asignar casa:
ejemplo:
  If contiene(casa, "winamax") Then Return "winamax"

En FormFiltro.clas:
Añadir en array casas[] el nombre de la casa y el case para asignar icono


En la subcarpta "iconos", añadir imagen de 80x25