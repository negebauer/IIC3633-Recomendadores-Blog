<table><tr><td>
  <a href="./Blog09.md">Anterior</a>
</td><td>
  <a href="./Lecturas/Blog10.pdf">Lectura</a>
</td><td>
  <a href="./README.md">Indice</a>
</td><td>
  <a href="./Blog11.md">Siguiente</a>
</td></tr></table>

***

# Hybrid Recommender Systems: Survey and Experiments

El paper hace en primer lugar un acercamiento a varios sistemas recomendadores que están siendo usados al momento de escritura.
Al hacer ello, hace una descripción de cada uno de ellos, mostrando sus puntos fuertes y sus debilidades. También hace comparaciones entre ellos.
Es una buena descripción del estado del arte.
Además está acompañada de muchas referencias a otros papers, lo que muestra un buen trabajo de investigación por parte del equipo.
Interesante notar que las estrategias de recomendación con mayor madurez (colaborativa) tienen más referencias a otros papers que las más nuevas.
También se dan el tiempo de mencionar cuales situaciones son más adecuadas para cada sistema.

Es interesante como se enuncian las debilidades de cada sistema recomendador.
Los autores lo hacen de una forma que deja entrever como el unir los distintos modelos resultará en un mejor sistema.
Esto se ve en partes donde menciona la debilidad de un sistema, luego que otro sistema es fuerte en ese aspecto, pero débil en donde el primero es fuerte.

Me gusta que la descripción de los sistemas híbridos está acompañada de ejemplos reales.
Estos permiten entender de mejor manera su funcionamiento.

También me gusta como en la descripciones va escalando desde el más simple al más complejo.
Esto ya que al final de la descripción de cada sistema menciona algo que introduce al siguiente a través de un beneficio que tiene sobre el anterior.

La tabla sobre posibles híbridos es muy interesante.
No solo muestra donde se ha realizado una mayor investigación, sino que también muestra posibles combinaciones interesantes que aún no han sido exploradas.
Esto puede servir para futuros investigadores al momento de decidir que nuevos híbridos probar.
También ayuda que se explique porque la tabla se ve de esta manera, mencionando como el estado actual (los datos disponibles abiertamente para los investigadores) ha influenciado los híbridos que han sido explorados.
También es útil para futuros investigadores que se menciona una estrategia para decidir que sistema híbrido usar, dando preferencia a sistemas como cascada cuando un recomendador sea siempre mejor y a _switching_ cuando el recomendador más fuerte no sea siempre el mismo.

Se explica como funciona el sistema Entree a través de una historia que deja claro como cada interacción del usuario afecta el resultado final.
Esto permite al lector entender mejor la recomendación de Entree.

La explicación sobre el sistema híbrido que se usó con EntreeC es muy completa.
Se van descartando opciones que tienen problemas o cuyo beneficio no es tan alto.
El ejercicio mental de ejemplo (Alice y Bob) ayuda a comprender mejor aún el efecto del sistema híbrido sobre las recomendaciones, dando al lector otro eje para aprender sobre como funcionan los sistemas híbridos.

Me gustó como se fue construyendo el sistema híbrido, mencionando distintos approachs y descartándolos por sus debilidades.


### Referencias

Robin Burke. 2002. _Hybrid Recommender Systems: Survey and Experiments._ User Modeling and User-Adapted Interaction 12, 4 (November 2002), 331-370. [DOI=10.1023/A:1021240730564](http://dx.doi.org/10.1023/A:1021240730564)
