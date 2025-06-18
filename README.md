# UADE - Fundamentos de la Informática (FDI) - Grupo 8

Repositorio de trabajo práctico correspondiente a la materia **Fundamentos de la Informática** de la carrera _Licenciatura en Tecnología de la Información_ en UADE (1er Cuatrimestre 2025).

## Descripción

Este proyecto simula un sistema básico para una administradora de consorcios. Su función principal es gestionar la información de las unidades de un edificio. Permite cargar datos esenciales como el número de unidad y su superficie en metros cuadrados. A partir de esta información, el sistema calcula automáticamente los gastos mensuales de expensas, basándose en un valor fijo por metro cuadrado. Además, ofrece la funcionalidad de ordenar las unidades según su superficie, facilitando la visualización y el análisis de los datos.

## Conceptos aplicados

Este trabajo pone en práctica los temas vistos en clase:

- Uso de funciones y modularización (`utils.py`)
- Validación de datos
- Estructuras de control (`if`, `while`, `for`)
- Estructuras de datos: listas paralelas
- Cálculo de promedios y multiplicaciones
- Ordenamiento burbuja descendente
- Salida formateada por consola
- Separación de lógica en módulos reutilizables

## Estructura del proyecto

| Archivos    | Contenido                                                |
| ----------- | -------------------------------------------------------- |
| main.py     | Versión principal en consola                             |
| main_gui.py | Versión con interfaz gráfica en Tkinter                  |
| utils.py    | Funciones auxiliares: cálculo, ordenamiento y validación |
| README.md   | Documentación del proyecto                               |

## Ejecución

### Desde consola (modo texto)

    python main.py
    El programa solicitará:
    -   Numero de unidad
    -   Superficie en m²
    -   Valor del metro cuadrado
    Y mostrará:
    -   Gasto por unidad
    -   Promedio general
    -   Listado ordenado de mayor a menor por superficie

### Desde interfaz gráfica (opcional)

    python main_gui.py
    Se abre una ventana donde se pueden:

    -   Ingresar unidades y superficies

    -   Ingresar el valor del m²

    -   Calcular automáticamente gastos y promedio

    -   Visualizar una tabla ordenada de resultados

## 🛠️ Requisitos

- Python 3.9 o superior
- No requiere la instalación de librerías externas adicionales. La librería Tkinter necesaria para la GUI viene incluida por defecto con la instalación estándar de Python.

## 📌 Créditos

**Grupo 8 - UADE**  
Materia: Fundamentos de la Informática  
Año: 2025
