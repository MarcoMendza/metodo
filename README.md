# Interpolación de Newton

Este proyecto en Python implementa el método de interpolación de Newton para aproximar una función a partir de un conjunto de puntos dados.

## Requisitos

- Python 3.x
- Las siguientes librerías de Python:
  - NumPy
  - Tabulate
  - Matplotlib

Para instalar las dependencias, ejecuta el siguiente comando:

`pip install -r requirements.txt`

## Uso

1. Ejecuta el script `interpolacion.py`.
2. Ingresa los valores de `x` separados por comas cuando se te solicite.
3. Ingresa los valores de `y` separados por comas cuando se te solicite.
4. Ingresa el valor de `xi` (el punto de interpolación).

El programa calculará el polinomio de interpolación de Newton y mostrará los resultados en forma de tablas. Además, se generará una gráfica que muestra los puntos originales y el polinomio de interpolación.

## Salida

- Tabla de resultados con los valores de `n`, `x`, `y`, `b`, `(xh - x0)(xh - x1)...(xh - xn-1)`, `y interpolación` y `Rn`.
- Tabla con los polinomios de interpolación.
- Tabla de diferencias divididas.
- Gráfica que muestra los puntos originales y el polinomio de interpolación.

## Contribución

Si deseas contribuir a este proyecto, puedes enviar un pull request con tus cambios o mejoras. Asegúrate de seguir las mejores prácticas de programación y de incluir pruebas unitarias cuando sea apropiado.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).