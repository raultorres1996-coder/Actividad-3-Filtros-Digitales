Actividad Formativa 3: Implementación y Evaluación de Filtros Digitales

Descripción del proyecto

Este proyecto tiene como finalidad diseñar, implementar y evaluar filtros digitales utilizando Python, con el propósito de analizar el comportamiento de señales antes y después del filtrado.

Se implementaron tres tipos de filtros: pasa bajos, pasa altos y pasa bandas.

Objetivo

Diseñar y evaluar filtros digitales Butterworth para identificar su efectividad en la selección y atenuación de diferentes componentes de frecuencia presentes en una señal con ruido.

Herramientas utilizadas

Python

Google Colab

NumPy

SciPy

Matplotlib

GitHub

Desarrollo

1. Generación de la señal

Se generó una señal digital compuesta por tres frecuencias:

5 Hz

50 Hz

120 Hz

Se agregó ruido aleatorio para simular interferencias en la señal.

2. Filtro pasa bajos

Se diseñó un filtro Butterworth de cuarto orden con frecuencia de corte de 20 Hz.

Este filtro permitió conservar principalmente la componente de 5 Hz y atenuar las frecuencias superiores.

3. Filtro pasa altos

Se implementó un filtro Butterworth de cuarto orden con frecuencia de corte de 80 Hz.

Este filtro permitió conservar principalmente la componente de 120 Hz y atenuar las frecuencias bajas.

4. Filtro pasa bandas

Se implementó un filtro Butterworth de cuarto orden con frecuencias de corte de 40 Hz y 60 Hz.

Este filtro permitió conservar principalmente la componente de 50 Hz.

Resultados obtenidos

Señal

5 Hz

50 Hz

120 Hz

Original

0.9980

0.6991

0.5081

Pasa bajos

0.9977

0.0048

0.0020

Pasa altos

0.0000

0.0147

0.4909

Pasa bandas

0.0035

0.6851

0.0006

Los resultados muestran que los filtros implementados conservaron principalmente las frecuencias deseadas y atenuaron las componentes que se encontraban fuera de su región de paso.

Gráficas

Filtro pasa bajos



Filtro pasa altos



Filtro pasa bandas



Comparación de filtros



Respuesta en frecuencia



Evaluación de resultados



Conclusión

La implementación de filtros digitales permitió comprender cómo se pueden seleccionar determinadas frecuencias de una señal mediante técnicas de procesamiento digital.

Los resultados obtenidos demostraron que los filtros Butterworth son efectivos para atenuar componentes no deseadas y conservar aquellas que se encuentran dentro de su región de paso.

Además, el uso de Python permitió visualizar y analizar el comportamiento de los filtros mediante gráficas y cálculos numéricos.

Código fuente

El código completo de la simulación se encuentra disponible en el cuaderno de Jupyter incluido en este repositorio.
