# Lección 12: Demos tamaño a la imagen

La etiquetas html tienen algo que se llama atributos o propiedades 
La etiqueta `<img>` por ejemplo tiene el atributo/propiedad width con este podemos darle tamaño a las imágenes, en este caso estaríamos dandole a la eqitqueta el ancho (en inglés **width**) de la imagen

de la siguiente manera

```html
<img width="100">
```

de este modo le estamos diciendo al navegador que muestre la imagen con un ancho de 100 píxeles y el alto de la imagen se modifica automáticamente para guardar las proporciones de la imagen

Creemos un archivo que se llame ejemplo12.html y peguemos el siguiente código:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  <main>
    <h1>Bienvenidos a mi primera página</h1>
    <h2>Mi nombre es</h2>
    <p> Ramón Morales</p>
  </main>
  <header>
  <h3>Acerca de mi:</h3>
  <p>Soy desarrollador de software, me gradué de ingeniería de sistemas hace algunos años, llevo trabajando como desarrollador desde el 2006, pero la primera vez que hice código, fue en 1999 cuando estaba en octavo grado, es decir hace 20 años que programo</p>
  </header>

  <img width="100" src="https://1.bp.blogspot.com/-_8zWqRJSgrA/XOonaO2T5tI/AAAAAAAAQ9c/E9-kwtsavc4EFYA2uycyU_Y5KNQIox8LACLcBGAs/s200/yzGVZJ4H.jpg">
  <header>
  <p>Ramón es una persona que trabaja en la industria del software</p>

  <p>Le encanta el lenguaje javascript y su framework frontend favorito es vueJS</p>
  </header>
  <p> Ramón está realizando un coding bootcamp online gratuito</p>

  <footer>
    Redes sociales de Ramón:
    <ul>
      <li>Twitter<a href="https://twitter.com/ramonmora">@ramonmora</a></li>
      <li>Instragram<a href="https://instagram.com/ramonmora">@ramonmora</a></li>
      <li>Facebook<a href="https://facebook.com/ramonmora">@ramonmora</a></li>
    </ul>

    <p>
      Email:
      <a href="mailto:ramonmora@gmail.com">
        ramonmora@gmail.com
      </a>
    </p>
    <p>
      Copyright 1999-2019 Ramón Morales. Todos los derechos reservados.
    </p>
  </footer>
</body>
</html>
```