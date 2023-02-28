# Lección 11: Pongamosle imágenes a nuestra página

La etiqueta `<img>` nos sirve para poner imágenes en nuestra página

En la página que llevamos hasta el momento, vamos a insertar una imagen desde nuestras redes sociales

Creemos un archivo que se llame ejemplo11.html y peguemos el siguiente código

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

  <img src="https://media.licdn.com/dms/image/C5603AQHd8Lkzi2x7ow/profile-displayphoto-shrink_800_800/0/1661831801868?e=1683158400&amp;v=beta&amp;t=OvFQo-u6qrfSGheP0uiEGcUp4N_-URSnE4nTc1F0NjY" loading="lazy" alt="imagen de perfil" id="ember352" class="lazy-image imgedit-profile-photo-frame-viewer__target-image ember-view">
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
[Vamos a la lección número 12 de este tutorial >>>](leccion12.md)