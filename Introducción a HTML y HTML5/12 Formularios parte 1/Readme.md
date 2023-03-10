# Lección 12: Empecemos a trabajar con formularios

En este fragmento de código, se está hablando sobre formularios HTML y sus atributos. Se menciona que un formulario es un elemento que no tiene visibilidad por sí mismo y que se usa para enviar información a través de inputs. El atributo acción es importante, ya que indica la dirección a la que se enviarán los datos del formulario. Además, se muestra un ejemplo de cómo enviar datos a través de formularios y cómo estos datos son enviados a la página de destino como parámetros de URL.


Vamos a ver como esta estructurado un formulario en html, con el siguiente código:

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Formularios</title>
</head>

<body>
  <form>
    <label for="nombre">nombre</label>
    <input type="text" name="nombre" id="nombre" />
    <br>
    <label for="apellido">apellido</label>
    <input type="text" name="apellido" id="apellido" />
    <button type="submit">Enviar</button>
  </form>
</body>

</html>
```

[Vamos a la lección número 13 de este tutorial >>>](../13%20Formularios%20parte%202/Readme.md)