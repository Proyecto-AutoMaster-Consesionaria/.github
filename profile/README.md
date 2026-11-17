# 🚗 Concesionaria de Vehículos AutoMaster

¡Bienvenido al repositorio oficial de **AutoMaster**! Este proyecto fue desarrollado con el objetivo de gestionar de manera integral las operaciones de un concesionario automotriz.

### ✨ Funciones Principales del Sistema

* **🚘 Catálogo e Inventario:** Registro, búsqueda y filtrado de vehículos disponibles (nuevos y usados) por marca, modelo, año y precio.
* **💰 Gestión de Ventas y Cotizaciones:** Simulación de financiamiento, cálculo de cuotas y emisión de comprobantes de venta.
* **👥 Administración de Clientes y Empleados:** Control de perfiles, historial de compras y asignación de roles/permisos.


### 📂 Estructura de Repositorios

Este proyecto está dividido en los siguientes módulos dentro de nuestra organización:

| Repositorio | Descripción | Tecnologías |
| :--- | :--- | :--- |
| **`frontend-web`** | Interfaz de usuario y experiencia visual del sistema. | `React` |
| **`backend-api`** | Lógica de negocio, autenticación y conexión a datos. | `Java` |
| **`database`** | Scripts de creación de tablas, consultas y datos de prueba. | `MySQL,` |
| **`docker-deploy`** | Orquestación de contenedores (`docker-compose`) para despliegue local y producción. | `Docker, Docker Compose` |
| **`documentacion`** | Diagramas UML, manual de usuario y documentación técnica. | `Markdown` |


### 🐳 Arquitectura y Despliegue con Docker

Todo el sistema está contenerizado para garantizar que funcione exactamente igual en cualquier entorno de desarrollo o evaluación, evitando problemas de dependencias:

* **Contenedores independientes** para el Frontend, Backend y Base de Datos comunicados mediante una red interna de Docker.
* **Persistencia de datos** configurada mediante volúmenes para no perder la información del concesionario al reiniciar los servicios.
* **Despliegue rápido** en un solo comando:

### 👨‍💻 Equipo de Desarrollo

* **[Joaquín Henriquez]**
* **[Rolando Castro]**
* **[Cristofer Figueroa]**

