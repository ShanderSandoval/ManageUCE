# ManageUCE - Sistema de Gestión de Clientes

ManageUCE es una aplicación que permite gestionar clientes a través de un sistema CRUD. Está compuesto por un **frontend** en React y un **backend** en Java con Spring Boot. Todo el sistema se puede ejecutar fácilmente con **Docker Compose**.

## **📌 Requisitos previos**
Antes de ejecutar el proyecto, asegúrate de tener instalado en tu sistema:
- [Docker]
- [Docker Compose]

## **🚀 Ejecución con Docker Compose**
Para levantar el sistema completo con **Docker Compose**, sigue estos pasos:

1. **Clonar el repositorio** con los submódulos:
   ```sh
   git clone --recurse-submodules https://github.com/ShanderSandoval/ManageUCE.git
   cd ManageUCE
   docker-compose up -d
