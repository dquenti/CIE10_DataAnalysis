# 🧩 Análisis Comparativo de Códigos CIE-10 en Sistemas de Salud 🧬

Este proyecto realiza un análisis exhaustivo de los códigos **CIE-10** implementados en tres sistemas de salud: **Rayen**, **Yani**, y la base oficial **MINSAL**. El análisis, realizado en `CIE10analisis.ipynb`, evalúa la **consistencia, calidad y diferencias** en la implementación de estos códigos, con el objetivo de mejorar la interoperabilidad y precisión en la comunicación entre sistemas de salud.

---

## 📊 Contenido del Proyecto

### 🎯 Objetivos del Análisis
- 🔍 **Comparar los códigos CIE-10** en Rayen, Yani y MINSAL para detectar coincidencias y diferencias.
- 🗃️ **Identificar códigos comunes y únicos** en cada sistema.
- ✅ **Evaluar la calidad de los datos** (valores nulos, duplicados, descripciones inconsistentes).
- 📈 **Visualizar diferencias y patrones** mediante histogramas, diagramas de Venn, y heatmaps.

---

## 🗂️ Descripción de las Bases de Datos

- **Rayen**: Última actualización en **noviembre de 2023**. Esta base contiene 14,383 códigos, representando la codificación en el sistema Rayen.
- **Yani**: Última actualización en **octubre de 2024**. Con un total de 12,561 códigos, esta base refleja los diagnósticos del sistema Yani.
- **MINSAL**: Base oficial del Ministerio de Salud, actualizada a **mayo de 2024**. Contiene 12,545 códigos, siendo la referencia nacional oficial para diagnósticos CIE-10.

Cada base se analiza en términos de calidad y consistencia, identificando patrones únicos y duplicados, y verificando que los sistemas se alineen en su implementación de los códigos.

---

## 🔍 Análisis Principal

1. **Carga y Limpieza de Datos**: Importación de bases de datos y eliminación de valores nulos.
2. **Exploración de Códigos Únicos y Duplicados**: Revisión de códigos exclusivos y duplicados en cada sistema.
3. **Comparación de Bases**: Identificación de códigos comunes entre Rayen, Yani, y MINSAL, usando un diagrama de Venn para visualizar superposiciones.
4. **Conclusiones y Recomendaciones**: Síntesis final con sugerencias para mejorar la estandarización y consistencia de los códigos CIE-10.

---

## 📋 Requisitos

Este proyecto requiere **Python** y las siguientes librerías:

- **pandas**: Manipulación de datos.
- **matplotlib**: Visualización básica.
- **seaborn**: Gráficos avanzados.
- **matplotlib_venn**: Diagramas de Venn.
- **plotly** (opcional): Visualización interactiva.

Instala todas las dependencias ejecutando:

```bash
pip install pandas matplotlib seaborn matplotlib-venn plotly
```

---

## 🚀 Instrucciones de Ejecución

1. **Clonar el repositorio** en tu máquina local:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```
2. **Abrir el archivo `CIE10analisis.ipynb`** en Jupyter Notebook o JupyterLab.
3. **Ejecutar cada celda** secuencialmente para reproducir el análisis.

---

## 📈 Visualizaciones

El análisis incluye una serie de visualizaciones para explorar los datos de forma interactiva y visual:

- 🔄 **Diagramas de Venn** para ver códigos en común y únicos en cada sistema.
- 📊 **Histogramas** de la longitud de descripciones para cada sistema.
- 🌡️ **Heatmaps de valores nulos** para evaluar la calidad y completitud de los datos.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar el análisis, encontrar errores o proponer nuevas funcionalidades, abre una **solicitud de cambios (pull request)** o una **incidencia (issue)** en este repositorio.

---

## 📜 Licencia

Este proyecto está disponible bajo la **licencia MIT**. Consulta el archivo `LICENSE` para obtener más detalles.

---

Este README ofrece una visión detallada y organizada del proyecto, resaltando el propósito y contenido de cada base de datos, y guiando al lector a través de los pasos de instalación y ejecución de manera clara y atractiva. ¡Perfecto para un repositorio de GitHub!

