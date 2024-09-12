# Analisis-de-Irregularidades-en-Cultivos-de-Agave-con-Imagenes-Multiespectrales
Proyecto AgroDataThon 2024 


Este proyecto está enfocado en atacar un desafío que se encuentra presente en el área del agave orgánico para su valor agregado en la producción tequilera y para el desarrollo de su variente, la inulina. El desafío se encuentra en garantizar que el agave que el tequilero compra cumple con la  Regulación Mexicana de Productos Orgánicos, en el cual, para que el agave pase la inspección, durante los últimos tres años de su cultivo debe de estar libre de cualquier tipo de sustancia o fertilizante sintético nitrogenado. 

Para garantizar esta regulación, empleamos datos e imágenes espectrales del satélite Sentinel-2 en el cual se detectan ciertas bandas multiespectrales que detectan variaciones en la vegetación. En este proyecto, nos enfocamos en cuatro bandas fundamentales para nuestro análisis: B2, B3, B4 y B8, esto nos proporcionará la información necesaria con la cuál podremos analizar el comportamiento a lo largo del tiempo de los parámetros a través de medidas de distancia como la de Manhattan. Junto a una combinanción de estadística, encontraremos aquellos cambios bruscos en los parámetros que representarán ciertas anomálias en el comportamiento del agave, con lo cual, podremos implementar otras herramientas para acceder a las imágenes espectrales de esos intervalos de tiempos, e identificar qué representan esas anomalías en el agave. 

Una vez implementado todo lo anterior, podremos determinar a través del NDVI aquellos agaves cuyas anomalías representan el uso de fertilizantes sintéticos.
