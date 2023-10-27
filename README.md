# Pr-ctica-2-Flask-con-par-metros
# Guía de Introducción a Flask

## Clase Flask
Se utiliza la clase Flask para crear una instancia de la aplicación web. Esta clase es el punto de partida y se usa para definir rutas y vistas.

## Rutas (@app.route)
Las rutas se definen utilizando el decorador `@app.route('/ruta')`. Estas rutas especifican la URL que activará una función de vista cuando se acceda.

## Funciones de Vista
Las funciones de vista son funciones de Python asociadas a rutas específicas. Estas funciones de vista toman parámetros de la URL y devuelven una respuesta HTTP que se mostrará en el navegador.

## Parámetros en Rutas
Puedes incluir parámetros en las rutas utilizando sintaxis como `<nombre>` para capturar valores de la URL. Estos valores se pasan como argumentos a la función de vista correspondiente.

## Cadenas Formateadas (f-strings)
Las cadenas formateadas, marcadas por la letra 'f' antes de las comillas, permiten combinar texto estático con valores de variables de una manera legible y eficiente.

## Tipos de Datos en Rutas
Flask permite especificar el tipo de datos esperado para un parámetro en una ruta, como "int" (entero), "float" (punto flotante), "path" (cadena con barras diagonales) o "string" (cadena de caracteres).

## Función `return`
Las funciones de vista devuelven una respuesta utilizando la declaración `return`. Pueden devolver cadenas, objetos de respuesta personalizados o HTML dinámico generado en Python.

## Combinación de Rutas
Puedes definir múltiples rutas para la misma función de vista, lo que permite que la misma función maneje diferentes URL y parámetros.

## Condicionales
Se pueden utilizar condicionales en las funciones de vista para controlar el flujo y decidir qué respuesta enviar en función de los parámetros proporcionados en la URL.

Estos conceptos y funciones son esenciales al trabajar con Flask para construir aplicaciones web dinámicas y responder a diferentes solicitudes del cliente. Flask proporciona un marco flexible para el desarrollo web en Python y permite crear rutas y vistas de manera organizada y eficiente.
