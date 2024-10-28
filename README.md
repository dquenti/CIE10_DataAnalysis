# Análisis Comparativo de Códigos CIE-10

Este proyecto realiza un análisis exhaustivo de los códigos CIE-10 utilizados en distintos sistemas de salud (Rayen, Yani y la base oficial de MINSAL). Utilizando el archivo `CIE10analisis.ipynb`, el objetivo es evaluar la consistencia, calidad y diferencias en la implementación de los códigos CIE-10 entre estos sistemas para mejorar la comunicación entre estos sistemas con miras a la interoperabilidad y precisión clínica.

## Contenido del Proyecto

### Objetivos
- **Comparar los códigos CIE-10** de los sistemas Rayen, Yani y MINSAL.
- **Identificar códigos comunes y únicos** en cada sistema.
- **Evaluar la calidad de los datos** en términos de valores nulos y descripciones inconsistentes.
- **Visualizar diferencias** mediante gráficos de distribución y diagramas de Venn.

### Análisis Principal
1. **Carga de Datos y Limpieza**: Se importan las bases de datos y se eliminan valores nulos para asegurar la calidad del análisis.
2. **Exploración de Códigos Únicos y Duplicados**: Se analizan los códigos únicos y duplicados en cada sistema.
3. **Comparación entre Bases**: Se identifican los códigos comunes y se visualizan las superposiciones entre sistemas mediante diagramas de Venn y gráficos.
4. **Conclusiones y Recomendaciones**: El análisis final sugiere mejoras para la estandarización y consistencia de los códigos CIE-10.

## Requisitos

Este proyecto está desarrollado en Python, y requiere las siguientes librerías:

- **pandas**: Manipulación de datos.
- **matplotlib**: Visualización básica.
- **seaborn**: Gráficos avanzados.
- **matplotlib_venn**: Creación de diagramas de Venn.
- **plotly** (opcional): Visualización interactiva.

Para instalar estas dependencias, puedes ejecutar:

```bash
pip install pandas matplotlib seaborn matplotlib-venn plotly
```

## Instrucciones de Ejecución

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```
2. Abre el archivo `CIE10analisis.ipynb` en un entorno de Jupyter Notebook o JupyterLab.
3. Ejecuta cada celda del notebook secuencialmente para reproducir el análisis.

## Visualizaciones

El análisis incluye:
- **Diagramas de Venn** para visualizar los códigos en común y únicos en cada sistema.
- **Histogramas de longitud de descripción** para cada sistema.
- **Heatmaps** de valores nulos para evaluar la calidad de los datos.

## Contribuciones

Las contribuciones a este proyecto son bienvenidas. Si deseas mejorar el análisis, reportar un problema o proponer nuevas funcionalidades, abre una solicitud de cambios (pull request) o una incidencia (issue) en este repositorio.



---

Este README está diseñado para que el lector entienda rápidamente el propósito del proyecto, los requisitos necesarios y cómo ejecutar el análisis. También facilita la colaboración futura si decides abrir el proyecto a contribuciones.
