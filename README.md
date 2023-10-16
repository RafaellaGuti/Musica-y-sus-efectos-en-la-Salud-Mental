#  ES - Musica y sus efectos en la Salud Mental 
En este caso se analizará un data set creado a partir de reportes de 736 participantes que describieron su relación y nivel de exposición con distintos géneros de música y su experiencia en el área de salud mental. El estudio se realizó en el mes de agosto hasta noviembre del año 2022, contando con una duración total de 3 meses.
Los atributos expresados en el data set reflejan con exactitud:

Timestamp, Age, Primary streaming service, Hours per day, While working,
Instrumentalist, Composer, Fav genre, Exploratory, Foreign languages, BPM, Frequency 
[Classical], Frequency [Country], Frequency [EDM], Frequency [Folk], Frequency 
[Gospel], Frequency [Hip hop], Frequency [Jazz], Frequency [K pop], Frequency [Latin],
Frequency [Lofi], Frequency [Metal], Frequency [Pop], Frequency [R&B], Frequency 
[Rap], Frequency [Rock], Frequency [Video game music], Anxiety, Depression, Insomnia,
OCD, Music effects.

Contando asimismo con respuestas tanto numéricas como características, los registros complementarios de estos atributos nos permitirán efectuar un análisis tanto cualitativo como cuantitativo, permitiéndonos expresar las conclusiones del estudio de una manera más completa.

# Herramienta utilizadas
A continuación, se explica a detalle qué herramientas tecnológicas se utilizaron en el proyecto y su objetivo:

- Microsoft Excel: El data set utilizado para el proyecto fue extraído de la web www.Kaggle.com en formato CSV. Se utilizo Excel para separar la data en tablas/hojas y columnas, crear columnas Primary Key y Foreign Key de cada tabla.
- ERD Plus Web Page: Se utilizó la pagina web ERD Plus para realizar el Modelo Entidad- Relación en el formato expuesto en este documento. 
- Power BI Desktop: Se utilizo la aplicación primariamente para elaborar las solapas del Tablero que expresan las visualizaciones de los datos de este proyecto. Para ello, se utilizó Power BI Desktop para desarrollar las siguientes acciones:
• Realizar conexión con Data Set.
• Armar modelo Entidad Relación en la Aplicación.
• Identificar columnas de dimensiones y medidas de 
cada tabla.
• Generar columnas calculadas.
• Generar tablas de Medidas y de Calendario.
• Generar medidas calculadas necesarias para la 
visualización.
• Realizar una maqueta del diseño de visualización 
del proyecto.

- Flat Icon Web Page: Se utilizo la pagina web www.FlatIcon.com para obtener recursos en iconos que contribuyeron al diseño del tablero.
- Adobe Color Web Page: Se utilizo la pagina web www.AdobeColors.com para crear la paleta de colores accesible utilizada en el tablero de visualización del proyecto.
- Microsoft Office Word: Se utilizo Microsoft Word para elaborar el documento que acompaña al tablero en el proyecto.

# Fuente de Datos
www.Kaggle.com

# Objetivos
Este análisis permitirá determinar, en general, si la música tiene efecto en el estado mental de los participantes y qué correlaciones, si las hay, existen entre los hábitos musicales de un individuo y su salud mental reportada:
• Tendencia de resultados de mejoría/empeoramiento/no efecto por edad: Qué
tanto puede afectar la edad del individuo en la tendencia de los resultados.
• Horas consumidas de cada género en cada servicio de Streaming: Cómo afecta la 
duración de exposición y qué servicio es el más utilizado entre los 736 
participantes.
• Relación entre géneros musicales y resultados de mejoría/empeoramiento/no 
efecto: Qué grupo de géneros hacen proceso de mejoría en los síntomas 
mencionados en los reportes (ansiedad, OCD, Depresión, Insomnio).
• Examinar relación de preferencias/gusto: cómo factores como preferencias 
musicales afectan en la mejoría/empeoramiento de los síntomas reportados.
• Porcentaje de mejoría presentada en individuos que componen o tocan algún 
instrumento musical.
• Porcentaje de mejoría presentada en individuos que escuchan música mientras 
trabajan/estudian.
• Porcentaje de mejoría presentada en individuos que escuchan música en otros 
idiomas. 
• Porcentaje de mejoría presentada en individuos que frecuentemente exploran 
nuevos artistas/géneros.

# Preparacion de Datos
- Limpieza y Manipulacion:
  Utilizando Microsoft Excel y the Power Query en PowerBI Desktop:
  - Remover duplicados y data irrelevante
  - Manejar los datos faltantes manipulando con precisión los valores nulos y usándolos de una manera que agregue al estudio en lugar de ser un inconveniente.
  - Se corrigieron y manejaron errores estructurales con las herramientas proporcionadas por los programas.

# Analisis de los datos, interpretacion y Visualizacion 
El estudio concluyó con un panel interactivo de Power BI que incluye:
- Portada - Paginacion
- Glosario : El glosario realizado para el proyecto incluye términos específicos relevantes para la 
comprensión e interpretación de la información en el tablero, en el documento pdf explicamos las fuentes de cada termino.
- Reportes Generales : Esta solapa responde a una introducción informativa al contexto del análisis. Utilizando la segmentación podemos observar la cantidad de participantes que reportaron mejoría o desmejora en los síntomas presentados y el rango de edad en que se encuentran, así como el puntaje promedio que presentan.
- Factores Influyentes en los Resultados : Es importante recalcar que cada participante puede tener mas de un habito musical. Esta solapa responde a preguntas de naturaleza operativa e informativa sobre la relación entre el nivel de exposición a la música diariamente (Preferida o no), hábitos musicales y la Mejoría o Desmejora en los síntomas de los participantes.
- Géneros Musicales y Síntomas : Esta solapa tiene como objetivo relacionar el género musical con los síntomas crónicos
presentados y realizar conclusiones.
- Tooltip – Géneros Musicales y Síntomas : La última solapa está destinada a la creación del Tooltip utilizado en la solapa ‘Géneros
Musicales y Síntomas’ sobre el grafico correspondiente. Su objetivo es aportar a la identificación de la relación entre la preferencia de genero musical y el resultado de Mejoría o Desmejora en los participantes.

# Futuras lineas
Para el complemento y la posterior mejora de la exposición de la información es recomendable profundizar la investigación y recolección de datos para:
• Proveer conclusiones sobre los síntomas que sean medibles en el tiempo.
• Ubicar participantes geográficamente e incluir estudios sobre factores como: cultura 
y condiciones en las cuales se consume algún género musical.
• Incluir factores cotidianos adicionales y de desempeño mental y anímico.
Con estas adiciones podremos expresar el efecto de la música en general en la mente de manera más detallada y medible.

# Documento ampliado
https://github.com/RafaellaGuti/Musica-y-sus-efectos-en-la-Salud-Mental/blob/main/Rafaella%20Gutierrez%20Musica%20y%20sus%20efectos%20en%20la%20salud%20mental%20Documentacion.pdf


