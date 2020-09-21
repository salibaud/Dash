# Dash
## Sitio creado para visualización de reportes

El sitio es una fusion de dos paquetes bastante buenos para python. Consiste en utilizar el paquete flask para la creacion de reportes o dashboard, su utilidad se basa en que no se necesita pagar mas que un servidor y una base de datos para empezar a usar (no requiere licencias). 

Los paquetes utilizados son:

* Dash es un paquete que contiene un marco (framework) de Python para crear aplicaciones web analíticas. No se requiere JavaScript (lo mejor!).
* Flask-Login proporciona administración de sesiones de usuario para Flask. Maneja las tareas comunes de iniciar sesión, cerrar sesión y recordar las sesiones de sus usuarios durante períodos de tiempo prolongados.

## Diseño.

El diseño de este "portal de reporte" se basa en el siguiente diseño:

https://dash-gallery.plotly.host/dash-salesforce-crm/

![alt text](https://dash-gallery.plotly.host/Manager/apps_data/dash-salesforce-crm/thumbnail_154dcf0e-cb59-11e9-8925-0242ac11004a.png)

Sin emabrgo se modifico el head para acoplar al paquete de flask login (en particular el creado por Rafael miquelino), adicionalmente se quitaron las conecciones a salesforce para que valla a buscar directamente desde un .csv (se puede agregar cualquier datos desde api pero para efectos de ejemplo solo toma un csv)

https://github.com/RafaelMiquelino/dash-flask-login

![alt text](https://user-images.githubusercontent.com/31367475/47422577-4f761500-d759-11e8-90c2-b70a79fcd610.gif)

Al combinar estos dos paquetes se genera una visualizacion simple y directa.

Entrada

![alt text](https://github.com/salibaud/Dash/blob/master/assets/Entrada.PNG)



Vista de dashboard



Registro de visitas



Ahi un dashboard que permite ver informacion detallada con un boton de descarga de los datos.

## Mejoras:
- En el apartado de administracion agregare la opcion para ver usuarios crear y elimina. Tambien asignar roles.
- Agregar nuevos graficos y formato simple para creacion de paginas.
