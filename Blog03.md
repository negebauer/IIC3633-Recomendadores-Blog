<table><tr><td>
  <a href="./Blog02.md">Anterior</a>
</td><td>
  <a href="./Lecturas/Blog03.pdf">Lectura</a>
</td><td>
  <a href="./README.md">Indice</a>
</td><td>
  <a href="./Blog04.md">Siguiente</a>
</td></tr></table>

***

# Item-Based Collaborative Filtering Recommendation Algorithms

A diferencia del CF basado en usuarios, el _Item-Based_ CF se basa en la comparación de _items_ para hacer recomendaciones.
Primero revisa la matriz usuario-item y descubre relaciones entre los distintos _items_.
Luego usa dichas relaciones para computar indirectamente recomendaciones para los usuarios.

El paper comienza mencionando trabajos relacionados.
Esto es interesante ya que se van enunciando las fortalezas y debilidades de varias maneras de implementar sistemas recomendadores.

En la explicación de _CF_ se restringen al ejemplo de comprar _items_ en un _E-Commerce_, siendo que _CF_ sirve para mucho más que solo eso.
Podrían haber mencionado un ejemplo más general o más de uno específico.

Me gusta del paper que explica como funciona _CF_ en general, los resultados esperados y las dos categorías (_memory_ y _model_ _based_).
Hace que el paper sea más accesible para cualquier lector y en particular me sirve como repaso de clases.

Se explica detalladamente el problema de _CF_
 basado en usuarios, siguiendo con la misma lína del principio del paper.
 Con ello queda muy claro porque es necesario explorar nuevos modelos de _CF_.

Me gusta lo detallado de la explicación de _model based_ _CF_.
Se explican las fórmulas y se acompañan con figuras para visualizar que está sucediendo.

Interesante el que dado que se esta filtrando por items, los cuales son más estáticos, se abre la posibilidad de guardar el modelo (o parte de este).
Esto permite reducir el trabajo de cómputo, pero se tiene un _trade off_.
Este es el común memoria vs rendimiento.

Me llama la atención que el paper es bastante detallado con varios temas, pero cuando se llega a la sección de métricas de evaluación esto ya no se cumple.
Menciona varias técnicas de evaluación pero solo se explican 2 en detalle.
Me habría gustado ver un poco más de ello.
De todas maneras se explica bien porque se usa la técnica elegida.

Me gusta el detalle de las experimentaciones y las figuras que las acompañan.
Queda muy claro que _item_item_ es un muy buen sistema _CF_.

### Referencias

Sarwar, B., Karypis, G., Konstan, J., & Riedl, J. (2001, April). _Item-based collaborative filtering recommendation algorithms._ In Proceedings of the 10th international conference on World Wide Web (pp. 285-295). ACM.
