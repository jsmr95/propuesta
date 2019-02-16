% LibrarYii
% José María Gallego Martel
% Curso 2018/19

# Descripción general del proyecto

La aplicación permitirá a un usuario poder informarse sobre cualquier libro o autor que esté en la base de datos y opinar sobre él. Podrá comentar sobre el libro, comentar un comentario, valorar un libro, ...

## Funcionalidad principal de la aplicación

La aplicación básicamente se centra en ofrecer a un lector (usuario) toda la información sobre un determinado ejemplar y/o autor, y aparte de ello, comentar mediante una feed, que le ha parecido, si lo recomienda o no, tendrá un mecanismo por el cuál, aparecerá en la feed automáticamente aquel libro que un usuario haya terminado de leer.

Podrá acceder a una vista personalizado de cualquier libro, comentar que le ha parecido tras leerlo, valorarlo, comentar otro comentario de otro lector, marcarlo como favorito, un usuario podrá modificar su propio perfil, buscar libros por titulo y categoria, ver todos los usuarios registrados, que libros tienen marcados como favoritos,...

Con respecto a los autores, tan solo podremos acceder a su información. Los usuarios normales, no podrán insertar, eliminar, modificar ejemplares y autores, ya que podrían generar malas acciones, estas opciones se les otorgará a los usuarios administradores, que serán los usuarios con mas privilegios sobre la aplicación.

Un administrador podrá otorgar permisos a otro usuario, tambien quitarselos, podrá eliminar cuentas de usuarios conflictivos, banearlos, eliminar comentarios fuera de contexto,...

## Objetivos generales

* Gestionar el registro y logueo de usuarios.
* Gestionar la insercción, modificación y borrado de libros y autores por un usuario 'admin'.
* Gestionar los comentarios de cualquier usuario.
* Gestionar las valoraciones de los usuarios.
* Un administrador podrá modificar los permisos de un usuario que no sea 'admin'.
* Gestionar la subida de archivos como por ejemplo el avatar de un usuario.
* Cada usuario podrá gestionar su feed personal, sus 'Lryb' que llamaremos (haciendo similitud a los tweets en Twitter)

# Elemento de innovación

-Amazon S3 o Amazon Simple Storage Service, como servicio de almacenamiento y protección de datos.

-Uso de paquetes como Yii2-Social y otros para ayudarme a que se parezca más una red social.
