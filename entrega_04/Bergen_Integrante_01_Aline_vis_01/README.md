# Documento (Proceso, Decisiones, Preguntas)


### **Proceso:**


1. **Recolección de Datos:**

    Fuentes utilizadas: Se obtuvo información de dos fuentes principales:
    * _INE (Instituto Nacional de Estadísticas)_: 
    
    Proyecciones basadas en el Censo 2017, proporcionando datos sobre la población infantil (0-15 años) por comuna. Estos datos fueron cruciales para comprender la distribución de la población infantil en Santiago y determinar cómo se distribuyen en las diversas comunas.

    * _Ministerio del Medioambiente - SEXTO INFORME REMA (2021)_:
    
     Este informe ofrece detalles sobre la cantidad de áreas verdes disponibles en Santiago y su distribución entre las distintas comunas. Específicamente, se obtuvo información sobre la superficie de áreas verdes por habitante, lo que permitió analizar el déficit de áreas verdes en relación con la población infantil.

    * _Complementación de Datos_:
    
     Se utilizó información adicional de la Biblioteca Nacional para corroborar la exactitud de los datos a nivel comunal y asegurar que la información sobre las áreas verdes estuviera completa y actualizada.

2. **Análisis Inicial:**

Se realizaron análisis preliminares para detectar patrones y posibles correlaciones entre las variables. Se centró en observar si existían zonas con alta población infantil pero pocas áreas verdes, y viceversa. Esto se hizo para identificar las comunas con mayores desigualdades en términos de acceso a espacios verdes para niños.
También se comenzó a observar la distribución geográfica de las áreas verdes en relación con la población infantil para comprender mejor si las comunas con mayor crecimiento poblacional estaban cubiertas adecuadamente en términos de infraestructura verde.

3. **Limpieza de Datos:**

Se procedió a limpiar los datos para garantizar su calidad:
Se eliminaron duplicados que pudieran afectar los resultados del análisis.
Se trató los valores faltantes mediante imputación (por ejemplo, usando medias o medianas en algunos casos) o eliminando las filas incompletas que no aportaban información relevante.
Se verificaron errores en la codificación de las variables, como por ejemplo en el cálculo de las áreas verdes por habitante, para asegurar que los valores fueran consistentes y correctos.

4. **Generación de Nuevas Métricas:**

Se creó una nueva variable que calcula el déficit de áreas verdes en cada comuna, relacionando la cantidad de niños con el número de metros cuadrados de áreas verdes disponibles por habitante. Esta métrica permitió identificar comunas con déficit significativo y ayudar a priorizar áreas que requieren atención urgente.



5. **Decisiones:**

_Selección de Variables:_

Elegimos dos variables clave para el análisis: cantidad de niños por comuna (0-15 años) y áreas verdes por habitante. Estas variables son fundamentales porque nos permiten observar:
La distribución de los niños en la ciudad y cómo se correlacionan con la disponibilidad de espacios verdes.
La relación entre áreas verdes y la población infantil, lo cual es crucial para evaluar si las zonas con mayor densidad infantil cuentan con suficientes áreas recreativas y de esparcimiento.

El  gráfico de dispersión ilustra de manera clara las diferencias entre las comunas con mayores y menores déficits de áreas verdes. Los puntos rojos del gráfico destacan las comunas con mayores déficits, mientras que los puntos verdes representan aquellas con mejores proporciones de áreas verdes en relación con su población infantil. Las diferencias son evidentes, subrayando la necesidad urgente de una distribución más equitativa de espacios recreativos en toda la ciudad.

6. **Preguntas:**


_¿Cuáles son las comunas con mayor déficit de áreas verdes per cápita infantil?_ 

Esta pregunta es clave para identificar las comunas más necesitadas de intervención urbana. Al analizar el déficit, podemos destacar las zonas donde se debería priorizar la inversión en infraestructura verde, especialmente aquellas comunas con una alta población infantil.

_¿Existe una correlación entre la superficie de áreas verdes y la población infantil en las comunas?_

Queremos saber si existe una relación directa o inversa entre la cantidad de áreas verdes y la población infantil. Este análisis podría revelar patrones interesantes, como si las comunas con más niños tienen proporcionalmente más áreas verdes, o si hay comunas con alta población infantil y pocas áreas verdes.
¿Qué comunas están mejor equilibradas en términos de áreas verdes y población infantil?

Esta pregunta nos permite identificar a las comunas que han logrado un buen equilibrio entre la cantidad de áreas verdes disponibles y la población infantil, sirviendo como ejemplos positivos de planificación urbana que pueden inspirar a otras comunas a mejorar sus espacios verdes.
¿Cómo podría influir esta información en la planificación de nuevas áreas verdes?

La visualización de estos datos puede ayudar a los responsables de la planificación urbana a tomar decisiones informadas sobre dónde se deben construir nuevas áreas verdes o mejorar las existentes. Esto es crucial para fomentar el bienestar de la población infantil y promover una ciudad más equitativa y saludable.