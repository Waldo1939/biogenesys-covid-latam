# Biogenesys – Expansión de vacunación COVID-19 en LATAM (Power BI + Python)

Proyecto de análisis y visualización para identificar países y regiones prioritarias en América Latina para la expansión de laboratorios y centros de vacunación de **Biogenesys**.  
Se combinan **Power BI** (dashboard interactivo) y **Python** (EDA y gráficos complementarios).


---

## 📂 Estructura del repositorio  

biogenesys-covid-latam/  
├─ powerbi/  
│ └─ Biogenesys_Dashboard.pbix  
├─ notebooks/  
│ └─ EDA_Biogenesys.ipynb  
├─ data/  
│ └─ DatosFinalesFiltrados/ # datasets listos para el PBIX   
├─ assets/  
│ └─ imgs/ # capturas del dashboard  
└─ README.md  


---

## 🧰 Requisitos

- **Power BI Desktop** (versión reciente)
- **Python 3.10+** con paquetes:
  - `pandas`, `numpy`, `matplotlib`, `seaborn` (si usaste gráficos Python en PBI)


---

## 🚀 Cómo usar

### 1) Clonar el repositorio
```bash
git clone https://github.com/tu_usuario/biogenesys-covid-latam.git
cd biogenesys-covid-latam
```
### 2) Abrir el dashboard

Abrí powerbi/Biogenesys_Dashboard.pbix.

### 3) (Opcional) Habilitar gráficos de Python en Power BI

File → Options → Python scripting: seleccioná tu instalación de Python.

Verificá que estén instalados pandas y matplotlib/seaborn.


---
🧪 Contenido del dashboard

Portada: contexto del proyecto y misión de Biogenesys.

Análisis por país:

Muertes por 100k (serie temporal actualizada).

Nuevos casos por 100k.

Relación vacunación vs muertes (scatter).

Dosis acumuladas administradas (línea) — Brasil lidera en términos absolutos; considerar población para cobertura.

Comparación entre países:

Mapa temático, ranking de vacunación y evolución comparada por dosis.

Factores estructurales y sanitarios:

Heatmap comparativo (muertes/casos/vacunación),

Rankings: % ≥60 años, physicians per 1k, prevalencia de diabetes, PIB per cápita.

Conclusiones: síntesis visual + recomendaciones por país (Chile, Argentina, Brasil) incorporando dimensión económica.


---

👤 Autor

Walter A. Frías Mendaro – Data Analytics (Soy Henry)  
Contacto: walterfrias.wf@gmail.com | LinkedIn: https://www.linkedin.com/in/walterfriasmendaro/

