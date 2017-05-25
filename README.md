# testSymfony

El siguiente proyecto fue desarrollado como una prueba tecnica para medir los conocimientos de Symfony.

# Instalación

1. Para instalar la aplicación se debe copiar la aplicación a la carpeta web del servidor Apache previamente instalado.

2. Configurar los parametros de la base de datos en el archivo "parameters.yml" de la carpeta "app/config".

3. Ejecutar el comando "php bin/console doctrine:database:create" para generar la base de datos en el motor de base de datos correspondiente.

4. Ejecutar el comando "php bin/console doctrine:generate:entities ProductosBundle" para compilar las Entidades de la aplicación.

5. Luego ejecutar el comando "php bin/console doctrine:schema:update --force" para generar el mapeo de la aplicación en la base de datos.

6. Ejecutar el archivo SQL "ScriptsTestSQL.sql" para poblar la base de datos y ejecutar la aplicación.

7. Ejecutar el comando "php bin/console server:run" para ejecutar la aplicación en ambiente productivo.

8. Ir a la ruta "{direción_server}/productos" para visualizar la aplicación.
