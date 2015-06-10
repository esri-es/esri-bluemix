# esri-bluemix
Este repositorio reune algunos proyectos semilla que permite empezar proyectos usando la API de ArcGIS y la infraestructura PaaS de Bluemix en menos de dos minutos.

## Crear un proyecto a partir de una semilla
Asegúrate de haber realizado los pasos especificados en la sección "Pre-requisitos"

1.  Abrimos una consola/terminal
2.  Clonamos o hacemos un fork del repositorio:<br>```$git clone https://github.com/esri-es/esri-bluemix.git```
3.  Crear la aplicación en Bluemix a partir de un directorio:<br>```$cf push proyecto-esri-map -p <directorio> `p.e: angular-esri-map>````
4.  Para actualizar cambios en la aplicación sólo necesitaremos correr:<br>```$cf push```

## Pre-requisitos
1. Tener Git instalado
2. Disponer de una cuenta de Bluemix
3. Tener instalada la línea de comandos de Cloud Foundry
4. Identificamos con nuestra cuenta de Bluemix:<br>```$cf login```
