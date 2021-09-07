# TRADE
Especificación de Trade - Calidad de Software
E01: Especificación del programa “trade”
 Visión general
El programa lee un fichero que contiene información acerca de una serie de empresas, y ha de procesar dicha información de modo apropiado. A continuación aparece un ejemplo sencillo de su uso:
Nombre
trade – Analiza la tendencia en el mercado de valores de una serie de empresas.
Uso
trade.exe  fichero-de-entrada.txt
Descripción
trade analiza la información bursátil contenida en un fichero de una serie de empresas y la muestra por pantalla. Se debe proporcionar al programa el nombre de un fichero y opcionalmente se le puede pedir información más detallada del análisis bursátil en forma de opciones. El orden de las opciones no es importante, aunque deben aparecer antes del nombre del fichero.
El fichero contiene la información de las empresas que se quieren analizar. Dicha información se refiere al número de acciones que posee la empresa, el sector al que pertenece y el precio por acción.
Datos de Entrada
Cada dato de entrada deberá estar separado solo por un espacio en blanco 
Cada línea del fichero de entrada deberá contener la siguiente información:
Descripción de la empresa.
	Contendrá el código del sector de la industria al que pertenece la empresa. Dicho código solo pueden ser: C (comida), T (transporte), O (ordenadores), M (metal), S (salud) o A (aerolíneas) seguido por un guión (-) y el nombre de la empresa sin espacios en blanco.
	El código debe ser escrito solo con letras mayúsculas.
Precio de cada acción de la compañía.
	El valor debe ser mayor y diferente de 0
Número de acciones que posee la empresa.
	El valor debe ser mayor y diferente de 0

