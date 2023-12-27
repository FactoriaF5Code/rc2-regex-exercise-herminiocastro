[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/aRQGnba4)
# Expresiones Regulares (regex)

## Investiga: 

- qué son las expresiones regulares? patrones de búsqueda utilizados para encontrar y manipular texto en cadenas de caracteres.
^: Coincide con el inicio de una cadena.
$: Coincide con el final de una cadena.
.: Coincide con cualquier carácter, excepto un salto de línea.
*: Coincide con cero o más repeticiones del elemento anterior.
+: Coincide con una o más repeticiones del elemento anterior.
?: Hace que el elemento anterior sea opcional (cero o una repetición).
[]: Define un conjunto de caracteres permitidos para la coincidencia.
|: Representa una alternativa, similar a "o".
(): Agrupa expresiones y recuerda la coincidencia para su uso posterior.

- Qué problema resuelven? Por qué es importante conocerlas?
Búsqueda y Validación de Patrones
Validación de Formatos: Verificar si una cadena cumple con un formato específico, como direcciones de correo electrónico, números de teléfono, fechas, etc.
Búsqueda de Patrones: Encontrar ocurrencias específicas dentro de un texto. Por ejemplo, buscar palabras clave, direcciones URL, números, etc.
Manipulación de Texto
Extracción de Datos: Extraer partes específicas de un texto, como números, nombres, direcciones, etc.
Reemplazo de Texto: Reemplazar o modificar texto basado en patrones definidos.
Procesamiento de Entrada
Validación de Datos: Verificar y filtrar datos de entrada en formularios o aplicaciones para garantizar que cumplan con ciertos criterios.
Tokenización: Dividir una cadena en tokens (componentes más pequeños) basados en patrones, como separar palabras en una oración.
Manipulación de Cadenas
Transformaciones de Texto: Realizar cambios en el formato o estructura de las cadenas según patrones específicos.
Formateo de Texto: Dar formato a texto de acuerdo con ciertas reglas predefinidas.
-Es importante conocer las expresiones regulares porque ofrecen una poderosa forma de manejar y manipular cadenas de texto de manera eficiente. Conocerlas permite a los desarrolladores realizar operaciones complejas de búsqueda, validación y manipulación de texto de una manera más efectiva y concisa.

## Ejercicio 1:

Escribe las expresiones regulares correctas para validar:

- un email: /^[\w-]+(\.[\w-]+)*@([\w-]+\.)+[a-zA-Z]{2,7}$/

- un número de teléfono (español): /^\+(34|0034)?\s*([689]\d{2}\s?\d{3}\s?\d{3}|7[1-9]\d{1}\s?\d{3}\s?\d{3})$/

- un DNI: /^\d{8}[a-zA-Z]$/


## Ejercicio 2:

Crea un formulario de contacto y utiliza el atributo `pattern` de los elementos `input` para validar los campos usando expresiones regulares. El formulario debe incluir: nombre, apellidos, dni, número de teléfono, email, dni y dirección.

Nota: puedes hacerlo añadiendo un archivo `index.html` en este repositorio.


## Referencias

- [Expresiones Regulares en Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions)
- [Online Regex Editor](https://regex101.com/)