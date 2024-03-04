Validación de la entrada de datos del RFC: Se requiere validar la entrada de los primeros cuatro caracteres del RFC, para lo cual se necesita una expresión regular y generar el autómata de la cadena aceptada. Esto implica que el usuario deberá ingresar las primeras cuatro letras de su RFC, respetando siempre el orden de entrada. El programa debe aceptar cadenas tanto en mayúsculas como en minúsculas.

El desarrollo del programa puede realizarse en cualquier lenguaje de programación. Además, se deberá incluir una presentación, capturas de pantalla y el código. El código debe estar disponible en un repositorio de GitHub, cuya URL será incluida en el mismo PDF de la presentación.

Ejemplos de entrada y resultados esperados:

Entrada: "GUAL" - Resultado: Cadena válida - Autómata
Entrada: "gual" - Resultado: Cadena válida
Entrada: "GUA" - Resultado: Cadena válida - Autómata
Entrada: "Gu" - Resultado: Cadena válida - Autómata
Entrada: "G" - Resultado: Cadena válida - Autómata
Entrada: "GUL" - Resultado: Cadena no válida
Entrada: "GA" - Resultado: Cadena no válida
