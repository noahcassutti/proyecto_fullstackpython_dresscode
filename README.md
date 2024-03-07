

# Back-End del Proyecto DRESSCODE

Este README proporciona una visión general de la parte de back-end del proyecto y detalla cómo funciona, los componentes clave y cómo configurar y ejecutar la aplicación.

## Contenido

1. [Introducción](#introducción)
2. [Requisitos](#requisitos)
3. [Configuración](#configuración)
4. [Base de Datos](#base-de-datos)
5. [Ejecución](#ejecución)
6. [Funcionalidad](#funcionalidad)
7. [Contribución](#contribución)

## Introducción

El back-end de este proyecto es una parte fundamental que se encarga de gestionar la lógica empresarial, la base de datos y las conexiones con el front-end. Proporciona la funcionalidad para administrar productos, usuarios y otras operaciones relacionadas con la tienda virtual.

## Requisitos

- Python 3.x
- MySQL Server
- Bibliotecas de Python: `mysql.connector`

## Configuración

1. Asegúrate de tener Python instalado. Puedes descargarlo desde [python.org](https://www.python.org/downloads/).

2. Configura un servidor MySQL y crea la base de datos `tienda_virtual` utilizando el script proporcionado.

3. Instala la biblioteca `mysql.connector` utilizando pip:

   ```
   pip install mysql-connector-python
   ```

4. Configura la conexión a la base de datos en el archivo `Conexion.py`. Asegúrate de especificar la dirección del servidor, nombre de usuario y contraseña.

## Base de Datos

La base de datos utiliza MySQL y consta de varias tablas, como `administrador`, `categoria`, `detalle_transaccion`, `productos`, `proveedores`, `transacciones`, y `usuario`. Puedes encontrar la estructura de la base de datos y datos de ejemplo en el script de creación de la base de datos.

## Ejecución

1. Ejecuta el script de Python principal:

   ```
   python main.py
   ```

2. Se mostrará un menú interactivo que te permitirá administrar productos y realizar otras operaciones relacionadas con la tienda virtual.

## Funcionalidad

- Cargar productos: Permite agregar nuevos productos a la base de datos.
- Eliminar productos: Elimina productos existentes de la base de datos.
- Actualizar productos: Modifica los detalles de los productos existentes.
- Mostrar productos: Muestra la lista de productos disponibles en la tienda virtual.

## Contribución

Si deseas contribuir a este proyecto, siéntete libre de hacerlo. Puedes crear solicitudes de extracción con nuevas características, correcciones de errores o mejoras en el código. También se pueden abrir problemas para discutir problemas o sugerir mejoras.

Las reuniones en su mayoria y los presentes van a estar colocados en la wiki con la division de tareas.
El sitio web incluye las páginas de inicio (index), productos, login, registro y "Quiénes Somos", además de un archivo JavaScript para gestionar el inicio de sesión y el registro de usuarios:

# README para el Front-end de DressCode

## Descripción del Proyecto
DressCode es una tienda en línea de ropa especialmente diseñada para programadores. Nuestro sitio web ofrece una variedad de camisetas, sudaderas, gorras y otros productos relacionados con la programación y la informática. Este README se enfoca en la estructura de carpetas y archivos del front-end del sitio.

## Estructura de Carpetas y Archivos

- **dresscode_indexes:**
  - **index.html:** La página de inicio que muestra una introducción al sitio y enlaces a otras secciones.
  - **productos.html:** La página de productos que enumera los artículos disponibles para la venta.
  - **quienes_somos.html:** La página "Quiénes Somos" que proporciona información sobre nuestra empresa y nuestra misión.
  - **login.html:** La página de inicio de sesión para los usuarios registrados.
- **css:**
  - **index.css:** Estilos CSS para la página de inicio.
  - **productos.css:** Estilos CSS para la página de productos.
  - **quienes_somos.css:** Estilos CSS para la página "Quiénes Somos".
  - **login.css:** Estilos CSS para la página de inicio de sesión.
- **js:**
  - **login_registro.js:** El archivo JavaScript que gestiona la funcionalidad de inicio de sesión y registro de usuarios.

## Requisitos
Asegúrate de tener instalado un navegador web actualizado para ver y probar el sitio.

## Instrucciones de Uso

1. Clona o descarga este repositorio en tu computadora.
2. Abre los archivos HTML en tu navegador para acceder a las diferentes secciones del sitio.
3. Utiliza las páginas de "Login" y "Registro" para gestionar tu cuenta de usuario.


## Créditos
Este front-end de DressCode fue desarrollado por el grupo de tecnicatura del ispc y se basa en tecnologías web estándar como HTML, CSS, JavaScript y Bootstrap


¡Esperamos que disfrutes de tu experiencia en DressCode!
Para ingresar al login tiene que colocar:


## IMPORTANTE!!!
## FRONT

Para ingresar con el login 

Correo: Juan@gmail.com
Contrasena: 1234!Milan

## BACK

Para que se conecte a la bd tiene que colocar en el modulo conexion, la contrasena de su bd

Por supuesto, aquí tienes una lista para incluir en el README de tu proyecto que resalta los aspectos clave de la gestión del proyecto que mencionaste:

# Gestión del Proyecto

A continuación, se detallan las actividades clave de gestión del proyecto que realizamos durante el desarrollo, organizado en dos sprints, con un equipo de 7 integrantes:

- Definición de Issues:
  - Definimos issues a partir de las historias de usuario o tareas correspondientes.
  - Asignamos las issues a los miembros del equipo responsables de completarlas.

- Esquema de Branching:
  - Creamos un esquema de branching que permitió una gestión eficiente de las ramas de desarrollo, asegurando la colaboración y la integración continua.

- Milestones:
  - Creamos un milestone correspondiente a cada uno de los dos sprints, lo que nos permitió planificar y rastrear el progreso de manera efectiva.

- Kanban del Proyecto:
  - Mantuvimos actualizado un tablero Kanban del proyecto con las issues, su estado y su asignación, lo que facilitó la visualización del flujo de trabajo y la priorización de tareas.

- Documentación de Ceremonias:
  - Documentamos las ceremonias de planning, review y retrospective, lo que incluyó objetivos, discusiones, decisiones y acciones tomadas en cada reunión.

- IEEE830:
  - Mantuvimos actualizado el documento del proyecto siguiendo las directrices de IEEE830, lo que incluyó descripciones de los requisitos, la arquitectura y otros aspectos técnicos del proyecto.

- README:
  - Documentamos el proyecto mediante el archivo README, proporcionando una visión general del proyecto, estructura de carpetas, instrucciones de uso y contactos.

- WIKI:
  - Documentamos de manera más detallada el proyecto mediante la creación y actualización de una WIKI, que incluyó información técnica, guías de instalación, configuración y otros recursos útiles.

Estas prácticas de gestión del proyecto nos permitieron mantener un flujo de trabajo organizado y efectivo, garantizando un desarrollo exitoso y colaborativo en equipo.

## ES POSIBLE INGRESAR A ELLO SALIENDO DEL FORK ENTRANDO A LA DEBIDA ORGANIZACION CREADA, VAN A PODER VISUALIZARLO

# FINAL (PENDIENTE)
-Realizar el release en Github.
-Realizar el despliegue en Github Pages.



