
# Proyecto: **Gran Santiago: Verde para algunos**

## Descripción General  
Este proyecto aborda la desigualdad en el acceso a áreas verdes en Santiago, especialmente desde la perspectiva de la población infantil. A través del análisis de distintas bases de datos y la creación de visualizaciones interactivas, buscamos revelar las disparidades en la distribución de espacios verdes, destacando las comunas más afectadas y promoviendo soluciones urbanas inclusivas.

---

## **1. Proceso General**

### **Recolección de Datos**  
Para desarrollar este proyecto, utilizamos tres fuentes principales que aportaron datos complementarios:

- **INE (Instituto Nacional de Estadísticas):**  
  Proyecciones del Censo 2017 para obtener la distribución de la población infantil (0-15 años) por comuna.  
- **Ministerio del Medioambiente - Sexto Informe REMA (2021):**  
  Información sobre la superficie de áreas verdes por comuna y el déficit relativo.  
- **MINVU - Catastro de Parques Urbanos:**  
  Registro de parques urbanos y su estado actual (buen/mal estado), integrando una perspectiva sobre la calidad de estos espacios.  

Además, los datos se integraron con archivos geoespaciales (GeoJSON) para representar la distribución territorial en mapas.

---

### **Análisis de Datos y Métricas**  
Los datos se limpiaron y analizaron en distintas etapas:
- **Limpieza y consistencia:** Eliminación de valores duplicados, corrección de errores y ajuste de formatos.  
- **Generación de métricas clave:**  
  - *Déficit de áreas verdes per cápita infantil.*  
  - *Relación entre áreas verdes totales y población infantil.*  
  - *Proporción de parques en mal estado respecto al total por comuna.*

Estos análisis permitieron identificar comunas con mayores desigualdades y establecer prioridades para intervenciones urbanas.

---

## **2. Visualizaciones Principales**

### **Gráfico 1: Distribución de Áreas Verdes y Población Infantil (Gráfico de Dispersión)**  
- **Descripción:**  
  Muestra la relación entre la cantidad de niños (0-15 años) y las áreas verdes disponibles en cada comuna. Cada punto representa una comuna, diferenciándose por color y tamaño según su déficit de áreas verdes.  
- **Propósito:**  
  Identificar comunas con alta población infantil pero baja superficie de áreas verdes, destacando zonas críticas.  

---

### **Gráfico 2: Áreas Verdes por Habitante (Gráfico de Barras)**  
- **Descripción:**  
  Barras ordenadas que ilustran la cantidad de m² de áreas verdes por habitante en cada comuna.  
- **Detalles Técnicos:**  
  - Tooltip interactivo para mostrar la superficie total de áreas verdes.  
  - Clasificación nominal de comunas según su déficit.  
- **Propósito:**  
  Destacar las comunas mejor y peor posicionadas en términos de acceso individual a áreas verdes.  


---

### **Gráfico 3: Estado de los Parques Urbanos (Mapa Interactivo)**  
- **Descripción:**  
  Mapa que presenta el número total de parques urbanos por comuna y su estado (buen/mal estado).  
- **Detalles Técnicos:**  
  - Uso de GeoJSON para representación geoespacial.  
  - Interactividad para explorar datos específicos de cada comuna.  
- **Propósito:**  
  Mostrar no solo la cantidad, sino también la calidad de los espacios verdes en Santiago.  

---

## **3. Reflexión General**  

Este proyecto revela profundas desigualdades en el acceso y calidad de las áreas verdes para la población en general pero también infantil en las comunas del Gran Santiago. Las visualizaciones complementarias permiten abordar el problema desde tres ángulos: cantidad (gráficos 1 y 2), calidad (gráfico 3) y distribución geográfica (todos).  

La información presentada no solo destaca la necesidad urgente de planificación urbana más equitativa, sino que también ofrece un marco para priorizar intervenciones en las comunas más vulnerables. Al empoderar a los ciudadanos y responsables políticos con estos datos, esperamos impulsar cambios significativos hacia una ciudad más verde e inclusiva.


### **Equipo de Trabajo:**  
- **[Aline Bergen]:** Gráfico de dispersión y análisis del déficit de áreas verdes per cápita infantil.  
- **[Cristóbal Ramírez]:** Gráfico de barras sobre áreas verdes por habitante y visualización del acceso desigual.  
- **[Danitza Sandrock]:** Mapa interactivo y análisis del estado de parques urbanos.
