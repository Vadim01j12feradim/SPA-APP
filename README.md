# 🌐 SPA-APP

![App Screenshot](https://github.com/user-attachments/assets/7448c3d5-4048-4377-84a6-6d862d86ae06)

Single Page Application (SPA) project with Dockerized deployment, designed for scalability and efficient organization. This README provides step-by-step instructions for setting up, running, and simulating the app with Docker.

---

## ⚙️ Requirements

To download and launch this application, ensure you have the `docker-compose.yml` file available in this repository. Follow these steps:

1. **Run Docker Compose**  
   Execute the following command in the directory containing `docker-compose.yml`:
   ```bash
   sudo docker-compose up --build 
   ```
2. Procura tener los puertos necesarios libres:

- **8081** para la App
- **3306** para MySQL
- **3001** para el Socket
- **3000** para la API

3. Una vez cargado, abre en tu navegador en la dirección [http://localhost:8081](http://localhost:8081). Ten paciencia y espera a que cargue el proyecto; puede tardar algunos segundos dependiendo de múltiples factores.

4. En caso de que no se cuente con Docker instalado, se debe descargar en Linux con el siguiente comando:
   ```bash
   sudo snap install docker
   ```


5. Para **Windows**, sigue la documentación sugerida en [Docker.com](https://www.docker.com/).

6. Para simular un vehículo en movimiento, utiliza el script llamado `client.js`, que permite hacer una simulación de movimiento aleatorio para un vehículo específico. Este archivo se encuentra en la carpeta `Agent`, y puedes ejecutarlo desde fuera del contenedor configurando únicamente el **ID del vehículo** en el parámetro de `axios` con una petición GET.

7. La razón por la que se crearon varias imágenes y no solo una es debido a la **escalabilidad y organización**. Esto facilita el mantenimiento y futuras actualizaciones en caso de que el proyecto evolucione.

# 📸 Vistas

Explore las distintas vistas de la aplicación:

### 🔑 Login
![Login Screenshot](https://github.com/user-attachments/assets/c69f44bd-f762-41d7-a867-83b423ffe8ad)

### 📝 Registro
![Registro Screenshot](https://github.com/user-attachments/assets/57a26583-ee07-4ee4-8ea4-6df940406833)

### 📊 Dashboard
![Dashboard Screenshot](https://github.com/user-attachments/assets/e6981fee-655b-404a-b69c-63292daa4989)

### ❌ Eliminar
![Eliminar Screenshot](https://github.com/user-attachments/assets/f0fe7e08-0ba9-4777-878b-1cc6c6b921fc)

### 🔄 Actualizar
![Actualizar Screenshot](https://github.com/user-attachments/assets/7e640164-e052-4caf-945b-7ebdb9674745)

### ➕ Agregar
![Agregar Screenshot](https://github.com/user-attachments/assets/c7f240a0-061a-40d5-ab48-995640313a3b)

### 🚫 Sin coches
![Sin Coches Screenshot](https://github.com/user-attachments/assets/6cc181b4-df03-441c-a601-17abd535de9f)

### 📱 Responsive
Responsive view across devices:
- ![Responsive Screenshot 1](https://github.com/user-attachments/assets/495b78eb-e4fc-4ac0-8947-1e08ee28914e)
- ![Responsive Screenshot 2](https://github.com/user-attachments/assets/87bb1734-246e-4b63-8f50-76e145f04ebf)
- ![Responsive Screenshot 3](https://github.com/user-attachments/assets/2d97717b-a09a-4916-9eb7-4e4bf731083d)

### 🐳 Imágenes de DockerHub
![DockerHub Screenshot](https://github.com/user-attachments/assets/39e2c734-3b34-4a33-b594-4b4e9b74f3b8)

### 🔢 Versiones de las imágenes
![Versiones de las Imágenes Screenshot](https://github.com/user-attachments/assets/dfc6cfd7-4eb5-4f45-ab4f-dc9b2fb772c4)



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
