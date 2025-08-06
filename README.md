# Predicción-de-mutantes-por-ESM-2
Predicción de los mutantes de la proteína de LuxR de _Aliivibrio fischeri_ generados a partir del modelo ESM-2 (esm.pretrained.esm2_t33_650M_UR50D) en Python y comparativa con la proteína silvestre. Código desarrollado en Google Colaboratory.

El código se divide en los siguientes puntos:

- Instalación de las librerías necesarias, incluyendo ESM-2 (esm.pretrained.esm2_t33_650M_UR50D).
- Determinar la secuencia de LuxR de _A. fischerii_ y generar todos los mutantes posibles de sustitución de 1 aminoácido entre las posiciones 176-241, incluidas.
- Cálculo de la posición asociada a cada mutante y ordenación de mayor a menor puntuación asociada.
- Cálculo de la energía asociada a la variante silvestre de la proteína y comparación con todos los mutantes.
- Guardado de los resultados en formatos .FASTA .
