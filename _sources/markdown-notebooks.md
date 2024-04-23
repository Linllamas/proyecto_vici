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

# Fuente de datos y variables

Los datos utilizados en nuestra aplicación fueron obtenidos de Kaggle, específicamente del conjunto de datos titulado "Data of properties for sale in Colombia from 2021". Este conjunto de datos, disponible en [este enlace](https://www.kaggle.com/datasets/angeloftechml/data-of-properties-for-sale-in-colombia-from-2021), fue recopilado mediante técnicas de scraping de las páginas web de **MetroCuadrado** y **Finca Raíz**, dos de los principales portales inmobiliarios en Colombia. Esta fuente ofrece una amplia variedad de información sobre propiedades en venta en Colombia, incluyendo detalles como ubicación geográfica, características de la propiedad y precios actualizados.

## Variables
- **lat**: Latitud geográfica de la ubicación de la propiedad.
- **long**: Longitud geográfica de la ubicación de la propiedad.
- **category**: Categoría de la propiedad (casa, apartamento, apartaestudio).
- **price**: Precio de venta de la propiedad en pesos colombianos.
- **rooms**: Número de habitaciones en la propiedad.
- **baths**: Número de baños en la propiedad.
- **park**: Número de espacios de estacionamiento disponibles.
- **ciudad**: Ciudad donde se encuentra la propiedad.
- **barrio**: Barrio o sector donde se encuentra la propiedad.
- **area_privada**: Área privada de la propiedad en metros cuadrados.
- **area_const**: Área construida de la propiedad en metros cuadrados.
- **admon**: Valor de la administración (cuota de mantenimiento) en pesos colombianos.
- **Estrato**: Estrato socioeconómico de la propiedad.
- **Estado**: Estado físico de la propiedad (Bueno, Excelente, Regular).
- **Antiguedad**: Rango de antigüedad de la propiedad.
- **Tipo de Apartamento**: Tipo de apartamento (Loft, Duplex, Penthouse).
- **Sector**: Sector específico donde se encuentra la propiedad.
