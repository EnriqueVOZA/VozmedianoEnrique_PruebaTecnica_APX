# README - Proyecto Exitoso de Inserción de Información de Cliente en Base de Datos Oracle

**Logros Destacados:**

- *Esquema y Nombre de Tabla:*
  - La tabla está ubicada dentro del esquema WIKJ y lleva el nombre T_WIKJ_HAB_PRUEBAFINAL, cumpliendo con las restricciones especificadas.

- *Campos de la Tabla:*
  - La estructura de la tabla incluye los campos necesarios:
    - `id Number(5) NOT NULL PRIMARY KEY`
    - `nuip Number(10)`
    - `full_name VARCHAR(50)`
    - `phone VARCHAR(15)`
    - `address VARCHAR(30)`

- *Prácticas de Seguridad y Buenas Prácticas:*
  - Se han implementado prácticas seguras en el manejo de la base de datos, evitando consultas del tipo `SELECT *` y utilizando una sintaxis segura para la inserción de valores.

- *Proceso y Salida:*
  - La salida refleja la información proporcionada como entrada, lograda mediante consultas `SELECT` utilizando el ID recibido o devolviendo directamente la información ingresada. La correcta ejecución de la inserción ha sido validada con éxito.
  - ![Consumo Correcto](https://raw.githubusercontent.com/EnriqueVOZA/VozmedianoEnrique_PruebaTecnica_APX/main/images/ConsumoCorrectoAPX.png)
- *Herramientas y Procedimientos:*
  - Se ha aprovechado `apx-cli` para la creación eficiente del DTO, la librería y la transacción.
  - La utilidad JDBC generada por `apx-cli` ha sido implementada con éxito para gestionar la conexión con la base de datos Oracle.

- *Pruebas y Validación:*
  - La aplicación ha sido sometida a pruebas exhaustivas utilizando Postman

- *Componentes Esenciales:*
  - Se ha desarrollado un DTO de salida y otro de entrada, ambos pasando de manera obligatoria por la librería de negocio.


