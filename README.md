# VelocityMotors-System
Sistema de gestión para taller automotriz desarrollado en C# y SQL Server, implementando arquitectura en capas y funcionalidades como gestión de clientes, vehículos, órdenes de trabajo y control de usuarios por roles.

---

#  Velocity Motors System
Sistema de gestión para taller automotriz desarrollado en C# (Windows Forms) y SQL Server, implementando arquitectura en capas y control de usuarios por roles.

---

## Descripción

Velocity Motors es un sistema diseñado para la administración de un taller automotriz (ficticio), permitiendo gestionar clientes, vehículos, órdenes de trabajo y servicios de manera organizada y eficiente.

---

## Tecnologías utilizadas

-  C# (Windows Forms)
-  SQL Server
-  Arquitectura en capas (Presentación, Negocio, Datos)
-  Guna UI (diseño de interfaz)

---

## Funcionalidades principales

-  Inicio de sesión con control de roles (Administrador / Empleado)
-  Gestión de empleados (CRUD)
-  Gestión de clientes
-  Gestión de vehículos
-  Gestión de órdenes de trabajo
-  Asignación de servicios a órdenes 
-  Visualización de datos mediante tablas

---

## Arquitectura

El sistema está estructurado en capas:

- **Presentación** → Formularios (UI)
- **Negocio** → Lógica del sistema
- **Datos** → Acceso a base de datos

---

## Base de datos

El proyecto incluye scripts SQL organizados:

- `01_schema.sql` → creación de tablas
- `02_stored_procedures.sql` → procedimientos almacenados
- `03_seed_data.sql` → datos de prueba

---

##  Cómo ejecutar el proyecto

1. Clonar el repositorio
2. Abrir la solución `.sln` en Visual Studio
3. Ejecutar los scripts SQL en SQL Server
4. Configurar la cadena de conexión en la capa datos, poner el nombre del servidor que ocupa en SQLserver
5. Ejecutar el proyecto

---

##  Notas

- Este proyecto es de carácter académico/demo
- No incluye seguridad avanzada (hashing de contraseñas, etc.)
- Totalmente funcional para fines de aprendizaje y demostración de habilidades

---

## Autor

**José Daniel Esteban Cea**
