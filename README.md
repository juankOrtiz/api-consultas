<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## Sobre el proyecto

API de consultas de una tabla de productos, creado con el Framework Laravel y la librería Sanctum para manejar la autenticación.
Los archivos importantes a tener en cuenta son:
- *routes/api.php*: manejo de las rutas de la API.
- *migrations*: migraciones de la base de datos, incluyendo el archivo de migración para la tabla de productos.
- *app/Http/Controllers/AuthController.php*: controlador para manejar los tokens de los usuarios que deseen acceder a las rutas protegidas por autenticación.
- *app/Http/Controllers/ProductController.php*: controlador para manejar las operaciones de las rutas de API para productos.