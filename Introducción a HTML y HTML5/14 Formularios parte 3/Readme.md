# Lección 21: Seguimos trabajando con Formualrios

En esta lección se enseña cómo enviar información a un servidor utilizando formularios web. Se muestra cómo enviar archivos grandes utilizando el método **POST** y el tipo de codificación **multipart/form data**. Luego, se explica cómo enviar diferentes tipos de información como **time**, **date**, **datetime** y **checkbox**, y cómo se envían los valores de estos inputs al servidor. Además, menciona que los formatos de fecha varían dependiendo de la configuración regional de la computadora. A lo largo de la clase, se va comentando y probando diferentes secciones del código en tiempo real.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Ejemplo de formulario con método POST</title>
  </head>
  <body>
    <form action="http://localhost" method="post" enctype="multipart/form-data">
  <label for="time">Hora:</label>
  <input type="time" id="time" name="hora"><br>

  <label for="date">Fecha:</label>
  <input type="date" id="date" name="fecha"><br>

  <label for="datetime">Fecha y Hora:</label>
  <input type="datetime-local" id="datetime" name="fecha_hora"><br>

  <label>Checkbox:</label>
  <input type="checkbox" name="checkbox[]" value="valor1"> Opción 1
  <input type="checkbox" name="checkbox[]" value="valor2"> Opción 2
  <input type="checkbox" name="checkbox[]" value="valor3"> Opción 3<br>

  <input type="submit" value="Enviar">
</form>
  </body>
</html>
```

En resumen, la clase trata sobre cómo enviar información a un servidor utilizando formularios web, y cómo diferentes tipos de inputs envían diferentes tipos de información. Se muestra cómo enviar archivos grandes y cómo se puede utilizar la codificación multipart/form data para hacerlo. También menciona que las fechas pueden variar en formato dependiendo de la configuración regional de la computadora.

# Lección 22: Siguiente