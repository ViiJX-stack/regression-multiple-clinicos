# Regresión y correlación múltiple para clínicos

Material docente con datos abiertos de la NASA (tripulación civil de Inspiration4) para enseñar regresión múltiple, variables indicadoras, medidas repetidas y correlación desde el punto de vista del médico.

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ViiJX-stack/regression-multiple-clinicos/blob/main/clase_regresion_nasa.ipynb)

## Cómo usarlo
1. Haga clic en **Abrir en Colab**.
2. Menú **Entorno de ejecución → Ejecutar todas**. No necesita instalar nada.

## Contenido
| Archivo | Descripción |
|---|---|
| `clase_regresion_nasa.ipynb` | Cuaderno de la clase (Python, comentarios en español) |
| `i4_analysis.csv` | 28 muestras (4 tripulantes × 7 momentos), con reglas de calidad aplicadas |

## Qué se enseña
- Variables categóricas como variables indicadoras (dummies).
- Medidas repetidas: modelo ingenuo vs regresión múltiple con el tripulante vs modelo mixto.
- Coeficiente de correlación intraclase y correlación múltiple (R).
- Supuestos revisados con residuos.
- Correlación entre personas vs dentro de cada persona.
- Calidad de datos: glucólisis in vitro en la toma R+45.
- Equivalencias en SPSS.

**Advertencia:** análisis exploratorio con fines didácticos; no debe usarse para decisiones clínicas.

## Fuentes de datos
- NASA Open Science Data Repository: OSD-569 (doi:10.26030/e0rx-sh52) y OSD-575 (doi:10.26030/mc5d-p710).
- Archivo derivado y código del estudio original: https://osf.io/57cdk
- Preregistro: https://doi.org/10.17605/OSF.IO/W3NP2
- Preprint: https://doi.org/10.64898/2026.10.16.26365757

## Ciencia abierta
Este material sigue las prácticas de ciencia abierta del curso:
- NASA Open Science Training Team. (2025). *Open Science 101*. NASA. https://science.nasa.gov/open-science/training/

## Licencia
Texto y datos derivados: CC BY 4.0. Código: MIT. Ver `LICENSE`.

## Cómo citar
Ver `CITATION.cff` o el botón **Cite this repository** de GitHub.

*Elaborado con asistencia de IA (Claude, Anthropic); el autor revisó el contenido y es responsable de él.*
