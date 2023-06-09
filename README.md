# Redes_QRNG
Implementación en Python de las redes utilizadas para el análisis del QRNG.
Los archivos de código son notebooks de jupyter 

El repositorio cuenta con 3 carpetas principales, LCG, Data Cruda y Data Post-Procesada

# LCG
Esta carpeta incluye las 3 redes empleadas para el ataque sobre el PRNG de congruencia lineal.

# Data Cruda
En esta carpeta se encuentran las redes utilizadas en el análisis de la data cruda.
Adicionalmente, se tienen 2 archivos de texto: data_4bits y prueba_estadistica

data_4bits incluye los datos crudos del QRNG en formato de números de 4 bits que siguen una distribución uniforme.
prueba_estadistica contiene los datos empleados para la prueba de muestras emparejadas.
Ambos archivos de texto deben encontrarse en el mismo directorio que los archivos de código para el buen funcionamiento de estos últimos.

Si se desea llevar a cabo la prueba estadística, es necesario crear adicionalmente un archivo de excel en el mismo directorio del archivo de código de la red
que se esté utilizando. El libro de excel debe llamarse prueba_estadistica_FNN.xlsx, prueba_estadistica_LSTM.xlsx o prueba_estadistica_RCNN.xlsx si se está
trabajando con la red prealimentada, la red LSTM o la red recurrente convolucional, respectivamente.

# Data Post-Procesada
En esta carpeta pueden hallarse las 3 redes que se emplearon para el análisis de la data post-procesada.
También se cuenta con los archivos de texto data_1bit y prueba_estadistica_pp. El primero contiene los datos post-procesados del QRNG en formato binario, mientras que el segundo está constituido por los datos empleados en las pruebas estadísticas de la data post-procesada.
Similar al caso de la data cruda, estos archivos deben estar en el mismo directorio que los archivos de código.

Si se desea llevar a cabo la prueba estadística, es necesario crear adicionalmente un archivo de excel en el mismo directorio del archivo de código de la red
que se esté utilizando. El libro de excel debe llamarse prueba_estadistica_FNN_pp.xlsx, prueba_estadistica_LSTM_pp.xlsx o prueba_estadistica_RCNN_pp.xlsx si se está
trabajando con la red prealimentada, la red LSTM o la red recurrente convolucional, respectivamente.
