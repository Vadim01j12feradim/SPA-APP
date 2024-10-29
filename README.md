# SPA-APP

Requerimientos
![Screenshot at 2024-10-27 12-19-39](https://github.com/user-attachments/assets/7448c3d5-4048-4377-84a6-6d862d86ae06)




1. Para descargar la aplicacion solo es necesario contar con el archivo docker-composer.yml que se encuentra aqui en el repositorio y ejecutar el siguiente comando en el[ directorio en donde se encuentra el archivo docker-composer.yml.
```
sudo docker-compose up --build 
```
2. Procura tener los puertos necesarios libreas por ejemplo el 8081 para la App, el 3306 para mysql, el 3001 para el socket y finalmente el 3000 para la API.
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
![Screenshot at 2024-10-29 16-11-36](https://github.com/user-attachments/assets/c69f44bd-f762-41d7-a867-83b423ffe8ad)

* Registro
![Screenshot at 2024-10-29 15-19-32](https://github.com/user-attachments/assets/57a26583-ee07-4ee4-8ea4-6df940406833)

* Dashboard.
![Screenshot at 2024-10-29 15-19-21](https://github.com/user-attachments/assets/e6981fee-655b-404a-b69c-63292daa4989)

* Eliminar
![Screenshot at 2024-10-29 15-17-18](https://github.com/user-attachments/assets/f0fe7e08-0ba9-4777-878b-1cc6c6b921fc)

* Actualizar
![Screenshot at 2024-10-29 15-17-26](https://github.com/user-attachments/assets/7e640164-e052-4caf-945b-7ebdb9674745)

* Agregar.
![Screenshot at 2024-10-29 15-18-56](https://github.com/user-attachments/assets/c7f240a0-061a-40d5-ab48-995640313a3b)
* Sin coches.
![Screenshot at 2024-10-29 15-05-13](https://github.com/user-attachments/assets/6cc181b4-df03-441c-a601-17abd535de9f)
* Responsive
![Screenshot at 2024-10-29 16-18-56](https://github.com/user-attachments/assets/495b78eb-e4fc-4ac0-8947-1e08ee28914e)
![Screenshot at 2024-10-29 16-19-40](https://github.com/user-attachments/assets/87bb1734-246e-4b63-8f50-76e145f04ebf)
![Screenshot at 2024-10-29 16-19-45](https://github.com/user-attachments/assets/2d97717b-a09a-4916-9eb7-4e4bf731083d)
* Imagenes del DockerHub
![Screenshot at 2024-10-29 16-10-37](https://github.com/user-attachments/assets/39e2c734-3b34-4a33-b594-4b4e9b74f3b8)
* Versioens de las imagenes
![Screenshot at 2024-10-29 16-10-46](https://github.com/user-attachments/assets/dfc6cfd7-4eb5-4f45-ab4f-dc9b2fb772c4)



# Construccion

* En caso de que desee recrear las imagenes y correr el proyecto puede ejecutar el script RESET.sh con los comandos siguientes en donde en el piero da permisos y el segudno para ejecucion.
  ```
  sudo chmod +x RESET.sh
  ```
  y para ejecutar

    ```
    ./RESET.sh
    ```
  











  

* 
