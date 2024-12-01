# Proceso de selección de datos y visualización
- Para la creación de este primer gráfico usé la base de datos corregida de la segunda entrega, específicamente la de AAVV por Habitante (2). Esto considerando que es la base de datos que ya había trabajado y que tiene relevancia para el tema de nuestro trabajo. Motivación y propósito del gráfico:
El objetivo principal de este gráfico es mostrar la disponibilidad de áreas verdes por habitante (AAVV x hab) en las distintas comunas del Gran Santiago, permitiendo identificar las disparidades entre ellas.

## El gráfico está diseñado para:

- Facilitar una comparación visual clara entre las comunas.
- Resaltar comunas con niveles significativamente altos o bajos de áreas verdes por habitante.
- Proveer contexto adicional con información complementaria como la superficie total de AAVV en cada comuna (en m²), accesible mediante la funcionalidad de tooltip.

## ¿Por qué elegí un gráfico de barras horizontal?


- Este facilita la lectura de categorías con nombres largos (como las comunas), especialmente en un conjunto de datos con muchos elementos.
- Permite ordenar los datos por un valor cuantitativo (AAVV por habitante), haciendo evidente dónde se ubican las comunas con menor o mayor acceso.
- El orden descendente me permitió destacar rápidamente las comunas con mayor cantidad de áreas verdes por habitante yal mismo tiempo permite observar las que están por debajo de los estándares deseados

## Diseño

- Elegí el color verde oscuro porque tiene sentido cuando hablamos de parques y áreas verdes, reforzando así el foco del gráfico .

- Para el tamaño del gráfico experimenté con muchas combinaciones pero me decídi por uno con  grandes dimensiones (700x600 píxeles) para asegurarme que sea legible, dado que el conjunto de datos contiene muchas comunas.
Incorporación de interactividad (tooltips):
- El tooltip  me permite agregardatos adicionales (nombre de la comuna, superficie total de áreas verdes y su valor en m² por habitante) sin tener que saturar el gráfico de elementos visuales.


## Proceso de creación del gráfico
- Lo primero que hice fue instalar las bibliotecas necesarias que en este caso eran altair y pandas
- Luego importe ambas bibliotecas y agregué el conjunto de datos del CSV y denomine cada variable por su nombre dentro del CSV ('comunas','sup AAVV m2' y 'AAVV x hab') y con sus respectivos valores
- Después convertí este diccionario en un DataFrame de pandas: df = pd.DataFrame(data)
- Ya pasando a la creación del gráfico, usé alt.chart para crearlo y señale que quería uno de barras con mark.bar. Le puse las barras de color verde oscuro con (color='darkgreen')
- Para la configuración de los ejes, asigné al de X la variable de 'AAVV por hab' y la llamé 'AAVV por Habitante' y para el eje Y elegí el de las 'comunas:N' y lo llamé 'Comunas'. Aquí agregué el sufijo :N para indicar que este es un dato nominal, es decir, una categoría. También agregué sort= '-x' para que las comunas se ordenen de mayor a menor según la cantidad  de AAVV por habitante
- Para que se viera la variable de 'sup AAVV m2' al pasar el cursor por encima de las barras, agregué el tooltip y asigné cada una de estas variables con su respectivo título y formato
- Delas últimas cosas que configuré fueron las propiedades como el título del gráfico que es 'Superficie AAVV por Habitante en cada comuna del Gran Santiago', el width (ancho) que establecí en 700 y el height (altura) que puse en 600. Eliminé la cuadrícula gracias a configure axis y estableciendo grid=False

# Preguntas que se pueden responder
- ¿Cuáles son las comunas con la mayor cantidad de m² de áreas verdes por habitante?
- ¿Cuáles son las comunas con la menor cantidad de m² de áreas verdes por habitante?
- ¿Cuál es el promedio de m² de áreas verde por habitante en las diferentes comunas?
- ¿Cuáles son las comunas con más m² de áreas verdes? (esa se responde al revisar con el tooltip)
