# Sistema de Gestión de Minas e Inventario

Un sistema de escritorio desarrollado en **Java** utilizando **Maven** para la administración, control de usuarios y gestión de inventario de materiales de extracción minera.

---

## 🚀 Características Principales

* **Control de Acceso y Autenticación:** Roles diferenciados para Administradores y Empleados.
* **Gestión de Usuarios:** Módulo exclusivo de administración para la creación y gestión de credenciales para empleados.
* **Administración de Inventarios:** Control detallado de materiales (stock, unidades de medida y precios).
* **Generación de Reportes PDF:** Exportación automatizada del estado de inventario de la mina en formato PDF.

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Java
* **Gestor de Dependencias:** Apache Maven
* **Entorno de Desarrollo (IDE):** IntelliJ IDEA / NetBeans / Eclipse
* **Base de Datos:** Script SQL (`BDMinasScript.txt`)

---
imagenes
<img width="702" height="391" alt="image" src="https://github.com/user-attachments/assets/4e523710-a280-4c66-90ec-9fb5f6c5f9ea" />
<img width="732" height="412" alt="image" src="https://github.com/user-attachments/assets/9ba0e22e-3834-448f-9f07-a7ad339a5855" />


## 📂 Estructura del Proyecto

```text
.
├── .mvn/                  # Configuración del ejecutable de Maven Wrapper
├── src/main/              # Código fuente de la aplicación (Java y Recursos)
├── BDMinasScript.txt      # Script para la creación e inicialización de la Base de Datos
├── Reporte_Inventario.pdf # Muestra/Ejemplo de reporte generado por el sistema
├── instrucciones          # Indicaciones iniciales del sistema
├── pom.xml                # Archivo de configuración de Maven y dependencias
└── mvnw / mvnw.cmd        # Wrapper ejecutable de Maven (Linux/Windows)
