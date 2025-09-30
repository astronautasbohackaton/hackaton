# Repositorio AstronautasBO hackaton Space Apps NASA 2025
Repository AstronautasBO Hackaton Space Apps NASA 2025
RETO CHALLENGE NASA SPACE APPS HACKATON - EQUIPO ASTRONAUTASBO

## Resumen

Si estás planeando un evento al aire libre —como unas vacaciones, una caminata por un sendero o una jornada de pesca en un lago— sería útil conocer las probabilidades de mal clima para el momento y lugar que estás considerando. Existen muchos tipos de datos de observación de la Tierra que pueden proporcionar información sobre las condiciones meteorológicas en un lugar específico y en un día del año. Tu desafío es construir una aplicación con una interfaz personalizada que permita a los usuarios realizar una consulta adaptada para indicarles la probabilidad de condiciones “muy calurosas”, “muy frías”, “muy ventosas”, “muy húmedas” o “muy incómodas” en el lugar y momento que especifiquen.


##BACKGROUNG

Aunque prácticamente todo el mundo desearía tener un clima perfecto para un día de playa, un desfile festivo, una caminata en el bosque o un almuerzo en un parque de la ciudad, eso no siempre ocurre. Para estar preparados ante lo que el clima pueda traer, sería deseable contar con un conocimiento preciso de qué tan probables son las buenas o malas condiciones meteorológicas en un lugar y momento específicos. Conocer las probabilidades de cómo podría ser el clima no es un pronóstico, ya que dichas probabilidades se basan en datos históricos del tiempo y no en un modelo predictivo. Sin embargo, conocer las condiciones históricas proporciona información que puede ayudar a los usuarios a estar mejor preparados e, incluso, a decidir evitar lugares y momentos donde el mal tiempo sea probable. (Por supuesto, el “mal clima” para una persona podría ser un clima deseado para otra. Por ejemplo, mientras algunas personas detestarían una fuerte nevada, los esquiadores y snowboarders podrían recibirla con entusiasmo).

La NASA ha recopilado una gran cantidad de datos meteorológicos globales durante varias décadas. Algunos ejemplos de los tipos de datos (variables) recopilados incluyen: precipitaciones, velocidad del viento, concentración de polvo, temperatura (incluyendo índices extremos), nevadas y profundidad de la nieve, y cobertura nubosa. Además, la NASA ha desarrollado modelos que pueden usar estas variables para establecer las condiciones climáticas típicas de un lugar y momento determinados (estación/mes/día del año), así como las probabilidades de que ocurran condiciones meteorológicas extremas.

Muchas aplicaciones pueden proporcionar pronósticos del clima con 1 a 2 semanas de anticipación, incluyendo valores “normales” promedio para muchos lugares. Sin embargo, sería útil contar con una aplicación que pueda determinar cuáles son las condiciones climáticas probables en un lugar y momento específicos con varios meses de anticipación. Los datos de observación terrestre de la NASA pueden usarse para crear un compendio de datos para una ubicación seleccionada en cualquier época del año y así determinar esta información. Además, dado que las condiciones están cambiando en muchos lugares, los datos de la NASA también pueden emplearse para estimar si la probabilidad de lluvias intensas, temperaturas peligrosamente altas, alta humedad o olas de calor ha ido aumentando en una ubicación en un momento específico del año.

##OBJETIVOS

Tu desafío es desarrollar una aplicación que use datos de observación terrestre de la NASA y permita a los usuarios crear un panel personalizado para obtener información sobre la probabilidad de condiciones meteorológicas específicas (por ejemplo, temperatura, precipitaciones, calidad del aire, velocidad del viento, etc.) en una ubicación y fecha (día del año) que ellos seleccionen.

Piensa en cómo los usuarios proporcionarán la información (por ejemplo, la ubicación deseada) en el panel. ¿Escribirán el nombre de un lugar, dibujarán un límite en un mapa o colocarán un “pin” en un mapa existente? ¿Qué tipo de información sería más útil para tus usuarios objetivo? Tal vez deseen ver un promedio a lo largo del tiempo para las variables especificadas y comprender la probabilidad de superar ciertos umbrales (por ejemplo, un 60% o más de probabilidad de condiciones de calor extremo por encima de los 90 grados Fahrenheit).

¿Cómo proporcionará tu aplicación la información deseada? ¿Los usuarios verán gráficos o mapas que ilustren la probabilidad de estos eventos meteorológicos acompañados de una explicación sencilla en texto, u otra cosa? No olvides que algunos usuarios también desearán la capacidad de descargar un archivo de salida que contenga el subconjunto de datos relacionado con la consulta (es decir, las variables relevantes para la ubicación y el momento de interés especificados).

POTENCIALES CONSIDERACIONES

Puedes (pero no estás obligado a) considerar lo siguiente:

Los datos de salida que contengan metadatos con unidades y enlaces a las fuentes de entrada podrían estar disponibles fuera de la aplicación y descargarse en formato CSV (Comma Separated Values) o JSON (JavaScript Object Notation).

Los usuarios de esta aplicación probablemente tendrán un entendimiento suficiente de las variables disponibles en la interfaz (precipitaciones, velocidad del viento, concentración de polvo, temperatura, etc.); por lo tanto, tu aplicación no necesariamente tendrá que definirlas.

No olvides asegurarte de que la lista de variables potenciales que los usuarios puedan elegir cubra las principales condiciones meteorológicas en las que se esperaría que las personas interesadas en actividades al aire libre estuvieran interesadas. Demasiadas variables podrían resultar confusas, así que ten cuidado de no usar demasiadas diferentes para la misma magnitud (por ejemplo, existen varios tipos de datos de precipitaciones, por lo que la selección de la variable más útil/precisa es importante).

Piensa en cómo tu herramienta podría proporcionar una representación visual de los resultados y, quizá, ofrecer la opción de descargar esa salida. ¿Sería mejor mostrar una curva de campana que indique el rango de probabilidades, una serie temporal en un punto, o un promedio en un área especificada? Los servicios existentes (ver pestaña Resources) pueden usarse para acceder y extraer subconjuntos de datos, facilitando el cálculo de estadísticas.



