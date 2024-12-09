# Hola Mundo REST API with Docker

## Project Description
A simple "Hello World" REST API built with **Node.js** and **Express**, containerized using **Docker**. This project serves as an introductory example to create and deploy a RESTful API, while learning about Docker and how to run applications in containers.

## Requirements
- **Node.js** (v18 or higher)
- **npm** (v8 or higher)
- **Docker** (v20 or higher)

## Installation

### Clone the repository:
```bash
git clone https://github.com/yourusername/hola-mundo-api.git
cd hola-mundo-api
```
Install dependencies:
```bash
npm install
```
Running the Application Locally:
Run the application:
```bash
node index.js
```
The API will be available at http://localhost:3000.
Dockerize the Application:
Build the Docker image:
```bash
docker build -t hola-mundo-api .
```
Run the Docker container:
```bash
docker run -p 3000:3000 hola-mundo-api
```
The API will be available at http://localhost:3000.
Docker Hub
You can find the Docker image on Docker Hub here.

README en Español
markdown
Copiar código
# Hola Mundo REST API con Docker

## Descripción del Proyecto
Una simple API REST de "Hola Mundo" construida con **Node.js** y **Express**, dockerizada usando **Docker**. Este proyecto sirve como ejemplo introductorio para crear y desplegar una API RESTful, mientras se aprende sobre Docker y cómo ejecutar aplicaciones en contenedores.

## Requisitos
- **Node.js** (v18 o superior)
- **npm** (v8 o superior)
- **Docker** (v20 o superior)

## Instalación

### Clonar el repositorio:
```bash
git clone https://github.com/tuusuario/hola-mundo-api.git
cd hola-mundo-api
```
Instalar dependencias:
```bash
npm install
```
Ejecutar la aplicación localmente:
Ejecuta la aplicación:
```bash
node index.js
```
La API estará disponible en http://localhost:3000.
Dockerizar la aplicación:
Construye la imagen de Docker:
```bash
docker build -t hola-mundo-api .
```
Ejecuta el contenedor de Docker:
```bash
docker run -p 3000:3000 hola-mundo-api
```
La API estará disponible en http://localhost:3000.
Docker Hub
Puedes encontrar la imagen de Docker en Docker Hub aquí.


---

### Explicación de los Apartados:
- **Project Description**: Una breve descripción del proyecto y su propósito.
- **Requirements**: Versión mínima de Node.js, npm y Docker necesarios.
- **Installation**: Cómo clonar el repositorio y las instrucciones para ejecutar la aplicación localmente, además de los comandos para dockerizarla.
- **Docker Hub**: Un enlace al repositorio de Docker Hub donde se encuentra la imagen dockerizada.

---

### **¿Qué Debes Hacer?**
1. **Reemplaza** `yourusername` y `tuusuario` con tu nombre de usuario real de GitHub y Docker Hub.
2. **Sube tu imagen a Docker Hub**: Si quieres compartir la imagen, asegúrate de subirla usando el siguiente comando:
   ```bash
   docker push yourusername/hola-mundo-api
