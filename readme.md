# Introducción a Bootstrap
## ¿Qué es bootstrap?

Contruir sitios responsivos (adaptable adiversos tamanños depantalla por medio de clases pre-hechas css)

## ¿Por qué es importante entender que es bootstrap?

Cuando nosotras hacemos css, tenemos qué tener acceso a el HTML donde se van a utilizar, y para que nuestras sentencias que indica como cambiar propiedades como:

``background-collor:red;``

Debemos utilizar un selector (eleemento, class, id), por lo tanto, para usar bootstrap se va poder utilizar esos mismos selectores, solo que ya estaran predefinidos

## Instalación

Para instalar bootstrap, lo que realmente vamos hacer es lo mismo que se hace con todos los recursos del mismo tipo, por ejemplo:
Para ligar un archivo de CSS, ocupamos:
``<link rel="stylesheet" href="style.css">``
En este caso, ligaremos con un archivo en internet:

``<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">``

Bootstrap es uno de un montón de fragmentos de CSS que podemos ocupar. Todos se pueden traer por medio de un CDN e importar con un link a nuestro archivo.

Por otro lado, bootstrap requiere de JS para hacer componentes dinamicos como el carrusel.

Por lo tanto voy a necesitar ese link en mi archivo, solo que este link va tener codigo de JS, por lo tanto como cualquier link de JS deberá ir al final de mi body, arriba de la etiqueta de cierre.

<script src="archivo.js"></script>

En este caso la linea para ligarlo contiene el link al archivo de JS, se pone al final para que una vez se cargaron todos los elementos de HTML, ahota si lo empecemos a gacer dinamicos, por que si ponemos el SCRIPT arriba, y el HTML se tarda en cargar, podriamos estar intentando hacer dinamico un elemento que aun no existe.


``<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>``

Con esto ya tenemos nuestro sitio listo para usar bootstrap.