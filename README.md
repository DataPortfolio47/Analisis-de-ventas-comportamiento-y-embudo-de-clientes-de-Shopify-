# 📊 Análisis de ventas, Comportamiento y Embudo de Clientes de Shopify 

![Dashboard de Ventas de Shopify](Dashboard.png)

## Contexto del Proyecto

Desarrollé este proyecto para analizar todas las operaciones de compra y el comportamiento de los clientes en una tienda de comercio electrónico que usa Shopify. El dashboard procesa un total de $4.18 millones en ventas netas y 7,534 unidades vendidas. Este proyecto  estudia qué tan bien funcionan las pasarelas de pago, donde Shopify Payments representa el 58.45% de los ingresos. También muestra cuáles son las categorías de producto más rentables, como lo fue el calzado deportivo.

El propósito fue crear un panel interactivo que muestre el rendimiento según los métodos de pago, las categorías de producto, la distribución geográfica con un mapa regional y un ranking por ciudades como Washington, Houston y New York. También incluye el comportamiento por días y horas de tráfico. Esto permite a la gerencia ver tanto la tracción operativa como la lealtad de los clientes.

Este proyecto estudia el rendimiento de las transacciones, la distribución geográfica de ventas y el comportamiento de compra de 4,431 clientes en Shopify. El equipo de operaciones y marketing necesita estos datos para encontrar los mercados con más conversiones. También los usan para mejorar las estrategias de retención de clientes habituales y ajustar los horarios de mayor venta para aumentar los ingresos.

El análisis mostró que las ventas netas llegaron a $4.18M. La categoría de calzado deportivo, especialmente Running Shoes con $1.5M, fue la principal causa. Aunque hay muchos clientes que vuelven a comprar, con una tasa de recurrencia del 46%, más de la mitad de los compradores, 2,392 de 4,431, solo han hecho un pedido. Shopify Payments es el método de pago más usado por los clientes, con un 58.45%. También se vio que los ingresos se concentran mucho en ciudades clave como Washington y Houston.

## 🛠️ Herramientas Utilizadas

- Excel: Limpieza y transformación de datos con Power Query.

- DAX (Data Analysis Expressions): Creé medidas dinámicas para calcular métricas de rendimiento transaccional, comportamiento del cliente (Lifetime Value, tasa de compra recurrente, frecuencia de compra) y lógica de selección de medidas.

- Power BI: Creé un panel de control interactivo que muestra mapas de densidad geográfica, gráficos de tendencia temporal, pasarelas de pago y filtrado cruzado dinámico entre visualizaciones. 

Analicé el conjunto de datos de transacciones de Shopify. Me enfoqué en el rendimiento por región, por periodos de tiempo y por tipo de cliente. Clasifiqué a los usuarios en compradores únicos y compradores habituales para ver métricas de retención como el LTV ($943.6) y la frecuencia de compra (1.68). Después, agrupé las ventas netas por pasarelas de pago, categorías de productos y ubicaciones como estados y ciudades en EE. UU. Crucé estos datos con las marcas de tiempo por día y hora para encontrar los momentos con mayor conversión operativa.

## Conclusiones Principales 

- Dominio de la categoría principal: Las líneas de calzado deportivo, como Running Shoes, Tennis Shoes y Walking Shoes, generan la gran mayoría de los $4.18M en ventas netas totales. Categorías como accesorios o prendas secundarias representan una porción mínima del volumen comercial.

- Oportunidad en la retención de clientes: Aunque hay una tasa de recurrencia notable del 46% (2,039 clientes habituales), el 54% de la base total de clientes (2,392 de 4,431) ha hecho solo un pedido. Esto muestra que hay mucho espacio para aumentar la lealtad de compra.

- La mayoría de las transacciones ocurren en solo dos canales de pago. Shopify Payments tiene el 58.45% y PayPal el 16.29%. En conjunto, casi el 75% de las transacciones pasan por estas dos opciones.
 
- Picos temporales de conversión: Las transacciones cambian su comportamiento en días concretos del mes. También hay concentraciones claras de tráfico en ciertas franjas horarias. Esto permite prever los momentos de mayor volumen operacional.
