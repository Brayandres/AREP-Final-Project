# Sistema de gestión de información a través de Big data para el reconocimiento y la reducción de la deserción estudiantil

## Problemática a resolver
La temática elegida es la deserción estudiantil, que vemos que es uno de los fenómenos que más afectan al sistema educativo a nivel mundial, haciendo que tenga repercusiones negativas sobre el estudiante mismo y sobre la sociedad.
La deserción estudiantil es un proceso que puede ser realmente complejo, ya que comprende múltiples aspectos tales como las condiciones socioeconómicas del individuo, su afinidad con la entidad educativa, su contexto social, su mentalidad, cuanto tiempo puede dedicar el estudiante a su proceso educativo, etc.; y que finalmente es la unión y el peso de todo esto lo que lleva a que una persona tome la decisión o quede obligada a desertar de su escuela, colegio, instituto o universidad; de manera que la responsabilidad suele caer casi que por completo sobre el estudiante, y esto es un error que se debe evitar, ya que entre más participativos seamos sobre todas las acciones de cada estudiante, conociendo las verdaderas razones de fondo, podremos ir generando estrategias máss efectivas para combatir eficazmente este fenómeno.

## Propuesta de solución

### Descripción
Una herramienta construída en AWS lo suficientemente potente y de alta velocidad como para trabajar con Big Data, en la que haciendo apoyándonos en la solución Redshift de Amazon vamos a poder manejar enormes volúmenes de datos que gestionaremos y analizaremos para poder brindar información inteligente y útil a las entidades educativas y a los estudiantes.

Así, la herramienta trabaja de manera en que puede recopilar, almacenar y analizar los datos de distintas instituciones educativas, lo que permitirá obtener resultados relacionados con el rendimiento de los estudiantes y asi mismo generar alertas al encontrar ciertos patrones de comportamiento que indiquen que el estudiante podría estar cerca de tomar la decisión de desertar si ha tenido un mal rendimiento, o también encontrar si podría requerir un cambio de metodología, o en última instancia y de manera más generalizada saber qué tan probable es que el estudiante abandone sus estudios.
La intención es que a través del entendimiento de esta información que podamos obtener de los datos, las entidades educativas puedan construír estrategias eficientes que puedan ser implantadas en las políticas institucionales y que generen un cambio positivo en la tarea de combatir la deserción. También, la idea es que las instituciones estén integrando sus propios datos en la plataforma, ya que así aportan a brindar más datos valiosos que generan información relevante para el país.

Nuestra plataforma también va enfocada a edtudiantes, de manera que estos también puedan obtener consejos e información a fin de evitar su proceso de deserción y entender qué motiva este fenómeno.

![Structure](https://github.com/Brayandres/AREP-Final-Project/Resources/Structure.png)


### Construcción y Arquitectura
Nuestra plataforma está construída sobre un modelo de SQL que facilita el acceso a datos teniendo en cuenta que SQL representa un estandar importante hoy en día. Así,  el proceso de conexión para entidades educativas, gubernamentales e interesadas será gestionado a través de un driver JDBC que permitirá obtener la información sobre los datos de nuestra base de datos.
La plataforma está diseñada para que las entidades puedan obtener datos y para que también puedan cargarlos.

La herramienta cuenta con distintas tablas que están cargadas con cantidades enormes de datos. La solución Redshift de Amazon entra en juego cuando deseamos generar análisis eficientes y valiosos sobre cantidades tan enormes de datos.
	
![Architecture](https://github.com/Brayandres/AREP-Final-Project/Resources/Architecture.jpg)


### Funcionamiento

- Video del experimento

	[![Experimento](https://www.learntotrade.com.ph/assets-lttph/uploads/2016/04/video-preview-pic.jpg)](https://drive.google.com/file/d/1jGYr5kTdyOwev9gYbPRozdvBwhmjRTDm/view)

- Uso y manejo de Amazon Redshift

	![Redshift](https://github.com/Brayandres/AREP-Final-Project/Resources/Redshift.jpg)

-  Test de carga y uso masivo en consulta de datos.

	![Tests](https://github.com/Brayandres/AREP-Final-Project/Resources/Tests.jpg)


## Oportunidades
Teniendo en cuenta la problemática trabajada, las características que ofrece nuestra herramienta, encontramos una serie de contextos en donde vemos que es realmente útil el uso de la solución propuesta. Claramente, todos estos contextos estan vinculados al ámbito educativo. Así, entre los posibles involucrados claves tenemos entidades gubernamentales y privadas, escuelas, colegios, institutos y universidades e Instituciones de Educación Superior, más específicamente:

- SENA

	![LogoSena](https://www.funcionpublica.gov.co/documents/418537/29620290/Sena.png)


- Ministerio de Educación

	![LogoMinEducación](https://iedepartamentalfunza.edu.co/assets/img/mineducacion.jpg)


- Escuela Colombiana de Ingeniería Julio Garavito

	![LogoECI](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Escuela_Colombiana_de_Ingenier%C3%ADa_2.jpg/300px-Escuela_Colombiana_de_Ingenier%C3%ADa_2.jpg)



## Estado de innovación
En pro de aprovechar todas las características ofrecidas por el proceso de transformación de la herramienta creada, se pretende ofrecer los siguientes servicios como una extensión de lo que ofrece nuestra propuesta de solución.
La idea es que todos estos servicios puedan ser aprovechados por medio de la plataforma web.
Destacar que en una primera instancia, solo va a estar disponible para Colombia.

![MapsWireframe](https://github.com/Brayandres/AREP-Final-Project/Resources/MapsWireframe.jpg)

- Ponderado de datos por región:
La idea es que se puedan mostrar a través de distintos mapas cada uno de los parámetros interesantes y pertinentes a la deserción estudiantil, así, vamos a poder identificar más fácilmente por regiones cuales son las mayores afectaciones de cada zona, y cuáles han sido o serían las estrategias más útiles que se podrían aplicar, o sea, las que se han probado útiles en esa zona.

- Mapa de distribución de factores de deserción:
Aquí se pretende que se pueda identificar más fácilmente cuales son los factores que más atacan a una región, lo que facilita la construcción en comunidad de estrategias acordes, ya que se está teniendo en cuenta el contexto implicado y no una globalización de este.
$Mapa afectaciones$

- Mapa de estrategias aplicadas
Se pretende que al consultar está información, los interesados puedan tomar decisiones basadas en las experiencias previas y puedan aplicar con mayor eficacia u confianza las soluciones encontradas.
O también, en el caso de haber aplicado una estrategia y haberla encontrado útil, se podría anexar como un caso de éxito en la región respectiva.
$Mapa Soluciones$

- Mapa por tasas de deserción
Este es el mapa que cuenta con la información de las estadísticas encontradas relacionadas con las tasas de deserción.

## Autores
[Brayan Andrés Macías Turmequé](https://github.com/brayandres)

[Kevin Edilson Garzón Piraban](https://github.com/kevinegp)

[Cristhian Camilo Torres Castro](https://github.com/)

[Mateo Ernesto Quintero Acevedo](https://github.com/mateo9931)

[Brayan Alexis Jimenez Moya](https://github.com/bjm19)

## Licencia & Derechos de Autor
**©** Brayan Andrés Macías Turmequé, Kevin Edilson Garzón Piraban, Cristhian Camilo Torres Castro, Mateo Ernesto Quintero Acevedo, Brayan Alexis Jimenez Moya. Estudiantes de Ingeniería de Sistemas de la [Escuela Colombiana de Ingeniería Julio Garavito](https://www.escuelaing.edu.co/es/).

Licencia bajo la [GNU General Public License](https://github.com/Skullzo/AREP-Proyecto/blob/main/LICENSE).