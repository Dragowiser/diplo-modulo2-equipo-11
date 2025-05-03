##  Proyecto final de moduli  
Este proyecto forma parte del módulo de programacion del diplomado para ciencia de datos, impartido en la **Facultad de Ciencias** de la **UNAM** este se encuentra en el [repositorio  de GitHub](https://github.com/Fernando-Alvarado/colaboracion-git-equipo-11).


## Introducción / Objetivo del Proyecto  
El propósito de este proyecto es emplear técnicas de programación usando R para analizar datos reales, obtener conclusiones, evaluar si las acciones se correlacionan con los datos y generar interpretaciones significativas, así como proponer posibles planes de acción.



## Colaboradores

- **Fernando Alvarado Palacios**: [GitHub](https://github.com/Fernando-Alvarado)  [linkedin](https://www.linkedin.com/in/fernando-alvarado-37415b216/) 
- **Bryant Canseco Hernández**: [Nombre de la organización]  
- **Diego Gómez Santiago**: [Nombre de la organización]  


## 📈 Métodos Utilizados  
- Estadística inferencial  
- Estadística descriptiva
- Modelo no parametricos y de regresion. 
- Visualización de datos  y datos faltantes


##  🔧 Tecnologías  
- R  
- Rmarkdown

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![RMarkdown](https://img.shields.io/badge/RMarkdown-2C3E50?style=flat&logo=r&logoColor=white)


## 📊 Descripción del Proyecto  
Este proyecto incluye el análisis de tres conjuntos de datos independientes:

1. **Análisis exploratorio de Vuelos y Aeropuertos**

### Análisis exploratorio de Vuelos y Aeropuertos

Para realizar este análisis se nos proporcionó una base de datos sobre los vuelos registrados en los aeropuertos de la ciudad de Nueva York durante el año 2013. Esta base incluye las siguientes tablas:

- La tabla `airlines` contiene información sobre las aerolíneas.
- La tabla `aeropuertos` contiene información sobre diferentes aeropuertos.
- La tabla `planes` describe las características de los aviones.
- La tabla `clima` contiene datos meteorológicos por hora en los aeropuertos.
- La tabla `vuelos` contiene datos sobre más de 300,000 vuelos desde NYC en el año 2013.

El objetivo de este análisis fue responder diversas preguntas para entender la dinámica de los aeropuertos y el comportamiento del tráfico aéreo. Algunas de las preguntas que pudimos abordar fueron:

- ¿Qué aerolíneas sufrían los mayores retrasos?
- ¿El clima afectaba la llegada o salida de los aviones?
- ¿Qué aerolíneas salían o llegaban con mayor frecuencia a los aeropuertos?
- ¿Cuáles eran los destinos principales?
- ¿Cómo variaban los retrasos entre aerolíneas?

Esta información puede ser útil para un administrador aeroportuario o para alguien interesado en invertir en una compañía aérea.



2. **Titulo**  
   

  **imagenes graficas**

3. **Titulo**  
   

  **imagenes graficas**


También se aplicaron procesos de limpieza, visualización y modelado básico para extraer conclusiones útiles de cada conjunto de datos.

## 💡 Necesidades del Proyecto  
- Desarrollo frontend  
- Estadísticas descriptivas  
- Limpieza y procesamiento de datos  
- Modelado estadístico  
- Redacción y documentación  

## Cómo Empezar  

Descarga Proyecto

```bash
git clone https://github.com/Fernando-Alvarado/colaboracion-git-equipo-11.git
```

## ▶️ Ejecución del Proyecto

1. Abrir `proyecto_final.Rmd` en RStudio.
2. Ejecutar en la terminal de R ` rmarkdown::render("proyecto_final.Rmd")`
3. Se generará automáticamente `proyecto_final.html` como salida.


## 📁 Organizacion del proyecto 

```text
proyecto/
├──  📂 Data/                              # Datos utilizados en el análisis
├──  📂   proyecto_final_files/     # Imágenes generadas por el Rmd
│        └── figure-html/
├──  📂   Image                          #Imagenes para el readme
├── .gitignore                              # Archivos ignorados por Git
├──  🅡 proyecto_final.Rmd               # Código fuente en R Markdown
└── README.md                          # Documentación del proyecto
```

## ⚙️ Requisitos

- Tener instalado R (versión ≥ 4.3.2)
- Tener RStudio (opcional pero recomendado)
- Instalar los siguientes paquetes de R:
  - `tidyverse`
  - `readr`
  - `dplyr`
  - `ggplot2`
  - `naniar`
