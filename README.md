# PROYECTO-GESTION-DE-NEGOCIOS

## Descripción
Este proyecto es un sistema modular desarrollado en Python para gestionar las entradas y salidas de inventario de un negocio en un período de un mes. El sistema permite ingresar datos del negocio, manejar un inventario predeterminado o personalizado, realizar facturación y exportar el inventario a un archivo Excel. El proyecto enfatiza el uso de principios de Clean Code y programación funcional, y está implementado para ejecutarse en consola (CMD) sin interfaz gráfica.

## Alcance
- Ingreso de datos básicos del negocio (nombre, RUC, propietario, tipo de negocio, correo, teléfono).
- Configuración predeterminada o personalizada de productos en inventario.
- Modificación de productos y precios en el inventario.
- Sistema de facturación que actualiza el inventario y calcula totales.
- Exportación del inventario a archivos Excel.
- Funcionalidad mediante menú en consola para fácil manejo.

## Funcionalidades Principales
- Mostrar productos disponibles en el inventario.
- Añadir nuevos productos o actualizar los existentes.
- Eliminar productos del inventario.
- Generar facturas por las ventas realizadas.
- Exportar inventario a archivo Excel para respaldo o análisis externo.

## Tecnologías
- Lenguaje: Python
- Herramienta: Jupyter Notebook
- Librerías: pandas (para manejo de datos tabulares y exportación a Excel)

## Estructura del Proyecto
El proyecto está organizado en módulos diferenciados para:
- Importación de librerías.
- Definición de funciones para cada tarea (mostrar, ingresar, eliminar productos; facturación; exportación).
- Sistema de menú interactivo.
- Programa principal para la captura de datos del negocio y ejecución del menú.

## Cómo usar
1. Descargar el repositorio en archivo .zip.
2. Abrir el archivo `PROYECTO-ORDENADO.ipynb` con Jupyter Notebook.
3. Ejecutar las celdas en orden para cargar las funciones y el programa principal.
4. Ingresar los datos solicitados para el negocio.
5. Utilizar el menú interactivo para gestionar el inventario y realizar operaciones de facturación.
6. Exportar el inventario a Excel si se desea un archivo de respaldo.

## Limitaciones
- No cuenta con interfaz gráfica, solo consola.
- La gestión está limitada a un registro local y condiciones definidas en el código.
- La configuración predeterminada de inventarios depende del tipo de negocio (3 tipos disponibles).

## Objetivos del Proyecto
- Poner en práctica conocimientos adquiridos en Python y programación funcional.
- Facilitar tareas comerciales mediante un sistema modular y claro.
- Fomentar el aprendizaje autónomo y la correcta aplicación del paradigma funcional.
- Implementar principios de Clean Code para facilitar mantenimiento y ampliación futura.

## Autor
Estefano Chávez

## Licencia
Este proyecto está bajo la licencia MIT - ver el archivo LICENSE para más detalles.
