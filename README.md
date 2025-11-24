# **Ejercicio Práctico \- Teoría del Control**

Este repositorio contiene la resolución de una serie de ejercicios prácticos de la asignatura de **Teoría del Control**, enfocados en el análisis de respuesta temporal y diagramas de bloques.

## **Estructura del Repositorio**

A continuación se describe el contenido de los archivos principales:

* **control.ipynb**: Este es el **archivo ejecutable** principal (Jupyter Notebook). Contiene todo el código Python, los cálculos y la generación de gráficas en tiempo real.  
* **control.pdf**: Es una exportación estática del notebook completo. Sirve para visualizar los resultados y el código sin necesidad de ejecutar Python.  
* **Imágenes (\*.png)**: Archivos de imagen que contienen los **diagramas de los sistemas de control** y esquemas de bloques analizados en los ejercicios.

## **Detalle de los Ejercicios**

El notebook (control.ipynb) aborda los siguientes problemas:

1. **Respuesta de Primer Orden:** Análisis y comparativa gráfica de un sistema $G(s) \= \\frac{K}{s+1}$ para ganancias $K=1, 2, 3$.  
2. **Amortiguamiento Crítico:** Cálculo de la ganancia $K$ necesaria para obtener $\\zeta \= 1$ en un sistema de segundo orden.  
3. **Especificaciones Temporales:** Obtención numérica del tiempo de crecimiento ($t\_r$) y sobreimpulso ($M\_p$).  
4. **Diseño de Controladores:** Ajuste de ganancia para cumplir requisitos de sobreimpulso máximo (5%) y error en régimen permanente.  
5. **Simplificación de Bloques:** Reducción algebraica de un diagrama de bloques complejo con perturbaciones para obtener su función de transferencia equivalente.

## **Tecnologías**

* **Python 3**  
* **Librerías:** control, numpy, matplotlib

## **Cómo ejecutar**

Para interactuar con el código, clona este repositorio y abre el archivo notebook *.ipynb*, puedes usar Jupyter Notebook


*Este ejercicio fue realizado como parte práctica de la asignatura de Teoría del Control.*
