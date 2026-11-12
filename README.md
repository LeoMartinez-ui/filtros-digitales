# Implementación y evaluación de filtros digitales

## Descripción del proyecto

Este proyecto tiene como objetivo diseñar e implementar filtros digitales utilizando Python y Google Colab, para analizar el comportamiento de señales antes y después de aplicar diferentes técnicas de filtrado.

Se utilizan filtros pasa bajos, pasa altos y pasa bandas, mediante los métodos FIR e IIR.

## Herramientas utilizadas

- Python
- Google Colab
- NumPy
- SciPy
- Matplotlib
- GitHub

## Desarrollo

Se generó una señal compuesta por tres frecuencias (5 Hz, 50 Hz y 150 Hz), a la cual se agregó ruido aleatorio para simular interferencias.

Posteriormente, se implementaron los siguientes filtros:

1. **Pasa bajos:** frecuencia de corte de 20 Hz.
2. **Pasa altos:** frecuencia de corte de 30 Hz.
3. **Pasa bandas:** frecuencias de corte de 40 Hz y 100 Hz.

Se utilizaron filtros IIR Butterworth de cuarto orden y filtros FIR diseñados mediante el método de ventana.

## Resultados

Se generaron gráficas para comparar las señales originales y filtradas, analizar la respuesta en frecuencia y observar las diferencias entre los métodos FIR e IIR.

Los resultados permiten comprobar que cada filtro tiene una función específica para conservar o atenuar determinadas frecuencias.

## Conclusión

La implementación permitió comprender la importancia de los filtros digitales en el procesamiento de señales. Se comprobó que los filtros pasa bajos, pasa altos y pasa bandas permiten seleccionar diferentes componentes de frecuencia. También se identificaron diferencias entre los métodos FIR e IIR.

## Autor

Leonardo Javier Martínez Rojas
