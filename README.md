# Análisis de Datos de Twitch en Español e Ingles

Este proyecto analiza los datos de los principales canales de Twitch que transmiten en español para obtener insights sobre el rendimiento y las características de estos streamers. El análisis incluye información sobre la audiencia, el contenido y otros aspectos relevantes de los canales.

## Dataset

El dataset utilizado proviene de [Kaggle](https://www.kaggle.com/datasets/aayushmishra1512/twitchdata) y contiene datos de los 1000 principales streamers de Twitch. Las variables incluyen, entre otras:

- Nombre del canal
- Idioma de transmisión
- Número de seguidores
- Número máximo de vistas simultáneas
- Estado de "Contenido Maduro" (Mature)
- Asociación con el programa "Partner" de Twitch

## Objetivos del Análisis

Este análisis intenta responder a las siguientes preguntas:

1. ¿Cuál es la distribución de idiomas entre los canales?
2. ¿Cuál es la proporción de canales en español que transmiten contenido "maduro"?
3. ¿Cuál es la distribución de canales asociados al programa "Partner"?
4. ¿Existen correlaciones significativas entre las variables numéricas?
5. ¿Cuáles son los canales en español con el máximo pico de vistas?
6. ¿Cuáles son los canales en español con más seguidores?

## Herramientas y Librerías Utilizadas

El análisis se llevó a cabo en Python utilizando las siguientes librerías:

- `pandas` y `numpy` para la manipulación y análisis de datos
- `matplotlib` y `seaborn` para la visualización de datos

## Estructura del Análisis

1. **Carga y Exploración de Datos**: Importación del dataset y limpieza de datos.
2. **Análisis Exploratorio**: Visualización de distribuciones de lenguaje, contenido "maduro", y programas "Partner".
3. **Correlación de Variables**: Análisis de correlaciones entre variables numéricas.
4. **Ranking de Canales**: Identificación de los canales en español con mayor pico de vistas y más seguidores.

## Resultados Principales

1. La distribución de idiomas revela que el español es uno de los idiomas predominantes en la plataforma para los streamers analizados.
2. Un porcentaje significativo de canales en español tiene contenido para adultos, lo cual indica una tendencia hacia contenido más maduro.
3. La mayoría de los streamers de habla hispana están asociados al programa "Partner" de Twitch, lo cual sugiere una gran participación y audiencia.
4. Las correlaciones más fuertes se observan entre el número de seguidores y el pico de vistas simultáneas.
5. Identificación de los principales canales en español por número de seguidores y máximo de vistas.

## Ejecución del Código

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/twitch_analytics_espanol.git
