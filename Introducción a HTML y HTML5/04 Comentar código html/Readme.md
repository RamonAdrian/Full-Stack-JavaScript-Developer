# Lección 4: Comentarios

Cómo desarrolladores de páginas web, a veces necesitamos tener marcas o herramientas con las cuales podamos recordar en el tiempo o remover temporalmente contenido, esto con el fin de saber por qué hicimos algo.

Para esto usamos los comentarios, para remover o indicar cuál fue nuestra intención con un bloque de código

Crea un archivo ejemplo6.html

y copia y pega en dicho archivo el siguiente código:

```html
<!DOCTYPE html><!-- Doctype es una instrucción que le dice al navegador qué tipo de contenido tiene nuestro documento -->
<html> <!-- La etiqueta html es el elemento de nivel superior de un página web -->
<head> <!-- head le da información al navegador acerca de la estrucutura de nuestro documento html  -->
  <meta charset="UTF-8"> <!-- meta charset indica al navegador qué grupo de carácteres vamos a usar en nuestro documento -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- viewport le indica al navegador qué tamaño y escalabilidad va a manejar con nuestro contenido la primera vez que se carga y cómo se va a manejar la escala del zoom -->
  <meta http-equiv="X-UA-Compatible" content="ie=edge"> <!-- http-equiv="X-UA-Compatible" era una forma de decir en el pasado con qué versión de un navegador debería ser compatible nuestro contenido (muy usado en la era de internet explorer) -->
  <title>Document</title> <!-- La etiqueta dice al navegador qué texto se debe mostrar en el título de la pestaña donde estamos visualizando nuestra página -->
</head><!-- etiqueta de cierre de head -->
<body><!-- La etiqueta body es en donde pondremos todo el contenido visual de nuestra página -->
  <h1>Bienvenidos a mi primera página</h1><!-- Título del contenido -->
  <h2>Mi nombre es</h2> <!-- Subtítulo de mi contenido -->
  <p> Ramón Morales</p> <!-- Párrafo con mi nombre -->
  <h3>Acerca de mi:</h3> <!-- otro subtítulo -->
  <p>Soy desarrollador de software, me gradué de ingeniería de sistemas hace algunos años, llevo trabajando como desarrollador desde el 2006, pero la primera vez que hice código, fue en 1999 cuando estaba en octavo grado, es decir hace 20 años que programo</p> <!-- Párrafo con mi biografía -->
</body><!-- etiqueta de cierre del body -->
</html><!-- etiqueta de cierre de html -->
```

Ahora abre el archivo ejemplo6.html en un navegador

¿Qué pasa con el contenido envuelto en 
```html
<!-- -->
``` 
?

[Vamos a la lección número 4.1 de este tutorial >>>](../04-1%20Comentar%20código%20html/Readme.md)