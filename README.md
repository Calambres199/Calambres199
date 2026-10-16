<div align="center">

# Jared Sánchez Martínez

**Estudiante de la Licenciatura en Matemáticas Aplicadas · Línea de Ciencias Computacionales**
Universidad Autónoma del Estado de Hidalgo · Instituto de Ciencias Básicas e Ingeniería

*Tepa, Hidalgo, México*

[![GitHub](https://img.shields.io/badge/GitHub-Calambres199-181717?style=flat-square&logo=github)](https://github.com/Calambres199)
[![UAEH](https://img.shields.io/badge/UAEH-ICBI-6E1428?style=flat-square)](https://www.uaeh.edu.mx/campus/icbi/oferta/licenciaturas/lic_mat/nosotros.html)

</div>

---

## Sobre mí

Estudio Matemáticas Aplicadas en el **Área Académica de Matemáticas y Física** del ICBI, UAEH, con énfasis en la **línea de Computación**. Me interesa la parte computacional de la matemática: diseñar algoritmos que resuelvan problemas de forma exacta y eficiente, analizar su complejidad e implementar métodos numéricos y estadísticos que trabajen con datos reales.

> *"Un buen modelo no es el que nunca se equivoca, sino el que se equivoca lo menos posible y sabe cuánto se equivoca."*

---

## Formación

**Licenciatura en Matemáticas Aplicadas** — UAEH, Instituto de Ciencias Básicas e Ingeniería

El programa forma matemáticos con bases sólidas en matemáticas puras y aplicadas, capaces de aportar a problemas biomédicos, computacionales, ecológicos, económicos, físicos y financieros, y de trabajar en equipos interdisciplinarios. Ofrece cuatro líneas de aplicación:

| Línea | Ejemplos de aplicación |
|---|---|
| ⭐ **Computación** *(mi línea)* | Algoritmos, sistemas inteligentes y software |
| Economía y finanzas | Riesgo financiero, seguros y estudios de mercado |
| Biología | Modelos demográficos y epidemiológicos |
| Física | Modelación de fenómenos físicos |

**Áreas de estudio:** Álgebra · Cálculo · Álgebra lineal · Ecuaciones diferenciales · Probabilidad · Estadística · Análisis numérico · Programación · Algoritmos

---

## Áreas de interés

### Ciencias computacionales (principal)

| Área | Herramientas |
|---|---|
| **Algoritmos** | Backtracking, búsqueda con retroceso y recursión |
| **Complejidad computacional** | Análisis del costo de un algoritmo en tiempo y en memoria |
| **Métodos numéricos** | Aproximación de soluciones que no se pueden obtener de forma exacta |
| **Programación** | Python y R; paquetes, pruebas unitarias y control de versiones con Git |
| **Aplicaciones web** | Aplicaciones interactivas con Shiny publicadas en GitHub Pages |

### Estadística computacional

| Área | Herramientas |
|---|---|
| **Series de tiempo** | Pruebas de raíz unitaria (ADF, KPSS, Phillips-Perron), modelos ARIMA y SARIMA, diagnóstico con Ljung-Box |
| **Modelos lineales** | Regresión lineal múltiple, selección de variables por AIC, validación cruzada |

---

## Herramientas

<div align="center">

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![RStudio](https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=rstudioide&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## Proyectos

### Resolvedor de Sudoku
Paquete en Python que resuelve sudokus $9 \times 9$ mediante **backtracking**, verifica si un tablero es válido y determina si la solución es única. Incluye pruebas unitarias con `pytest`.

Un tablero es válido si cada fila, columna y subcuadrícula de $3 \times 3$ contiene cada dígito a lo más una vez:

$$
\forall\, d \in \{1,\dots,9\}: \quad \big|\{\,j : a_{ij} = d\,\}\big| \le 1, \qquad \big|\{\,i : a_{ij} = d\,\}\big| \le 1, \qquad \big|\{\,(i,j) \in B_k : a_{ij} = d\,\}\big| \le 1
$$

**Complejidad.** Si el tablero tiene $m$ celdas vacías, en el peor caso el backtracking explora hasta

$$
T(m) = O\!\left(9^{m}\right)
$$

configuraciones. En la práctica es mucho menor, porque cada vez que una asignación rompe una regla se **poda** esa rama y no se exploran sus continuaciones. Para saber si la solución es **única**, el algoritmo no se detiene en la primera solución y sigue buscando una segunda.

[![Repo](https://img.shields.io/badge/Repositorio-Sudoku-181717?style=flat-square&logo=github)](https://github.com/Calambres199/Sudoku)

---

## Algunas ideas que uso seguido

**Modelo SARIMA** $(p,d,q)(P,D,Q)_{s}$, para series con estacionalidad de periodo $s$:

$$
\phi_p(B)\,\Phi_P(B^{s})\,(1-B)^{d}(1-B^{s})^{D}\,Y_t = \theta_q(B)\,\Theta_Q(B^{s})\,\varepsilon_t
$$

**Estimador de mínimos cuadrados** en regresión lineal múltiple:

$$
\hat{\boldsymbol\beta} = (\mathbf{X}^\top \mathbf{X})^{-1}\mathbf{X}^\top \mathbf{y}
$$

**Criterio de información de Akaike**, para comparar modelos penalizando su complejidad:

$$
\mathrm{AIC} = 2k - 2\ln \hat{L}
$$

**Error de predicción** en validación cruzada:

$$
\mathrm{RMSE} = \sqrt{\frac{1}{n}\sum_{i=1}^{n}\left(y_i - \hat{y}_i\right)^2}
$$

---

<div align="center">

👻 *Fuera del aula: entrenador Pokémon de tipo fantasma. Gengar sigue siendo el favorito.*

</div>
