# SPA-APP

Requerimientos
![Screenshot at 2024-10-27 12-19-39](https://github.com/user-attachments/assets/7448c3d5-4048-4377-84a6-6d862d86ae06)




1. Para descargar la aplicacion solo es necesario contar con el archivo docker-composer.yml que se encuentra aqui en el repositorio y ejecutar el siguiente comando en el[ directorio en donde se encuentra el archivo docker-composer.yml.
```
sudo docker-compose up --build 
```
2. En caso de que no se cuente con docker instalado se deve descargar desde linux con elsiguiente comando
```
sudo snap install docker
```
Para Windeos segui la documentacion sugerida en https://www.docker.com/

3. Para simular un vehiculo en movimiento se cuenta con un script con nombre client.js que permitira hacer una simulacion de cmovimiento random para un vehiculo en especifico, este archivo se encuentra en la carpeta client y lo puedes ejecutar desde afuera del contenedor configurando el id del vehiculo unicamente
