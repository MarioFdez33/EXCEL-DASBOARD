# 📈 ANÁLISIS DE LAS VENTAS DE CONCESIONARIOS EN USA 🇺🇸

## ÍNDICE: 
-a) Descripción del proyecto 
-b)Definir las hipótesis
-c) Estructura del proyecto
-d) Resultados y conclusiones

### 1. Descripción del proyecto
Este proyecto lleva a cabo un análisis de las ventas de varios concesionarios en EE.UU durante el año 2022. El objetivo del mismo es crear un tablero con el que podamos ver a simple vista la información básica de las ventas: concesionario con más ventas, coche más vendido, concesionario que peor le va, etc.

### 2. Hipótesis
La idea principal de este análisis es situarnos en supuesto contexto donde vayamos a abrir un concersionario en un estado de EE.UU pero no sabemos en cual hacerlo, ni tampoco qué vehíuclo comprar y qué características deben tener estos. 
#### 2.1) Definimos las hipótesis
Al ser un país con un nivel adquisitivo ciertamente algo, el precio medio por unidad será de unos 35.000€
La marca más vendida será una marca con un precio medio no muy elevado (Toyota, Hynduai, Honda...)
La mayor concertración de ventas se darán a final de año, donde muchos concesionarios ofrecen descuentos por liquidez.
Habrá una diferencia nottoria de ventas de vehículos automáticos frente a la venta de manuales
Habrá una distribución equitativa del porcentaje de ventas por tipo de coche (a excepción de modelos menos típicos con el Hardtop)

### 3. Estructura del proyecto 
#### 3.1)Limpieza de los datos
En una primera instancia, los datos importados incluían columnas irrelevantes para el análisis como el teléfono del cliente, el nombre o el género del mismo. Limpiamos esos datos y también valores duplicados (no había ninguno).
#### 3.2) Transformación de los datos
Después de traducir el nombre de las columnas al español
Tras acabar con la limpieza de los datos, hice una lectura general. A continuación cambiará el tipo de cada una de las columnas (fecha, número, moneda...).
Seguidamente quise cambiar la palabra "Auto" en la columna de cambio por Automático
Despues vi que la columna de color tenia solo 3 colores, los cuales tambien traduje al español
#### 3.3) Análisis descriptivo
A continuación creamos una hoja nueva donde incluiremos todas las tablas y gráficos dinámicos.
Para saber que análisis hacer a los contenidos, hice uso de la inteligencia artificial: le pasé los nombres de cada una de las columnas y le pregunté qué información podría ser relevante para analizar. CHATGPT respondió "Total de vehículos vendidos, Ingreso total por ventas, Precio medio por vehículo, % de cambio (auto/manual) y Modelo y marca más vendida. También sugirió algunos gráficos como ventas/mes, ventas por región, modelos mas vendidos, concesionarios con más ventas..."
Ahora lo que hacemos es ir generando todas las tablas dinámicas que nos van a ser de utilidad y en algunas de ellas creamos a su vez unos gráficos dinámicos.
Vamos poniendo el nombre a cada tabla dinámica (MUY IMPORTANTE)⚠️
Una vez tengamos toda la información organizada y los gráficos creados, creamos una pestaña donde irá el tablero
Añadimos figuras para hacerlo bonito, lo reestructuramos y organizamos con la información de los gráficos y tablas dinámicas y... ¡LISTO!

### 4. Resultados y conclusiones -Analicemos una a una nuestras hipótesis... 
#### 4.1) Análisis de hipótesis
Pensamos que el precio medio seria de 35.000€ --> resultó ser de 28.090€
Pensamos que la marca más vendida seria una marca de gama media --> resultó ser dos de gama alta
Pensamos que la mayor concertración de ventas se darían a final de año --> diciembre es el mejor mes
Pensamos que habría una distribución equitativa del porcentaje de ventas por tipo de coche --> resultó ser cierto
Pensamos que habría una diferencia equitativa también en la transmisión de ls vehículos vendidos --> resultó ser cierto
#### 4.2) Conclusiones
En definitiva, si tuviéramos que abrir una tienda sería en Austin, Texas, lugar donde se han dado el mayor número de ventas. No haríamos ninguna distinción en la transmisión de los vehículos que comprendamos pero sí en la gama de estos. Buscaremos vehículos de gama media-alta, donde casi la mitad deberá ser de color blanco. Sería buena idea hacer uso de promociones en otros meses que el resto de concersionarios los cuales hacen ofertas únicamente en diciembre. Las marcas menos venidas en este estado han sido Infinity y Jaguar, una información de mucha utilidad para saber que marcas de vehículos no debemos importar tan masivamente como sí haríamos con Dodge, Chevrolet, Ford o Volkswagen.
