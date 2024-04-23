---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Resultados y conclusiones

A lo largo del análisis y modelado de datos de inmuebles, se llevaron a cabo diversas etapas de limpieza y preprocesamiento para asegurar la calidad y precisión de los modelos predictivos.

## Limpieza y Preprocesamiento de Datos

- **Identificación y Corrección de Atípicos**: Se emplearon métodos robustos como las pruebas de Rosner, IQR y Z-score para identificar y manejar valores atípicos en características críticas como el precio, la superficie y la ubicación, marcándolos como nulos o ajustándolos según los límites razonables de cada ciudad.
- **Imputación de Datos Nulos**: La imputación fue un desafío notable, especialmente debido a la complejidad de los datos de localización (latitud y longitud) y las características inherentes de los inmuebles como área construida y número de habitaciones. Se utilizaron técnicas avanzadas como IterativeImputer y modelos KNN para imputar estos datos, asegurando que los modelos predictivos funcionaran con conjuntos de datos completos.
- **Limpieza de Datos por Ciudad**: Se definieron y aplicaron límites específicos de latitud y longitud para cada ciudad para asegurar que las ubicaciones de los inmuebles fueran precisas, eliminando registros que se encontraban fuera de estos rangos permitidos.

## Modelado Predictivo y Resultados

Los modelos evaluados incluyeron Ridge, Lasso, XGBoost y MLP, mostrando una variedad en desempeño que culminó en una destacada actuación del modelo XGBoost, que presentó el menor MAPE y el RMSE más bajo, junto con el más alto valor de R², indicando una excelente capacidad predictiva respecto al precio de los inmuebles en comparación con los demás modelos.

## Utilidad para Inmobiliarias y Compradores/Vendedores

- **Inmobiliarias**: El uso de estos modelos puede ayudar a las inmobiliarias a establecer precios precisos y competitivos en el mercado, optimizar sus estrategias de inventario según las predicciones de áreas de alta demanda y mejorar la satisfacción del cliente al proporcionar estimaciones precisas y personalizadas.
- **Compradores y Vendedores**: Los modelos pueden ofrecer a los compradores una herramienta para verificar si los precios de los inmuebles están en línea con el mercado, ayudándoles a tomar decisiones informadas. Para los vendedores, proporciona una base para establecer precios de venta que maximicen sus posibilidades de transacción favorablemente y en tiempos óptimos.

## Conclusión

El proceso detallado de limpieza y modelado de datos no solo mejoró la calidad de los datos con los que trabajaron los modelos predictivos, sino que también demostró la importancia de una buena práctica de gestión de datos en el ámbito inmobiliario. El modelo XGBoost, en particular, demostró ser excepcionalmente efectivo, destacando su utilidad en aplicaciones inmobiliarias tanto para análisis de mercado como para toma de decisiones estratégicas. Esta metodología ofrece un enfoque replicable y escalable que puede adaptarse a diferentes mercados y necesidades de datos, lo que es crucial en un sector tan dinámico como el inmobiliario.