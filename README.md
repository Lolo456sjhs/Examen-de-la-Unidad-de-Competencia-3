Examen de la Unidad de Competencia 3

Este proyecto en Java (Swing) implementa tres métodos numéricos para la resolución de sistemas de ecuaciones lineales de tres incógnitas:
Método de Gauss, Gauss-Jordan y Gauss-Seidel.

Descripción general

El programa permite al usuario ingresar los coeficientes de tres ecuaciones con tres variables (x1, x2, x3) y seleccionar el método numérico a aplicar.
Después de resolver el sistema, muestra el procedimiento paso a paso y una tabla con los cálculos realizados.

Métodos implementados

Método de Gauss
Aplica eliminación hacia adelante y sustitución regresiva para obtener las soluciones del sistema.

Método de Gauss-Jordan
Transforma la matriz aumentada en una matriz identidad para encontrar las soluciones directamente.

Método de Gauss-Seidel
Calcula las soluciones iterativamente hasta alcanzar una tolerancia establecida.

Interfaz gráfica (frmPrincipal)

La interfaz incluye:

Campos para ingresar los coeficientes de las tres ecuaciones.

Tres botones de selección (Gauss, Gauss-Jordan, Gauss-Seidel).

Un botón “Resolver” para ejecutar el método elegido.

Áreas de texto donde se muestran el procedimiento detallado y la tabla de resultados.

Clases principales

frmPrincipal → Controla la interfaz gráfica y la interacción con el usuario.

MetodoGauss → Contiene la lógica del método de eliminación de Gauss.

MetodoGaussJordan → Implementa el método de Gauss-Jordan.

(Opcional) MetodoGaussSeidel → Implementa el método iterativo Gauss-Seidel.

Autor

Humberto Barreras Carrisoza
Proyecto de la asignatura Métodos Numéricos Computacionales
