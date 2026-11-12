# Ejercicio 2: Modelo Relacional y Diseño Físico - Base de Datos Empresa

Este repositorio contiene la solución para el diseño de base de datos relacional correspondiente al sistema de gestión de departamentos y empleados, estructurado e implementado en **MySQL Workbench 8.0**.

## 📁 Estructura del Repositorio

* **`Tabla de relación.png`**: Imagen del diagrama Entidad-Relación (E-R) desarrollado y validado en MySQL Workbench.
* Archivos adicionales de modelo (`.mwb`) o script DDL (`.sql`) asociados al diseño físico.

## 🗂️ Modelo de Datos y Relaciones

El esquema consta de dos entidades principales vinculadas mediante una relación de uno a muchos (**1:N**):

1. **`DEPARTAMENTO`**: Almacena la información institucional de cada área de trabajo.
   * `DeptID` (PK): Identificador único del departamento.
   * `NombreDepto`: Nombre asignado al departamento.
   * `Ubicacion`: Dirección o zona física de la dependencia.

2. **`EMPLEADO`**: Registra los datos del personal adscrito a la organización.
   * `EmpID` (PK): Identificador único del empleado.
   * `Nombre`: Nombre(s) del trabajador.
   * `Apellido`: Apellido(s) del trabajador.
   * `Edad`: Edad actual en años.
   * `Salario`: Compensación económica mensual.
   * `DeptID` (FK): Llave foránea que referencia al departamento al que pertenece.

---
*Desarrollado como parte de las prácticas de modelado de bases de datos relacionales.*