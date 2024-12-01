# Ficha Técnica de la Base de Datos: Parques Urbanos por Comuna

### **1. Características de los Datos**
- **Tipo de datos:** Datos cuantitativos y categóricos.
- **Fuente:** (Indicar la fuente específica, ej., municipalidades, encuestas, instituciones de gobierno).
- **Período cubierto:** (Especificar el rango de tiempo si corresponde, ej., 2020-2024).
- **Unidad de análisis:** Comunas y parques urbanos.

### **2. Dimensiones Principales**
1. **Comunas:**
   - Descripción: Cada registro incluye una comuna como categoría principal.
   - Formato: Variable categórica (ej., "Comuna de Santiago").
2. **Cantidad de parques urbanos:**
   - Descripción: Número total de parques urbanos registrados por comuna.
   - Formato: Variable cuantitativa.

### **3. Variables Incorporadas**
| Variable                       | Descripción                                                                 |
|--------------------------------|-----------------------------------------------------------------------------|
| `comuna`                       | Nombre de la comuna.                                                       |
| `parques_urbanos`              | Cantidad total de parques urbanos por comuna.                              |
| `parques_en_mal_estado`        | Cantidad de parques urbanos en mal estado dentro de cada comuna.           |
| `porcentaje_mal_estado`        | Porcentaje de parques urbanos en mal estado respecto al total en la comuna. |

### **4. Observaciones sobre la Base de Datos**
- **Cobertura geográfica:** La base de datos cubre las comunas especificadas, pero puede haber comunas sin datos disponibles.
- **Estado de los datos:** La categoría de "mal estado" puede variar según los criterios utilizados, como infraestructura deteriorada, falta de mantenimiento, o riesgos de seguridad.
- **Complejidad:** Es posible realizar análisis comparativos entre comunas y calcular indicadores como porcentajes de deterioro o ratios de parques por habitantes (si se incluyen datos poblacionales adicionales).
- **Limitaciones:** Si los datos no están actualizados, puede haber discrepancias con la realidad actual.

### **Posibles Usos de los Datos**
- Diagnósticos para asignación de presupuesto y priorización de mantenimiento.
- Planificación de intervenciones urbanas.
- Estudios sobre accesibilidad y calidad de áreas verdes urbanas.
