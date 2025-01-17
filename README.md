<h1>-----APLICACION LITERALURA-----</h1>
<h2>Caracteristicas</h2>
<p>Aplicación de consola que permite buscar especificaciones sobre libros, esto gracias al consumo de la API GUTENDEX <code>https://gutendex.com </code> 
esta aplicacion lleva el almacenamiento de datos en una base de datos PostgreSQL</p>
<h2>Funcionalidades</h2>
<p>1 - Buscar libro por título.
Muestra y almacena los datos de un libro determinado:
<ul>
  <li>Solicita el título de un libro y lo busca en la API de Gutendex.</li>
  <li>Devuelve los datos encontrados y los almacena en la base de datos.</li>
  <li>Si el libro no existe devuelve un mensaje de error.</li>
</ul></p>
 <p>2 - Listar todos los libros registrados.
Muestra una lista de todos los libros que han sido registrados. </p> 
<p>
  3 - Listar autores registrados.
Muestra una lista de los autores que han sido registrados en la base de datos y los libros asociados a cada uno de ellos.
</p>
<p>
  4 - Listar autores vivos en un determinado año.
Muestra los nombres de los autores que hayan estado vivos en determinado año.
</p>
<p>
  5 - Listar libros por idioma.
Muestra una lista de los libros registrados que hayan sido publicados en determinado idioma.
</p>
<p>
  6 - Top 10 de los libros más descargados.
Muestra una lista con los 10 libros registrados con mayor número de descargas.
</p>
<h2>Tecnologias utilizadas</h2>
<p>
  <ul>
    <li>Java 17</li>
    <li>Spring Boot</li>
    <li>PostgresSQL</li>
    <li>Jackson</li>
    <li>JPA</li>
    <li>PGAdmin</li>
  </ul>
</p>
<h2>Como utilizarlo</h2>
<p>
  1.Clonar repositorio <code>git clone </code>
  2.Crear la base de datos en Postgresql
  <ul>
    <li>Usando PGAdmin, crear una base de datos de nombre</li>
    <li>Configurar el archivo application.properties del proyecto según tus credenciales de PostgreSQL:</li>
  </ul>
  3.Ejecutar la aplicación
  
</p>



