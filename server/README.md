## Backend
### Configuracion Inicial
1. Iniciar Laravel en server/
    ```
    sudo apt install php-xml
    composer create-project laravel/laravel .
    ```
2. Instalar dependencias
    ```
    composer install
    ```
3. Iniciar server
    ```
    php artisan serve
    ```
4. Configuracion de .env con info de la base de datos

5. Ejecutar las migraciones que están en database/migrations/ para crear o modificar tablas en la base de datos según las clases PHP que Laravel usa para definirlas. Se modifcara despues segun las necesidades.
    ```
    php artisan migrate
    ```