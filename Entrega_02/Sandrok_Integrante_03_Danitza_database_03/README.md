
# Procesos y Decisiones

## **Proceso de recolección de datos**

El análisis se basó en los siguientes datos:

### **Estado de las áreas verdes por comuna**
Los datos utilizados provienen del **Catastro de Parques Urbanos** del Ministerio de Vivienda y Urbanismo (MINVU). Se decidió usar este catastro porque es una fuente oficial que ofrece una evaluación detallada del estado de las áreas verdes en cada comuna de la Región Metropolitana de Santiago. Este catastro incluye información clave sobre la calidad, cantidad y el estado de conservación de los parques y plazas públicas en las comunas.

El catastro clasifica las áreas verdes en función de su estado, identificando aquellas que están en **buen estado** y aquellas que están en **mal estado**, lo cual es crucial para evaluar la disponibilidad efectiva de estos espacios recreativos para la población.

### **Superficie total de áreas verdes por comuna**
Los datos incluyen la **cantidad total de áreas verdes** por comuna, medida en términos de **FID (Feature ID)**, lo que permite identificar cada área verde de manera única. También se proporcionan porcentajes de áreas verdes en buen y mal estado.

Esta decisión permite una evaluación más precisa de la experiencia que los residentes tienen en términos de acceso a espacios recreativos funcionales.

## **Cruce de datos y análisis**
El análisis se centra en comparar el estado de las áreas verdes (bien vs. mal estado) en cada comuna con su cobertura total. Este enfoque permite responder preguntas clave, como:

- **¿Qué comunas tienen la mayor cantidad de áreas verdes en mal estado?**
- **¿Cuáles tienen una proporción mayor de áreas verdes en buen estado?**
- **¿Cúales tienen una proporcioón mayor de áreas verdes en mal estado?**

Al cruzar estos datos, se busca comprender cómo la **distribución y calidad** de las áreas verdes impacta la vida diaria de los residentes.

## **Fuentes**
- **MINVU**: Ministerio de Vivienda y Urbanismo, **Catastro de Parques Urbanos**, con datos sobre el estado de las áreas verdes en la Región Metropolitana de Santiago.
