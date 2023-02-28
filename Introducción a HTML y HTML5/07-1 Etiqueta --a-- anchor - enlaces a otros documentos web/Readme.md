# Lección 14: Revisemos otros atributos de la etiqueta anchor `<a>`


¿Te diste cuenta que usamos el atributo `href` de `<a>` ?

En ese atributo ponemos la dirección web de las páginas u otros documentos html a los cuales queremos enlazar nuestra página.

Sin embargo, no queremos que nuestros visitantes abandonen nuestra página cuando den click en uno de sus enlaces. Para evitar eso, vamos a usar el atributo `target`

crea un archivo ejemplo14.html y pega el código que te compartiremos a continuación:

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
  <a target="_blank" href="https://www.facebook.com/">
  <img width="100" src="https://1.bp.blogspot.com/-_8zWqRJSgrA/XOonaO2T5tI/AAAAAAAAQ9c/E9-kwtsavc4EFYA2uycyU_Y5KNQIox8LACLcBGAs/s200/yzGVZJ4H.jpg">
  </a>
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

Ahora da click nuevamente en la imagen de tu página.

¿Notaste la diferencia? 

El atributo `target="_blank"` le dice al navegador que abra el vínculo en una nueva pestaña.

[Vamos a la lección número 15 de este tutorial >>>](leccion15.md)