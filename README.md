# Taller-S4-programacion-I-
**Sistema de Gestión de Inventario (Multi-Sucursal)**

Ingeniería en Inteligencia Artificial - UDLA. 

Este sistema permite gestionar el inventario de una tienda con 3 sucursales (Norte, Centro y Sur) para un máximo de 10 productos. El proyecto destaca por su arquitectura de **Programación Modular**, dividiendo la lógica en múltiples archivos (`main.c`, `inventario.c`, `inventario.h`) para un código limpio y escalable.

## Funcionalidades
* **Registro de Datos:** Ingreso de nombres, precios y cantidades por sucursal mediante validaciones de entrada.
* **Cálculos Financieros:** Cálculo del valor total del inventario y del precio promedio por sucursal.
* **Análisis de Extremos:** Identificación automática del producto más caro y más barato en cada local.
* **Motor de Búsqueda:** Búsqueda de productos por nombre utilizando la biblioteca `<string.h>`.
* **Alertas de Stock:** Conteo total de unidades y generación de alertas visuales para productos con stock crítico (≤ 5 unidades).

## Aspectos Técnicos
Cumpliendo con los requerimientos estrictos de la consigna, este sistema **no utiliza estructuras (`structs`) ni punteros**. La relación de los datos se maneja íntegramente mediante la técnica de **Arreglos Paralelos** (vectores unidimensionales para textos y matrices bidimensionales flotantes/enteras para valores numéricos), iterados mediante bucles anidados.

---
**Autores:**
* Matías Moya
* Esteban Rojas
* Anthony Loor
