# GEA Gestor Escolar Academico

Tema de WordPress para gestión académica, convertido desde maquetas HTML estáticas con integración a una base de datos MySQL local.

### Arquitectura del Proyecto
*   **Directorio raíz:** `GEA-main/`
*   **Empaquetado del tema:** `gea-theme.zip`
*   **Documentación base:** `README.md`
*   **Entorno:** Localhost (LocalWP / XAMPP) con motor PHP y MySQL.

### Despliegue y Configuración

1. **Gestión de Base de Datos:** Importar el volcado SQL preexistente en tu servidor MySQL local.
2. **Instalación del Tema:** Extraer el contenido de `gea-theme.zip` o mover la carpeta `GEA-main/` hacia el directorio `/wp-content/themes/` de tu instalación local de WordPress[cite: 1].
3. **Conexión de Credenciales:** Asegurar el enlace de la base de datos configurando el archivo `wp-config.php` en la raíz de WordPress:

```php
// Credenciales estándar para entorno local
define( 'DB_NAME',     'nombre_bd_gea' );
define( 'DB_USER',     'root' );
define( 'DB_PASSWORD', '' );
define( 'DB_HOST',     'localhost' );
