##  Proyecto final de moduli  
Este proyecto forma parte del módulo de programacion del diplomado para ciencia de datos, impartido en la **Facultad de Ciencias** de la **UNAM** este se encuentra en el [repositorio  de GitHub](https://github.com/Fernando-Alvarado/colaboracion-git-equipo-11).


## Introducción / Objetivo del Proyecto  
El propósito de este proyecto es ________.  
(Describe los objetivos principales del proyecto y su posible impacto cívico. Limítalo a un párrafo breve de 3 a 6 oraciones.)



## Colaboradores

- **Fernando Alvarado Palacios**: [GitHub](https://github.com/Fernando-Alvarado)  [linkedin](https://www.linkedin.com/in/fernando-alvarado-37415b216/) 
- **Bryant Canseco Hernández**: [Nombre de la organización]  
- **Diego Gómez Santiago**: [Nombre de la organización]  


## 📈 Métodos Utilizados  
- Estadística inferencial  
- Estadística descriptiva
- Modelo no parametricos y de regresion. 
- Visualización de datos  

##  🔧 Tecnologías  
- R  
- Rmarkdown

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![RMarkdown](https://img.shields.io/badge/RMarkdown-2C3E50?style=flat&logo=r&logoColor=white)


## 📊 Descripción del Proyecto  
Este proyecto incluye el análisis de tres conjuntos de datos independientes:

1. **Análisis de la Prueba de Bechdel**  
   - ¿Qué tan frecuente es que las películas pasen la prueba?  
   - Relación con año, presupuesto, género.
   
   **imagenes graficas**

2. **Seguridad en Aerolíneas**  
   - Análisis por aerolínea y década de incidentes.  
   - Visualización de cambios en la seguridad aérea a lo largo del tiempo.

  **imagenes graficas**

3. **Calidad del Café**  
   - Análisis sensorial (acidez, aroma, cuerpo, etc.) vs. calificación global.  
   - Exploración por país y tipo de procesamiento.

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
