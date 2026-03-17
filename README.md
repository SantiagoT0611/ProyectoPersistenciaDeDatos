# Sistema de Persistencia de Datos - Campañas de Vacunación

##  Descripción

Este proyecto consiste en el desarrollo de un sistema de gestión de campañas de vacunación, enfocado en la implementación de persistencia de datos mediante el uso de bases de datos relacionales y el patrón DAO (Data Access Object).

El sistema permite administrar información relacionada con personas, profesionales de la salud y registros de vacunación, garantizando una correcta organización, almacenamiento y acceso a los datos.

---

##  Objetivos del Proyecto

- Implementar un sistema CRUD completo para la gestión de datos.
- Aplicar el patrón DAO para desacoplar la lógica de acceso a datos.
- Gestionar la conexión a base de datos de forma eficiente.
- Modelar entidades del mundo real relacionadas con campañas de vacunación.
- Aplicar buenas prácticas de programación en Java.

---


---

##  Componentes Principales

###  Conexión a Base de Datos

- **Conexion.java**
  - Encargado de establecer la conexión con la base de datos.
  - Maneja credenciales, driver y configuración.

---

###  DAOs (Data Access Object)

Se encargan de interactuar directamente con la base de datos:

- **PersonaDAO**
  - CRUD de personas registradas.

- **ProfesionalSaludDAO**
  - Gestión de profesionales de la salud.

- **RegistroVacunacionDAO**
  - Registro de vacunas aplicadas.

 Ventaja: separación total entre lógica de negocio y acceso a datos.

---

###  Modelos (Entidades)

Representan las tablas en la base de datos:

- **CampañaVacunacion**
- **PersonaDTO**
- **RegistroVacunacion**

Contienen atributos, getters, setters y lógica básica.

## Tecnologías Utilizadas

-  Java
-  JDBC (Java Database Connectivity)
-  Base de datos relacional (MySQL)
-  Programación orientada a objetos (POO)

---

##  Funcionalidades

-  Registrar personas
-  Registrar profesionales de salud
-  Crear campañas de vacunación
-  Registrar vacunaciones
-  Consultar información
-  Actualizar registros
-  Eliminar datos
---

##  Operaciones CRUD

El sistema permite:

- **Create** → Insertar datos en la base de datos  
- **Read** → Consultar registros  
- **Update** → Modificar información  
- **Delete** → Eliminar registros  

---

##  Instalación y Ejecución

###  Requisitos

- Java JDK 8 o superior
- Base de datos MySQL (o compatible)
- IDE (IntelliJ, Eclipse o VS Code)

---

1. Clonar el repositorio:

```bash
git clone https://github.com/SantiagoT0611/ProyectoPersistenciaDeDatos.git
