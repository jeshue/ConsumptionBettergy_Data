# SmartHouse_BettergyData
Repositorio de datos utilizados en las simulaciones del trabajo fin de Máster "Optimización de sistemas de generación fotovoltaica con almacenamiento". Los datasets utilizados están disponibles en ficheros en formato Excel y CSV.

**REPOSITORIO: DATOS DE CONSUMO y GENERACIÓN DE UNA SMART HOUSE UBICADA EN EL SUR DE ESPAÑA**
Este repositorio contiene los datos utilizados en las simulaciones de un edificio inteligente situado en el sur de España, proporcionados por la empresa Bettergy. Los datos están organizados en varios DATASETS.

**Listado de Datasets Utilizados**
- Dataset1: Set de datos del caso base original. Este conjunto de datos representa las condiciones originales del edificio sin modificaciones en la generación de energía fotovoltaica (FV).
- Dataset2: Generación FV reducida a la mitad respecto al caso base. Aquí se simula una situación donde la generación de energía fotovoltaica es un 50% menor que en el caso base, permitiendo el análisis de escenarios con menor generación de energía solar.
- Dataset3: Generación FV duplicada respecto al caso base. Este conjunto de datos refleja una generación de energía fotovoltaica duplicada en comparación con el caso base, lo cual es útil para evaluar el impacto de una mayor disponibilidad de energía solar.
- Dataset0a: Generación FV nula. Representa un escenario sin generación de energía fotovoltaica, proporcionando un punto de referencia para comparar con otros datasets que incluyen generación solar.
- Dataset_periods1: Discriminación horaria de 3 periodos con oscilación moderada en el precio de la energía. Valle: Precio reducido al 50%; Plana: Precio sin cambios; Pico: Precio multiplicado por dos.
- Dataset_periods2: Discriminación horaria de 3 periodos con fuerte oscilación en el precio de la energía. Valle: Precio reducido al 25%; Plana: Precio sin cambios; Pico: Precio multiplicado por cuatro.

**Campos Datasets**
-	Timestamp: Resolución cuartohoraria
-	Consumption: Consumo en kWh
-	Generation: Generación FV en kWh
-	Price_buy: Precio de compra de energía a red en €
-	Price_sold: Precio de venta de energía a red en €
-	Price_shed: Precio de energía de deslastre en €
-	Power: Potencia contratada en kW
-	Period: Periodo de facturación de energía en tarifas con discriminación horaria (1:valle; 2:llano; 3:pico).
