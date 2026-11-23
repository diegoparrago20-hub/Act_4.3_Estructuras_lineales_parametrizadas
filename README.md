# Act_4.3_Estructuras_lineales_parametrizadas
Este proyecto consiste en el desarrollo de una aplicación de escritorio para gestionar trabajos de una biblioteca mediante una estructura de datos de tipo Lista Circular. Permite registrar, insertar, eliminar, consultar y navegar entre libros, revistas y artículos, utilizando una interfaz gráfica y aplicando conceptos de programación genérica, herencia y polimorfismo en Java.

## Equipo #2
CONTRERAS RODRIGUEZ JANIS ISABEL

LIRA DOMINGUEZ BRYANT

PARRA GONZALEZ DIEGO ALBERTO

# Objetivo
Desarrollar e implementar una Lista Circular genérica que permita administrar diferentes trabajos bibliográficos, realizando operaciones de inserción, eliminación, búsqueda y navegación entre los elementos de manera continua.

# Tecnologías utilizadas
Java
Java Swing
Apache NetBeans
Git y GitHub

# Características
Registro de libros, revistas y artículos.

Captura de datos generales y específicos de cada publicación.

Implementación de una Lista Circular enlazada.

Inserción de publicaciones al inicio y al final.

Inserción de publicaciones por posición.

Eliminación de publicaciones por posición o título.

Navegación al siguiente y anterior elemento.

Consulta del elemento actual.

Visualización de todos los elementos de la lista.

Opción para vaciar la lista circular.

Validación de los datos ingresados.

Interfaz gráfica para facilitar la administración de las publicaciones.

# Estructura del proyecto
El proyecto está organizado mediante clases que permiten administrar los diferentes tipos de publicaciones:

Trabajo: clase base con los atributos generales de las publicaciones.

Libro: clase heredada que contiene el número de páginas.

Revista: clase heredada que contiene el número de edición.

Articulo: clase heredada que contiene el nombre de la conferencia.

ListaCircularTrabajos: administra las publicaciones mediante nodos enlazados de forma circular.

Clase Nodo: almacena cada publicación y mantiene las conexiones entre los elementos.

Interfaz gráfica: permite capturar información y ejecutar las operaciones de la lista circular.

# Interfaz gráfica
La aplicación cuenta con una interfaz desarrollada en Java Swing mediante el GUI Builder de NetBeans.

Desde ella se pueden seleccionar los tipos de publicaciones, ingresar sus datos y utilizar los botones para insertar al inicio, insertar al final, insertar por posición, eliminar, navegar entre elementos, mostrar todos los trabajos y vaciar la lista.

La información se presenta en un área de visualización donde se identifica la cabeza de la lista y el elemento actual seleccionado, facilitando la comprensión del recorrido circular.
