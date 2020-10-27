# Introducción

* El proyecto **Cansat Educativo** es un sistema electrónico programable para telemetría de datos atmosféricos y geolocalización, lanzado por un cohete y rescatado con un paracaídas.

<center>
![CanSat](img/introduccion/cansatParacaidas.png)

CanSat
</center>

*  El **sistema electrónico programable** con el lenguaje visual Arduinoblock es un Arduino Mega 2560 Pro Mini con los siguientes sensores: BMP180, acelerómetro, receptor IR y GPS. También un datalogger en memoria microSD para la grabación de datos en local y el módulo de comunicaciones RF APC220 para mandar los datos captados por los sensores a la estación base.

<center>
![ComponentesSE](img/introduccion/cansatComponentes.png)

Componentes del sistema electrónico
</center>

<center>
![programaSensores](img/introduccion/programaSensores.png)

Programa. Código de bloques de Sensores
</center>

* La **estación base** recibe los datos por radio y  con el lenguaje de programación Processing almacena los datos en un archivo de datos plano y visualiza gráficamente, en tiempo real, la recepción de los datos con la aplicación KST.

<center>
![comunicaciones](img/introduccion/comunicaciones.png)

Comunicaciones CanSat-Estación Base.
Fuente: [recursos de ESERO](http://esero.es/wp-content/uploads/2019/10/T11_Radio_Communication.pdf)
</center>

<center>
![estacionBase](img/introduccion/graficas.png)

Presentación y gráficas de los datos
</center>
