# pruebasCarga
Pruebas de carga APIS - Jmeter

Pasos para ejecutar por CMD:

1. Ubicarse en la ruta del bin de la carpeta de apache_jmeter
2. Ejecutar el siguiente comando:

jmeter -n -t "<Ubicación del archivo .jmx>" -l "<Ubicación y nombre del archivo de resultados resultadosPrueba.jtl>" 

Ejemplo:

jmeter -n -t "D:\apache-jmeter-5.1.1\bin\PrecisoConsumo\Sprint_1.jmx" -l "D:\apache-jmeter-5.1.1\bin\PrecisoConsumo\resultadosPrueba.jtl" 
