<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

Hoy comparto un proyecto que hize en Laravel sobre una Cartelera de Cine. En Principio solo iba a ponerle 2 vistas diferentes ( la que veia el administrador que añadia peliculas , eliminabas usuarios y demas funciones ) y la del usuario que compraba entradas. Me gusto tanto el proyecto que le puse muchisimas funciones como un panel HTML de administrador novedoso, y demas funciones que veran. Tambien tiene varios addons como parte de contacto que avisa al email real que configures y muchas cositas más. Como algo que me falto y no pude conseguir seria ponerle un generador de factura y que se imprimiera pero no tuve tiempo :D. Disfruten el codigo.


![image](https://user-images.githubusercontent.com/17550010/157157390-e6b21a7a-ea7c-4e1b-9271-c23970d51e68.png)




Cualquier duda contactarme :D



<H1> INSTALACION </H1>

Para importarlo es priotario tener Composer y un LAAMP( instalado con Apache y MYSQL) logicamente ya sea XAAMP o AAMPS. Recomendable que la version de PHP no sea 8 para arriba , sino tendreis que actualizar en cmd el composer. ( Composer update)

Segundo importar la base de datos

Y tercero en el archivo .env del proyecto laravel dejo por defecto root como user de la Base de Datos y contraseña en blanco. El nombre de la base de datos es "cinealfredo" pero eso ya es opcional cambiarla , pero si cambiais acordad que tambien hay que hacerlo en el sql de la base de datos.


![image](https://user-images.githubusercontent.com/17550010/157157452-82850157-7aa9-456e-ab4d-b2568bd98154.png)



Por ultimo , en la carpeta del proyecto ejecutar "**composer install**" y luego "**php artisan key:generate**" para generar nuevas claves.


Listo , ejecutarlo con "**php artisan serve**" y deberian visualiarlo en 127.0.0.1:8000

Las claves de acceso son:

**Cuentas con permisos de administrador
**
admin@alfrredo.com
Contraseña: alfredo2020

secundaria@live.com
Contraseña: hola12345


<h3>Imágenes del proyecto</h3>


![image](https://user-images.githubusercontent.com/17550010/157157556-e7e8c0c9-bfa4-4c11-a068-b3711e418c40.png)
![image](https://user-images.githubusercontent.com/17550010/157157569-9520e3d0-7b44-4023-9df1-274b588a714f.png)
![image](https://user-images.githubusercontent.com/17550010/157157601-89496af2-4e91-49a0-869b-19895ac55530.png)
![image](https://user-images.githubusercontent.com/17550010/157157762-90bd5803-c32e-47b5-a657-67dade46b3e9.png)






