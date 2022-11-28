# Proyecto_final
 Integrantes:
 Aura Orozpe
 Ariadna Lozano
##Las mejores  ciudades para vivir
La información con  cuál se realizará el siguiente analisis descriptivo  es parte de un estudio que hizo Arcadis en colaboración de el Centre for economics and Business Research, en donde buscaban hacer un ranking para encontrar cuales son las mejores ciudades para vivir y que cuiden los siguientes 3 aspectos:

- Calidad de vidad de las personas
- Relación con el medio ambiente 
- Salud economica de la ciudad

Tomando en cuenta lo anterior Arcadis realizo un ranking del promedio sobre 100 ciudades de diferentes partes del mundo, con ayuda de 32 indicadores que no son representados en nuestra base de datos.
 
 Información adicional proporcionada:
  
 - Pais en donde se encuentra
 - Continente

(1) ¿Cuál fue el motivo de elegir tu base de datos?
Consideramos que dadas las problemáticas actuales (ambientales, económicas y sociales) en todo el mundo, se está viviendo una incertidumbre respecto a la situación de los países, es por eso que escogimos esta base de datos y buscamos entender y dar una perspectiva sobre cuáles son los mejores y peores países para vivir en relación a dichas circunstancias. 

(2) ¿Cuáles fueron tus fuentes para desarrollar el proyecto?
La base datos la sacamos de kaggle, de un estudio realizado por  Arcadis en colaboración de el Centre for economics and Business Research
También utilizamos información general de cada país para consultar el número de habitantes 

(3) ¿Cuáles fueron tus metas para tu entendimiento del proyecto?
Al principio, buscábamos mostrar cuáles eran los mejores países, tanto en total de calificación, como en las categorías específicas. Mientras realizábamos dicho análisis nos dimos cuenta que podíamos relacionar dicho ranking con factores como el número de habitantes y realizar un análisis exploratorio, un cálculo de la varianza, covarianza y predicciones. 
Nos gustaría en un futuro lograr predecir (incluyendo más variables de información), las tendencias políticas, sociales y ambientales de cada país y cómo se moverían en el ranking tomando en cuenta el desarrollo sustentable de acuerdo a la agenda G30, la calidad de vida de acuerdo a los sucesos ocurridos y la economía de acuerdo a los registros de cada país creando un ranking dinámico para consultarse. 

(4) ¿Qué elementos representativos tomaste en cuenta, esto es cuáles fueron tus variables explicativas y cuál fue tu variable responsiva?
Nuestra variables explicativas para la resolución de nuestro caso fueron el promedio general de las variables dentro del ranking (Overall), calidad ambiental con la que cuenta el país (Planet), calidad economica del pais (Profit) y la calidad de vida (People). Mientras que nuestra variable responsiva fue el numero de habitantes por país

##Conclusiones
Ariadna: 
Al realizar este proyecto nos dimos cuenta de que una base de datos simple que no nos brinda una gran cantidad de información puede convertirse en una base de datos que nos arroje un modelo predictivo, nos enseñe relación entre las variables y lo más impoprtante, nos permita conocer y analizar información útil para nosotras y para otras personas interesadas en temas como sostenibilidad, economía de un país o calidad de vida. 
Convertimos un ranking en un modelo que puede tener usos de muchos tipos, como una consulta personal, hasta un senso poblacional o un análisis económico de un país, estadísticas respecto a efectividad de los programas ecológicos entre muchos otros. 

Aura:
Con el desarrollo de este proyecto pude ver la aplicación real de la probabilidad aplicada a datos, de esta ultima etapa pudimos sacar primero un promedio del ranking general de los pais en los 4 indicadores que contaba, donde pudimos ver que el pais con mejor puntaje dentro de la categoria de relación con el planeta, energias renovables es Suecia. Con la palicación de la regresión lineal podemos obser que si tomamos en cuenta todos los factores el modelo cuenta con una efectividad del 62%. Contando con una pendiente positiva, ademas podemos observar que a mayor población es mas dificil mantener un buen lugar dentro del ranking, por lo que es bastante probable encontrarse dentro de los ultimos lugares como es el caso de China que cuenta con la peor puntación en el aspecto calidad de vida de sus habitantes.
