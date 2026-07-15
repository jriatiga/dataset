# Gobernanza

## Framework V7 - Ciencia de Datos para la Gestión Hídrica

### Información general

| Campo | Valor |
|--------|-------|
| Capa | Gobernanza |
| Código | GOB |
| Versión | 1.0 |
| Responsable | Juan Carlos Riatiga |

---

## Descripción

La Capa de Gobernanza consolida indicadores demográficos, económicos e institucionales asociados a los municipios objeto de estudio del Framework para la Gestión Hídrica.

La información fue integrada a partir de múltiples conjuntos de datos abiertos publicados por la Gobernación de Cundinamarca y posteriormente transformada a un formato tabular maestro con un registro por municipio y año.

Esta capa permite complementar la información climática, hidráulica y de percepción incorporando variables relacionadas con el contexto socioeconómico e institucional de cada territorio.

---

## Cobertura

Municipios incluidos

- CHIA
- SOPO
- TOCANCIPA
- VILLAPINZON

Cobertura temporal

2020 - 2024

Número de registros

20

Número de variables

22

---

## Variables principales

- POBLACION TOTAL
- DENSIDAD POBLACIONAL
- PORCENTAJE POBLACION URBANA
- PORCENTAJE POBLACION RURAL
- PRODUCTO INTERNO BRUTO DEPARTAMENTAL
- INDICE DE DESEMPENO INSTITUCIONAL
- ACCESO A AGUA POTABLE ADECUADO
- PORCENTAJE DE LA POBLACION CON ACCESO A METODOS DE SANEAMIENTO ADECUADOS
- COBERTURA DE ACUEDUCTO URBANO
- COBERTURA DE ACUEDUCTO RURAL
- COBERTURA DE ALCANTARILLADO URBANO
- COBERTURA DE ALCANTARILLADO RURAL
- CONTINUIDAD DE ACUEDUCTO URBANO
- CALIDAD DEL AGUA
- AGUAS RESIDUALES TRATADAS

---

## Transformaciones realizadas

- Integración de tres conjuntos de datos oficiales.
- Selección de indicadores de gobernanza relevantes para el proyecto.
- Filtrado de los municipios objeto de estudio.
- Conversión del formato largo a formato ancho mediante tabla pivote.
- Estandarización de nombres de municipios.
- Conversión de tipos de datos.
- Generación de identificadores del Framework.
- Validación estructural.
- Generación de metadatos.
- Elaboración del diccionario de datos.
- Auditoría de calidad.
- Construcción de indicadores descriptivos.
- Análisis exploratorio de datos (EDA).

---

## Fuentes de información

Portal de Datos Abiertos de Cundinamarca

https://datosmintic-cundinamarca-map.hub.arcgis.com/

Conjuntos utilizados

- SERVICIOS_PUBLICOS.xlsx
- ECONOMIA.xlsx
- DESCRIPCION_GENERAL.xlsx

---

## Archivo generado

01_Capa_Gobernanza_V1.xlsx

---

Framework V7
Proyecto de Maestría
Ciencia de Datos aplicada a la Gestión Hídrica
