# SPA-APP

Requerimientos
![Screenshot at 2024-10-27 12-19-39](https://github.com/user-attachments/assets/7448c3d5-4048-4377-84a6-6d862d86ae06)




1. Para descargar la aplicacion solo es necesario contar con el archivo docker-composer.yml que se encuentra aqui en el repositorio y ejecutar el siguiente comando en el[ directorio en donde se encuentra el archivo docker-composer.yml.
```
sudo docker-compose up --build 
```
2. Una vez cargado abre en tu navegador en la direccion http://localhost:8081, se pasiente y espera a que cargue el proyecto puede llegar a tardar algunos segundos dependiendo de multiples factores.
3. En caso de que no se cuente con docker instalado se deve descargar desde linux con elsiguiente comando
```
sudo snap install docker
```
Para Windeos segui la documentacion sugerida en https://www.docker.com/

4. Para simular un vehiculo en movimiento se cuenta con un script con nombre client.js que permitira hacer una simulacion de cmovimiento random para un vehiculo en especifico, este archivo se encuentra en la carpeta Agent y lo puedes ejecutar desde afuera del contenedor configurando el id del vehiculo unicamente en el parametro del axios con get.
5. La razon por la que se crearon varias imagenes y no solo una es debido a la escalabilidad y organizacion ya que esi es mas facil dar mantenimiento en actualizaciones futuras en el caso de que fuese un proyecto real.

# Vistas
* Login

* Registro

* Dashboard.

* Eliminar

* Actualizar

* Agregar.

* 
