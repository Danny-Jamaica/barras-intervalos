# Graficas de barras con intervalos de confianza

Al momento de graficar con barras ocurre el problema heredado por la interpretación erronea de la media. Este problema se puede solucionar si aplicamos los intervalos de confianza. Aquí te lo voy a explicar de manera muy sencilla.

En este archivo generé valores aleatorios, se agrupan en 4 grupos, luego la altura de cada barra es la media de cada uno de los grupos. Se crean los intervalos de confianza de cada barra de acuerdo a que tanto varian los datos, luego cada barra tiene su propio intervalo de confianza.

Se fija cualquier valor en este caso es 41000. Si este valor fijo está por debajo del intervalo de confianza se tornará de color azul. Si el valor fijo está por encima del intervalo de confianza se tornará de color azul.

Si los las barras está lejos de 41000 serán de color oscuro. Pero si las barras están cerca de 41000 serán de color claro.

Tu puedes cambiar el valor de 41000 para ver como se comporta el modelo. Esto lo haces cambiando "value" en el código que puse en Jupyter.

¡Para comprender todo lo que acabo de mencionar te invito observar el código!

Esto lo aprendí con Coursera - University of Michigan - Applied Data Science with Python Specialization. 

¡Es una especialización que te recomiendo!