# 📊 Análisis de ventas, Comportamiento y Embudo de Clientes de Shopify 

![Dashboard de Ventas de Shopify](Dashboard.png)

## Contexto del Proyecto

Desarrollé este proyecto para analizar las compras y el comportamiento de 4,431 clientes de una tienda Shopify. El dashboard muestra el rendimiento por método de pago, categoría de producto, ubicación geográfica (mapa regional y ranking de ciudades) y patrones de tráfico por día y hora. Está pensado para ayudar a que los equipos de operaciones y marketing encuentren los mercados con mayor conversión, mejoren la retención de clientes recurrentes y ajusten los horarios de mayor venta.

Dividí a los clientes en compradores únicos y habituales. Relacioné las ventas netas con la pasarela de pago, la categoría de producto, la ubicación y la marca de tiempo, que incluye el día y la hora, durante una ventana de 7 días, del 18 al 24. 

## 🛠️ Herramientas Utilizadas

- Excel: Limpieza y transformación de datos con Power Query.

- DAX (Data Analysis Expressions): Creé medidas dinámicas para calcular métricas de rendimiento transaccional, comportamiento del cliente (Lifetime Value, tasa de compra recurrente, frecuencia de compra) y lógica de selección de medidas.

- Power BI: Creé un panel de control interactivo que muestra mapas de densidad geográfica, gráficos de tendencia temporal, pasarelas de pago y filtrado cruzado dinámico entre visualizaciones. 

Analicé el conjunto de datos de transacciones de Shopify. Me enfoqué en el rendimiento por región, por periodos de tiempo y por tipo de cliente. Clasifiqué a los usuarios en compradores únicos y compradores habituales para ver métricas de retención como el LTV ($943.6) y la frecuencia de compra (1.68). Después, agrupé las ventas netas por pasarelas de pago, categorías de productos y ubicaciones como estados y ciudades en EE. UU. Crucé estos datos con las marcas de tiempo por día y hora para encontrar los momentos con mayor conversión operativa.

## Conclusiones Principales 

- Ventas: $4.18M netos. Se vendieron 7,534 unidades, y el valor promedio por pedido fue de $562.6.

- Calzado deportivo lidera: Running (1.5M),Tennis(0.9M) y Walking ($0.6M) suman cerca del 72% de las ventas. Accesorios y prendas secundarias aportan una porción mínima.

- La mayoría de las transacciones ocurren en solo dos canales de pago. Shopify Payments tiene el 58.45% y PayPal el 17.62%. En conjunto, casi el 75% de las transacciones pasan por estas dos opciones.
 
- Picos temporales de conversión: Las transacciones cambian su comportamiento en días concretos del mes. También hay concentraciones claras de tráfico en ciertas franjas horarias. Esto permite prever los momentos de mayor volumen operacional.
