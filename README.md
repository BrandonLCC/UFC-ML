<p align="center">
    <!--![imagen-readme-presentacion](../img/img-readme.jpg)-->
    <img src="../img/img-readme.jpg" alt="Banner del proyecto" width="600">

</p>

# Proyecto: UFC con machine learning

## Objetivo del proyecto

El objetivo principal de esta investigación es realizar un modelado probabilístico utilizando técnicas de Machine Learning que permita predecir el resultado de los combates **(ganados o perdidos)** y la **duración de un combate** en función de ciertas características de los luchadores o de las acciones realizadas durante los combates.
Además, se propone implementar tres tipos de modelado: regresión, clasificación y creación de clústeres.

---

## Dataset utilizado

Para este proyecto se utilizará únicamente el dataset `UFC.csv`, el cual corresponde a la combinación de los archivos CSV obtenidos desde Kaggle (`event_details.csv`, `fight_details.csv` y `fighter_details.csv`). 

Este dataset contiene toda la información relacionada con las peleas de la UFC, incluyendo los detalles de los eventos y los combates realizados, así como estadísticas de rendimiento de los peleadores, tales como el porcentaje de golpes acertados, derribos, caídas, control sobre el oponente y otras características esenciales del combate.

- **Fuente:** Kaggle — [ufc-datasets-1994-2025](https://www.kaggle.com/datasets/neelagiriaditya/ufc-datasets-1994-2025/data)
- **Licencia:** CC0 1.0 Universal
- **Origen de los datos crudos:** [ufcstats](ufcstats.com)    
- **Filas:** ~8.000 registros  
- **Columnas:** 124 características  
- **Formato:** CSV (`UFC.csv`)


## Instrucciones de ejecución

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/BrandonLCC/UFC-ML.git
   ```

2. Acceder al directorio:
   ```bash
    cd UFC-ML
   ```

## Dependencias 

### Librerías

- pandas: `2.2.2`
- numpy: `2.0.2`
- matplotlib: `3.10.0`
- seaborn: `0.13.2`
- scikit-learn: `1.6.1`

### Lenguaje y versión

Python 3.12 (compatible con todas las librerías usadas)