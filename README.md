# Regresión y correlación múltiple para clínicos · Multiple regression and correlation for clinicians

Material docente con datos abiertos de la NASA (tripulación civil de Inspiration4) para enseñar regresión múltiple, variables indicadoras, medidas repetidas y correlación desde el punto de vista del médico.

*Teaching material using NASA open data (the Inspiration4 civilian crew) to teach multiple regression, indicator variables, repeated measures and correlation from a physician's point of view.*

| Idioma / Language | Abrir / Open |
|---|---|
| Español | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ViiJX-stack/regression-multiple-clinicos/blob/main/clase_regresion_nasa.ipynb) |
| English | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ViiJX-stack/regression-multiple-clinicos/blob/main/clase_regresion_nasa_EN.ipynb) |

**Cómo usarlo / How to use:** abra el cuaderno en Colab y use *Entorno de ejecución → Ejecutar todas* · open the notebook in Colab and use *Runtime → Run all*. No installation needed.

## Contenido / Contents
| Archivo / File | Descripción / Description |
|---|---|
| `clase_regresion_nasa.ipynb` | Cuaderno en español (Python) |
| `clase_regresion_nasa_EN.ipynb` | Notebook in English (Python) |
| `i4_analysis.csv` | 28 muestras / samples (4 tripulantes / crew members × 7 momentos / timepoints), con reglas de calidad aplicadas / with quality rules applied |

## Qué se enseña / What is taught
- Variables categóricas como indicadoras (dummies) · categorical variables as indicators (dummies)
- Medidas repetidas: modelo ingenuo vs regresión múltiple con el tripulante vs modelo mixto · repeated measures: naive model vs multiple regression with the crew member vs mixed model
- Correlación intraclase y correlación múltiple (R) · intraclass correlation and multiple correlation (R)
- Supuestos revisados con residuos · assumptions checked with residuals
- Correlación entre personas vs dentro de cada persona · between- vs within-person correlation
- Calidad de datos: glucólisis in vitro en R+45 · data quality: in-vitro glycolysis at R+45
- Equivalencias en SPSS · SPSS equivalents

**Advertencia / Caution:** análisis exploratorio con fines didácticos; no debe usarse para decisiones clínicas · exploratory teaching analysis; not for clinical decisions.

## Fuentes de datos / Data sources
- NASA Open Science Data Repository: OSD-569 (doi:10.26030/e0rx-sh52), OSD-575 (doi:10.26030/mc5d-p710)
- Archivo derivado y código del estudio original / Derived file and code of the original study: https://osf.io/57cdk
- Preregistro / Preregistration: https://doi.org/10.17605/OSF.IO/W3NP2
- Preprint: https://doi.org/10.64898/2026.10.16.26365757

## Lecturas previas / Pre-reading
- Swinscow TDV, Campbell MJ. *Statistics at Square One*. 9th ed. BMJ; 1997. Chapter 11: Correlation and regression. https://www.bmj.com/about-bmj/resources-readers/publications/statistics-square-one/11-correlation-and-regression (edición vigente / current edition: Campbell MJ. 12th ed. Wiley; 2021)
- UNC Eshelman School of Pharmacy. Biostatistics, Lesson 6: Continuous outcomes, linear regression. https://wp.media.unc.edu/biostatistics/lesson-6-continuous-outcomes-linear-regression/

## Ciencia abierta / Open science
- NASA Open Science Training Team. (2025). *Open Science 101*. NASA. https://science.nasa.gov/open-science/training/

## Licencia / License
Texto y datos derivados / Text and derived data: CC BY 4.0. Código / Code: MIT. Ver / See `LICENSE`.

## Cómo citar / How to cite
DOI: [10.5281/zenodo.23649828](https://doi.org/10.5281/zenodo.23649828) · Ver / See `CITATION.cff` or GitHub's **Cite this repository**.

*Elaborado con asistencia de IA (Claude, Anthropic); el autor revisó el contenido y es responsable de él · Prepared with AI assistance (Claude, Anthropic); the author reviewed the content and is responsible for it.*
