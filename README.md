# Odoo

El archivo "docker-compose.yml" esta compuesto por 2 servicios:

El servicio 'db' utiliza la imagen de Postgres, y el servicio 'web' utiliza la imagen de Odoo.

En la terminal nos posicionamos en el directorio del proyecto en PyCharm y ejectutamos el comando ->

docker-compose up -d

Esto descarga las 2 imagenes antes mencionados.

![Captura de pantalla de 2023-06-01 10-53-05](https://github.com/davidmoralesluis/Odoo/assets/91198406/372e2b52-e208-4bd9-8e79-f214a1c447ea)


Cuanto se esta ejecutando, abrimos en el navegador 'http://localhost:8069'

![Captura de pantalla de 2023-06-01 11-00-42](https://github.com/davidmoralesluis/Odoo/assets/91198406/b569d984-5fef-4173-b73d-4895ad1d7401)

Si el puerto 5432 en tu ordenador ya esta ocupado se producira un conflicto al intentar ejecutar el contenedor. 
Lo podemos solucionar cambiando el puerto en el 'docker-compose.yml'.
