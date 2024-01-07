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
 
  - ![Consumo Correcto](https://github.com/EnriqueVOZA/VozmedianoEnrique_PruebaTecnica_APX/blob/main/images/ConsumoCorrectoAPX.png)
  - ![Persistencia correcta](https://github.com/EnriqueVOZA/VozmedianoEnrique_PruebaTecnica_APX/blob/main/images/Persistencia%20de%20datos.png)
    
    
- *Herramientas y Procedimientos:*
  - Se ha aprovechado `apx-cli` para la creación eficiente del DTO, la librería y la transacción.
  - La utilidad JDBC generada por `apx-cli` ha sido implementada con éxito para gestionar la conexión con la base de datos Oracle.

- *Pruebas y Validación:*
  - La aplicación ha sido sometida a pruebas exhaustivas utilizando Postman

- *Componentes Esenciales:*
  - Se ha desarrollado un DTO de salida y otro de entrada, ambos pasando de manera obligatoria por la librería de negocio.
 
- *Errores:*
  - Debido a las dificultades con el entorno local el consumo correcto con todos los datos incluido el fullName fue conseguido y registrado en el archivo "apx-cpnt-persistenciacpva-master@a3be244fb4f__PRUEBAFINALCONSUMOCORRECTO.zip", pero con la intención de presentar unas imágenes mas limpias con los registros de la base de datos y la correcta inserción del fullName al hacer un DROP TABLE T_WIKJ_HAB_PRUEBAFINAL las solicitudes por Postman empezaron a devolver un 500 y no pude hacer la foto y por la falta de tiempo no he podido sacar las imágenes, pero el código es 100% funcional.


