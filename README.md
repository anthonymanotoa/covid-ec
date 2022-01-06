# ¿Cómo afectó el Covid 19 a la educación (básica y secundaria) en Ecuador?

> Este proyecto fue realizado en Deepnote. Puedes utilizar Deepnote para trabajar interactivamente con los notebooks siguiendo el enlace de este botón:

[<img src="https://deepnote.com/buttons/launch-in-deepnote-white.svg">](https://deepnote.com/launch?url=https%3A%2F%2Fgithub.com%2Fanthonymanotoa%2Fcovid-ec)

Análisis de datos de la evolución del Covid 19 en Ecuador y su afectación a la educación básica y secundaria. En el [notebook de análisis](https://github.com/anthonymanotoa/covid-ec/blob/main/notebooks/3.1-python-analysis.ipynb) se responden las siguientes preguntas:
- ¿Cómo se relaciona el cierre de los centros educativos y las vacunas con los casos positivos y fallecimientos diarios debido al Covid-19?
- ¿Cuál es el progreso histórico de los estudiantes en Ecuador y cómo ha visto afectado durante la pandemia?
- Con base en los datos de educación: ¿Qué grupo social fue el más afectado por la crisis? ¿Qué pasó con los otros grupos?

También puedes ver el análisis publicado en Deepnote: [Covid y educación](https://deepnote.com/@anthonymanotoa/Covid-19-y-educacion-en-Ecuador-57BI3_ybSXCqiN8VOycKbw)

Estas son, entre otras, algunas de las conclusiones más importantes encontradas:
- El último año, en gran parte debido a la pandemia, **75.566 niños y jóvenes abandonaron sus estudios**.
- **159.024 estudiantes** migraron de una educación particular/fiscomisional a una fiscal como resultado de la crisis.

## Data
_Covid data_ extraída de:
- [Ecuacovid](https://github.com/andrab/ecuacovid)
- [CSSE at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)

_Education data_ extraída de:
- [UNESCO](https://en.unesco.org/covid19/educationresponse)
- [Gobierno de Ecuador](https://educacion.gob.ec/base-de-datos/)

## Notebooks
Los notebooks están divididos entre los datos de covid y educación siguiendo este patrón:
0) Extracción
1) Procesamiento
2) Exploración
3) Analisis

## Project organization

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks. Naming convention: number (for ordering),
│   ├── 0. extraction     topic, delimited description, e.g.
│   ├── 1. process        `1.1-covid-data_process.ipynb`.
│   ├── 2. exploration
│   └── 3. analysis
│
└── requirements.txt   <- The requirements file for reproducing the analysis environment.
```
