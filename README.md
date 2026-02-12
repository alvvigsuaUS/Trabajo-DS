# Fuente de los datos

Los datos estan sacados del portal de transparencia de la universidad de sevilla, concretamente de la sección 1.5 (Datos Académicos)

<https://transparencia.us.es/informacion-institucional>

## Datasets

- Abandono y rendimiento
- Matriculados y aprobados
- Satisfacción

### Abandono/Rendimiento

```
    abandono_rendimiento
    ├── abandono
    │  ├── abandono_2017_2018.xlsx
    │  ├── abandono_2018_2019.xlsx
    │  ├── abandono_2020_2021.xlsx
    │  ├── abandono_2021_2022.xlsx
    │  ├── abandono_2022_2023.xlsx
    │  └── abandono_2023_2024.xls
    ├── rendimiento
    │  ├── rendimiento_2017_2018.xlsx
    │  ├── rendimiento_2018_2019.xlsx
    │  ├── rendimiento_2020_2021.xlsx
    │  ├── rendimiento_2021_2022.xlsx
    │  ├── rendimiento_2022_2023.xlsx
    │  └── rendimiento_2023_2024.xls
    └── abandono_rendimiento_2019_2020.xlsx
```



#### Preview de abandono (2023-2024)

| Cod. Cent. | Cod. Tit. | Titulación | 1.11 | 1.11(numerador) | 1.11(denominador) |
|:---:|:---:|---|---:|---:|---:|
| 1 | 151 | Grado en Administración y Dirección de Empresas | 37.92 % | 182 | 480 |
| 5 | 153 | Grado en Biología | 14.08 % | 29 | 206 |
| 18 | 154 | Grado en Ciencias de la Actividad Física y del Deporte | 13.22 % | 16 | 121 |
| 20 | 155 | Grado en Derecho | 14.48 % | 74 | 511 |
| 1 | 156 | Grado en Economía | 31.10 % | 51 | 164 |
| 11 | 157 | Grado en Enfermería | 21.72 % | 58 | 267 |
| 19 | 158 | Grado en Farmacia | 19.58 % | 56 | 286 |
| 16 | 159 | Grado en Filología Hispánica | 28.79 % | 38 | 132 |
| 12 | 160 | Grado en Filosofía | 96.20 % | 76 | 79 |
| 7 | 161 | Grado en Finanzas y Contabilidad | 51.26 % | 163 | 318 |

![Preview de abandono (2023-2024)](images/captura%20abandono.png)

**Numero de filas inconsistente (media de 200)**

**Para el mismo año abandono y rendimiento tienen el mismo numero de filas**

#### Preview de rendimiento (2023-2024)

| Cod. Cent. | Cod. Tit. | Titulación | 1.6 | 1.6(numerador) | 1.6(denominador) |
|:---:|:---:|---|---:|---:|---:|
| 1 | 151 | Grado en Administración y Dirección de Empresas | 58.60 % | 69042.0 | 117828.0 |
| 5 | 153 | Grado en Biología | 76.16 % | 41340.0 | 54282.0 |
| 18 | 154 | Grado en Ciencias de la Actividad Física y del Deporte | 88.29 % | 17514.0 | 19836.0 |
| 20 | 155 | Grado en Derecho | 70.95 % | 100311.0 | 141378.0 |
| 1 | 156 | Grado en Economía | 63.75 % | 26490.0 | 41556.0 |
| 11 | 157 | Grado en Enfermería | 88.18 % | 61371.0 | 69594.0 |
| 19 | 158 | Grado en Farmacia | 66.65 % | 2512.5 | 3769.5 |
| 16 | 159 | Grado en Filología Hispánica | 64.16 % | 20700.0 | 32262.0 |
| 12 | 160 | Grado en Filosofía | 40.00 % | 96.0 | 240.0 |
| 7 | 161 | Grado en Finanzas y Contabilidad | 48.02 % | 33348.0 | 69450.0 |

![Preview de rendimiento (2023-2024)](images/captura%20rendimiento.png)

**Numero de filas inconsistente (media de 200)**

**Para el mismo año abandono y rendimiento tienen el mismo numero de filas**

#### Preview de abandono y rendimiento (2019-2020)

| Titulación | 1.6_Tasa Rendimiento | 1.6(numerador) | 1.6(denominador) | 1.11_Tasa Abandono | 1.11(numerador) | 1.11(denominador) |
|---|---:|---:|---:|---:|---:|---:|
| Grado en Administración y Dirección de Empresas | 68.49% | 74334 | 108534 | 37.07% | 182 | 491 |
| Grado en Biología | 80.26% | 43152 | 53766 | 17.45% | 37 | 212 |
| Grado en Ciencias de la Actividad Física y del Deporte | 91.26% | 19542 | 21414 | 10.29% | 7 | 68 |
| Grado en Derecho | 81.45% | 110028 | 135081 | 16.12% | 93 | 577 |
| Grado en Economía | 67.81% | 25446 | 37524 | 31.71% | 52 | 164 |
| Grado en Enfermería | 80.15% | 44349 | 55335 | 21.46% | 53 | 247 |
| Grado en Farmacia | 81.72% | 68215.5 | 83473.5 | 14.97% | 44 | 294 |
| Grado en Filología Hispánica | 72.91% | 21480 | 29460 | 30.28% | 43 | 142 |
| Grado en Filosofía | 77.67% | 11832 | 15234 | 30.14% | 22 | 73 |
| Grado en Finanzas y Contabilidad | 56.17% | 42258 | 75228 | 47.32% | 203 | 429 |

![Preview de abandono y rendimiento (2019-2020)](images/captura%20abandono%20rendimiento.png)

**Contiene 178 filas**

### Matriculado/Aprobado

```
    matriculado_aprobado
    └── matriculado_aprobado_2017_2018_a_2023_2024.xls
```

#### Preview de matriculado aprobado

| Cód. | Centro | Nombre Título | código nombre asignatura | Nº matriculados | Nº presentados | Nº no presentados | Nº que superan | Tasa SUPERA/MAT | Nº de MH | Nº de SOB | Nº de NOT | Nº de APR | Nº de suspensos | Curso |
|:---:|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510001-Estadística | 575 | 483 | 92 | 317 | 55.1 % | 3 | 4 | 60 | 250 | 166 | 2017-18 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510001-Estadística | 605 | 484 | 121 | 279 | 46.1 % | 8 | 17 | 57 | 197 | 205 | 2018-19 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510001-Estadística | 640 | 483 | 157 | 333 | 52.0 % | 5 | 16 | 111 | 201 | 150 | 2019-20 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510001-Estadística | 668 | 505 | 163 | 299 | 44.8 % | 1 | 4 | 73 | 221 | 206 | 2020-21 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510001-Estadística | 721 | 502 | 219 | 305 | 42.3 % | 8 | 4 | 60 | 233 | 197 | 2021-22 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510001-Estadística | 774 | 501 | 273 | 245 | 31.7 % | 5 | 5 | 58 | 177 | 256 | 2022-23 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510001-Estadística | 847 | 606 | 241 | 392 | 46.28% | 3 | 5 | 75 | 309 | 213 | 2023-24 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510002-Finanzas | 764 | 494 | 270 | 267 | 34.9 % | 4 | 6 | 36 | 221 | 227 | 2017-18 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510002-Finanzas | 797 | 460 | 337 | 298 | 37.4 % | 11 | 3 | 87 | 197 | 162 | 2018-19 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510002-Finanzas | 733 | 642 | 91 | 573 | 78.2 % | 1 | 14 | 177 | 381 | 69 | 2019-20 |
| 1 | Facultad de CC. Económ. y Empresariales | Grado en Administración y Dirección de Empresas | 1510002-Finanzas | 549 | 437 | 112 | 363 | 66.1 % | 0 | 8 | 77 | 278 | 74 | 2020-21 |

![Preview de matriculado aprobado](images/captura%20matriculado%20aprobado.png)

**Contiene 63883 filas**

### Satisfacción

```
    satisfaccion
    ├── grado
    │  ├── satisfaccion_2017_2018_grado.pdf
    │  ├── satisfaccion_2018_2019_grado.pdf
    │  ├── satisfaccion_2019_2020_grado.pdf
    │  ├── satisfaccion_2020_2021_grado.pdf
    │  └── satisfaccion_2021_2022_grado.pdf
    └── master
    ├── satisfaccion_2017_2018_master.pdf
    ├── satisfaccion_2018_2019_master.pdf
    ├── satisfaccion_2019_2020_master.pdf
    ├── satisfaccion_2020_2021_master.pdf
    └── satisfaccion_2021_2022_master.pdf
```

#### Preview de satisfacción grado (2021-2022)

![Preview de satisfacción grado (2021-2022)](images/captura%20satisfaccion%20grado%201.png)

![Preview de satisfacción grado (2021-2022)](images/captura%20satisfaccion%20grado%202.png)

#### Preview de satisfacción máster (2021-2022)

![Preview de satisfacción máster (2021-2022)](images/captura%20satisfaccion%20master%201.png)

![Preview de satisfacción máster (2021-2022)](images/captura%20satisfaccion%20master%202.png)
