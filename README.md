![image](https://github.com/PFLC/624-crus-basicos-4d0lfo0117/assets/113808375/0a141a22-0e5c-4550-b3d5-c4659af3bd27)

# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD Create (Crear registros),Read bzw. Retrieve (Leer registros),Update (Actualizar registros),Delete bzw. Destroy (Borrar registros) simple. 

Y este resume las funciones requeridas por un usuario para crear y gestionar datos. Varios procesos de gestión de datos están basados en CRUD, en los que dichas operaciones están específicamente adaptadas a los requisitos del sistema y de usuario, ya sea para la gestión de bases de datos o para el uso de aplicaciones.

![image](https://github.com/PFLC/624-crus-basicos-4d0lfo0117/assets/113808375/9bac77b8-84ba-4944-9951-123356b85738)

Los frameworks CRUD facilitan el acceso al sistema de bases de datos y son utilizados tanto en el desarrollo como en el uso de aplicaciones. Existen numerosos frameworks con un concepto CRUD basados en diferentes lenguajes y plataformas.

![image](https://github.com/PFLC/624-crus-basicos-4d0lfo0117/assets/113808375/82c38236-eaf2-4d0f-be75-6706703117dc)

## Ventajas de CRUD

**Estandarización:** las operaciones CRUD interactúan con las aplicaciones de almacenamiento de datos en un solo espacio. De esta manera, la tarea de los desarrolladores se reduce significativamente.
**Experiencia de usuario mejorada:** los usuarios pueden crear, actualizar, leer y borrar datos de una aplicación sin problemas, lo que hace que la experiencia de usuario sea mucho más fácil de entender y satisfactoria.
**Facilidad de mantenimiento:** dado que la gestión de datos tiene protocolos bien establecidos, los sistemas CRUD no requieren un mantenimiento tan complicado. Es mucho más sencillo resolver problemas y actualizar la aplicación con esto.
La flexibilidad significa que los desarrolladores pueden ampliar y modificar componentes específicos de la aplicación sin que esto afecte al resto del sistema.
Proceso de desarrollo más simple: las operaciones CRUD permiten prácticas más efectivas y coherentes, lo que hace que el procedimiento de creación de aplicaciones sea mucho más rápido y fluido.
**Compatibilidad con múltiples tecnologías:** las operaciones CRUD se pueden aplicar a una variedad de tecnologías y bases de datos relacionales, incluidas GraphQL, API RESTful y NoSQL.
**Escalabilidad:** las aplicaciones se pueden escalar más fácilmente para adaptarse a las necesidades y datos del usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.


