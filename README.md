# Trabajo Práctico Integrador - Base de Datos

Este proyecto tiene como objetivo la creación de una base de datos denominada "integrador_cac" y una tabla llamada "oradores". A continuación, se presenta un resumen del desarrollo y entrega del trabajo.

## Desarrollo

### 1. Creación de la Base de Datos y Tabla

- Se creó la base de datos "integrador_cac" y se seleccionó para trabajar con ella.
- La tabla "oradores" se diseñó con las siguientes columnas:
  - `id_orador`: Tipo INT, clave primaria, autoincremental.
  - `nombre` y `apellido`: Tipo VARCHAR(50), no nulos.
  - `email`: Tipo VARCHAR(100), no nulo y único.
  - `tema`: Tipo VARCHAR(100), no nulo.
  - `fecha_alta`: Tipo DATE, no nulo.

### 2. Inserción de 10 Registros de Ejemplo

- Se añadieron 10 registros ficticios a la tabla "oradores" como ejemplo.

### 3. Backup de la Base de Datos

- Se realizó un backup de la base de datos "integrador_cac" utilizando MySQL Workbench. El archivo de respaldo se encuentra en el repositorio y se denomina `integrador_cac_backup.sql`.

## Entrega en GitHub

El repositorio de GitHub contiene los siguientes elementos:

1. **Estructura de la Tabla:**
   - Captura de pantalla que muestra la estructura de la tabla "oradores" desde MySQL Workbench.

2. **Registros Insertados:**
   - Capturas de pantalla que muestran algunos registros insertados en la tabla "oradores" desde MySQL Workbench.

3. **Backup de la Base de Datos:**
   - El archivo de respaldo `integrador_cac_backup.sql`.

4. **Archivo con Estructura tabla:**
   - El archivo `integrador-BD.sql` contiene la estructura de la tabla, y los 10 registros. 