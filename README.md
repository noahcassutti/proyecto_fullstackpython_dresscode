

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

¡Espero que este README te ayude a comprender la parte de back-end de tu proyecto! Asegúrate de personalizarlo con la información específica de tu proyecto y las instrucciones detalladas según sea necesario.# trabajointegradorgrup1
Las reuniones en su mayoria y los presentes van a estar colocados en la wiki con la division de tareas.

Claro, aquí tienes un ejemplo de cómo podría ser un archivo README para el front-end de un sitio web llamado "DressCode" que se dedica a la venta de ropa para programadores. El sitio web incluye las páginas de inicio (index), productos, login, registro y "Quiénes Somos", además de un archivo JavaScript para gestionar el inicio de sesión y el registro de usuarios:

Entendido, gracias por la aclaración. Aquí tienes una versión actualizada de la estructura de carpetas y un README que refleja la estructura que mencionaste:

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

## Personalización
Puedes personalizar este front-end según tus necesidades. Asegúrate de tener el back-end adecuado para gestionar los usuarios y los productos. Además, considera implementar un carrito de compras y un proceso de pago si deseas habilitar la funcionalidad de compra en línea.

## Créditos
Este front-end de DressCode fue desarrollado por [Tu Nombre] y se basa en tecnologías web estándar como HTML, CSS y JavaScript.

## Contacto
Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto con nosotros en [tu@email.com].

¡Esperamos que disfrutes de tu experiencia en DressCode!
Para ingresar al login tiene que colocar:


## IMPORTANTE!!!
## FRONT

Para ingresar con el login 

Correo: Juan@gmail.com
Contrasena: 1234!Milan

## BACK

Para que se conecte a la bd tiene que colocar en el modulo conexion, la contrasena de su bd



