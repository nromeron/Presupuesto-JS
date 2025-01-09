# Aplicación Presupuesto

Esta es una aplicación web para gestionar presupuestos personales. Permite a los usuarios agregar ingresos y egresos, y calcula automáticamente el presupuesto disponible y el porcentaje de egresos sobre los ingresos.

## Estructura del Proyecto

El proyecto tiene la siguiente estructura de archivos:

### Archivos y Directorios

- **.gitattributes**: Archivo de configuración para normalizar los finales de línea en el repositorio.
- **Web App Presupuesto/css/estilos.css**: Archivo de estilos CSS para la aplicación.
- **Web App Presupuesto/index.html**: Archivo HTML principal de la aplicación.
- **Web App Presupuesto/js/app.js**: Archivo JavaScript principal que contiene la lógica de la aplicación.
- **Web App Presupuesto/js/Dato.js**: Clase base `Dato` que representa un dato genérico con descripción y valor.
- **Web App Presupuesto/js/Egreso.js**: Clase `Egreso` que extiende de `Dato` y representa un egreso.
- **Web App Presupuesto/js/Ingreso.js**: Clase `Ingreso` que extiende de `Dato` y representa un ingreso.

## Funcionalidades

### Agregar Ingresos y Egresos

Los usuarios pueden agregar ingresos y egresos a través del formulario en la parte superior de la página. Los ingresos se muestran en la sección de ingresos y los egresos en la sección de egresos.

### Calcular Presupuesto

La aplicación calcula automáticamente el presupuesto disponible restando los egresos de los ingresos. Este valor se muestra en la parte superior de la página.

### Calcular Porcentaje de Egresos

La aplicación también calcula el porcentaje de egresos sobre los ingresos y lo muestra junto al valor total de egresos.

### Eliminar Ingresos y Egresos

Los usuarios pueden eliminar ingresos y egresos haciendo clic en el icono de eliminar junto a cada elemento. La aplicación recalcula automáticamente el presupuesto y el porcentaje de egresos.

## Cómo Ejecutar la Aplicación

1. Clona el repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador web.

## Ejemplo de Uso

1. Abre la aplicación en tu navegador.
2. Agrega un ingreso o egreso utilizando el formulario.
3. Observa cómo se actualiza el presupuesto disponible y el porcentaje de egresos.

## Tecnologías Utilizadas

- HTML
- CSS
- JavaScript

## Autor

Esta aplicación fue desarrollada por Nicolas Romero Niño siguiendo los pasos e instrucciones del curso de Udemy "JavaScript, de cero a experto".