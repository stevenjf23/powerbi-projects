# Proyecto de Práctica – DAX y Visualización en Power BI

## Descripción
Este proyecto fue desarrollado únicamente con fines de práctica y aprendizaje del lenguaje DAX y la creación de visualizaciones en Power BI.

El objetivo principal fue trabajar cálculos básicos en DAX para analizar información económica y poblacional de distintos países mediante gráficos interactivos.

---

## Vista del Proyecto

![Grafico de Dispersión](./imagen1.png)
![Formula DAX](./imagen2.png)
![Segunda Fomrula DAX](./imagen3.png)

---

## Tecnologías Utilizadas
- Microsoft Power BI
- DAX (Data Analysis Expressions)

---

## Funciones DAX Utilizadas

### PBI en MUSD
```DAX
PBI en MUSD =
SUMX(
    Paises,
    Paises[PBI (millones de moneda nacional)] /
    RELATED(Cambio[Tipo de cambio (USD/moneda nacional)])
)
