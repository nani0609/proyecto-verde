# **Procesos y decisiones**
## **1- Recolección de datos:** 
- Para la construcción de nuestra base de datos usamos los datos en bruto que adquirimos del reporte de Estado del Ambiente del Sistema Nacional de Información Ambiental, específicamente del capitulo de Infraestructura Verde Urbana. De aquí extrajimos las columnas de "Superficie de Área Verde (m2)" y la de "BPU_29 Superficie de Área verde por habitantes (m2/hab)"
- Al mismo tiempo, descartamos toda comuna que no estuviera dentro del Gran Santiago
- Simplificamos los nombres de los encabezados de las columnas reemplando "Superficie de Área Verde (m2)" por "supp AAVV m2" y "BPU_29 Superficie de Área verde por habitantes (m2/hab)" lo pusimos como "% AAVV x hab"

## **2- ¿Por qué estos datos?:**
- Los datos extraídos del Sexto Reporte de Estado del Ambiente nos entregan importante información sobre las superficies en metros cuadrados sobre el total de áreas verdes de cada comuna y el espacio de estas mismas al que cada habitante de una comuna tendría acceso. Que estén todas las comunas juntas permite una rápida comparación sobre el estado y la desigualdad de acceso entre cada una de ellas. 
- Estos datos nos entregan una visión cuantitativa de las grandes brechas que existe a lo largo de todo Santiago

## **3- ¿Qué preguntas responde?:** 
La base de datos que despejamos y limpiamos nos permitiría responder algunas preguntas como estas: 

-¿Cuál es la comuna de Santiago con peor porcentaje de área verdes por habitante? 

-¿Cuál es la mejor comuna en cuanto al porcentaje de área por habitante se refiere? 

-¿Cuántas comunas se encuentran tienen un porcentaje por sobre el 10%?
