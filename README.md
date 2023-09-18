# Recopilación sobre competiciones matemáticas
Teoremas, problemas y soluciones de problemas de olimpiadas y competiciones matemáticas.

## Estructura de los ficheros TeX
(Inicialmente) el repositorio en el branch `master`contiene fundamentalmente texto en formato TeX. Los contenidos se han organizado de forma que se favorezca la reutilización. Es por eso que los teoremas y los problemas se han colocado en carpetas aparte, con los enunciados separados de las soluciones.

Para clasificar la información se han considerado dos criterios fundamentales. En primer lugar se han identificado las competencias y olimpiadas que son de interés para la recopilación. Cada caso tiene una carpeta que incluye entradas para cada edición de acuerdo al año en que se realizó. A través de un enlace simbólico, los enunciados se clasifican atendiendo al año y la competencia en que el problema apareció en el alguno de los temarios, shortlist o longlist. En cada carpeta de este tipo se incluye un fichero TeX para los temarios por día, con los enunciados nada más. En otro fichero aparte se redactan los problemas con sus respectivas soluciones.

Otra clasificación posible es por temas. Para este fin se recurre al [MSC2020](https://msc2020.org/). Cada categoría tiene su propia carpeta. A parir de ese nivel, recursivamente, cada una incluye otras carpetas para cada uno de sus subtemas. A través de enlaces simbólicos dentro de cada categoría se relacionan los teoremas y problemas que tienen que ver con cada tema.

### Otras clasificacionnes posibles
Las clasificaciones precedentes no son las únicas posibles. A continuación se incluyen ideas que pueden ser útiles, pero que todavía no se han implementado.

- Por niveles de dificultad de problemas.
- Por niveles de entrada de los teoremas, atendiendo a una lógica del aprendizaje progresivo y continuo de los concursantes. En parte considerando también una relación de orden entre dos teoremas en la que el "más complejo" (con nivel de entrada superior) utiliza al "más simple" (con nivel de entrada inferior) para su demostración.
