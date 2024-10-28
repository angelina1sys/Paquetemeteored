
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

## Introducción

Este paquete proporciona herramientas sencillas pero potentes para
trabajar con datos de temperatura. Las tres funciones incluidas permiten
resumir las temperaturas registradas en diferentes estaciones, convertir
valores de temperatura de Fahrenheit a Celsius y generar gráficos para
visualizar las temperaturas promedio mensuales por estación.

### Funciones principales

1.  **`tabla_resumen_temperatura`**: Crea una tabla de resumen con el
    valor mínimo, máximo y promedio de la temperatura registrada a 150
    cm de altura para cada estación.
2.  **`farenheit_a_centigrados`**: Convierte un valor de temperatura de
    Fahrenheit a Celsius.
3.  **`grafico_temperatura_mensual`**: Genera un gráfico de líneas con
    las temperaturas promedio mensuales agrupadas por estación.

### ¿Para quién es útil?

Este paquete es útil para climatólogos, meteorólogos, investigadores o
cualquier persona que trabaje con datos de clima y desee simplificar el
análisis de las temperaturas a lo largo del tiempo. Es especialmente
útil en estudios estacionales o en el seguimiento del clima en
diferentes regiones o alturas.

### Datos requeridos

Las funciones trabajan con data frames que incluyen información sobre
las temperaturas medidas en estaciones meteorológicas. Los datos deben
contener una columna de temperatura registrada a 150 cm de altura, junto
con identificadores de la estación y del mes o tiempo de medición.

### Uso

Puedes utilizar este paquete para obtener resúmenes estadísticos de las
temperaturas, realizar conversiones de unidades y visualizar datos de
clima de una manera gráfica y clara. Esto facilita la comparación entre
estaciones y la observación de patrones a lo largo del año.

### Instalación

Se puede instalar la versión de desarrollo de meteored desde GitHub con:

``` r
# install.packages("pak")
pak::pak("angelina1sys/Paquetemeteored")
```
