# Lección 13: Seguimos trabajando con formularios

Esta es una explicación sobre formularios en **HTML** y cómo se manejan los datos que se envían a través de ellos. En primer lugar, se menciona que hay varios tipos de datos que se pueden enviar a través de un formulario, como texto **HTML**, **XHTML**, **CPH**, imágenes y otros elementos.

Luego, se muestra cómo se manejan los parámetros de la web cuando se envían datos a través de un formulario. El parámetro referer se utiliza para mostrar de dónde viene una persona que navegó a una página en particular. También se mencionan otros parámetros, como la **URL** y el atributo **Method**, que se utiliza para especificar si los datos se envían a través del método **GET** o **POST**.

El método **GET** envía los datos a través de la **URL**, mientras que el método POST los envía a través de un atributo llamado **Body**. El método **POST** se utiliza comúnmente para crear recursos, como usuarios, y que los datos se envían en un atributo llamado **payload**.

```html
<!DOCTYPE html>
<html>
<head>
	<title>Ejemplo Formulario con POST y GET</title>
</head>
<body>
	<h1>Formulario con método POST</h1>
	<form action="http://localhost" method="POST" enctype="multipart/form-data">
		<label for="nombre">Nombre:</label>
		<input type="text" name="nombre" id="nombre">
		<br>
		<label for="apellido">Apellido:</label>
		<input type="text" name="apellido" id="apellido">
		<br>
		<label for="archivo">Archivo:</label>
		<input type="file" name="archivo" id="archivo">
		<br>
		<input type="submit" value="Enviar">
	</form>

	<h1>Formulario con método GET</h1>
	<form action="http://localhost" method="GET">
		<label for="busqueda">Búsqueda:</label>
		<input type="text" name="busqueda" id="busqueda">
		<br>
		<input type="submit" value="Buscar">
	</form>
</body>
</html>
```

El atributo enctype, que se utiliza para especificar la codificación de los datos que se envían a través de un formulario. Por defecto, el valor es **url-encode**, pero hay otros valores que se pueden utilizar, como **text/plain** o **application/x-www-form-urlencoded**. Se muestra cómo cambiar el valor de este atributo y cómo afecta a los datos que se envían.

>Es importante tener en cuenta que la codificación **multipart/form-data** se utiliza sólo cuando se envían archivos a través de un formulario. Para los formularios que sólo envían texto, se utiliza la codificación por defecto, **application/x-www-form-urlencoded**.

En resumen, es una explicación sobre cómo se manejan los datos que se envían a través de un formulario en **HTML**, incluyendo los parámetros de la web, los métodos **GET** y **POST**, y el atributo **enctype**.

[Vamos a la lección número 14 de este tutorial >>>](../14%20Formularios%20parte%203/Readme.md)