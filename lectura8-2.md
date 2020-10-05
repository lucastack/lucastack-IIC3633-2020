# Lectura: See What You Want to See: Visual User-Driven Approach for Hybrid Recommendation. Parra, D., Brusilovsky, P., and Trattner, C. (2014). 

Al igual que el primer paper de la semana (A user-centric evaluation framework for recommender systems), este se encuentra fundamentalmente centrado en la experiencia de usuario que se tiene con un sistema recomendador. En ese contexto, los investigadores se concentran en el aspecto de la controlabilidad y es allí donde se encuentra su propuesta: *SetFusion*, una interfaz de usuario que permite controlar cómo se hacen las recomendaciones. 

*SetFusion* se encuentra acoplado a un sistema de recomendación híbrido, osea, que mezcla distintas maneras (o algoritmos) de recomendación. La interfaz permite que el usuario modifique que tan importante es cada una de estos tipos de recomendación. Por ejemplo, siguiendo el ejemplo del paper, un usuario podría estar más interesado en las conferencias de autores con más citas y no en aquellas conferencias que hayan sido más marcadas como favoritas. Indirectamente esto trae novedad a las recomendaciones pues si un usuario desea probar algo nuevo entonces basta con que cambie el modo de recomendación por algún otro.

Un problema que tiene el uso de la interfaz es que presupone que las personas que utilizarían *SetFusion* entienden cómo funcionan los distintos tipos de recomendación, lo cual no parece muy razonable para un contexto cualquiera. Convenientemente, los estudios fueron llevados a cabo en conferencias académicas o de investigación, grupo que claramente no es representativo de la sociedad. Debido a esto me parece que los resultados encontrados son de difícil generalización.

Otro punto que aparece a raíz de lo anterior es si realmente poner a disposición un controlador del sistema recomendador mejora la experiencia del usuario, ya que si este no lo entiende le parecerá engorroso y ocurrirá todo lo contrario: preferirá otro sitio web (si corresponde el caso) más simple. Aquí es donde aparece la pregunta ¿Es realmente útil un controlador como *SetFusion* en un contexto más cotidiano, como por ejemplo, en una página de e-commerce? 

En cuanto a la evaluación de la interfaz, me parece que muy apropiado que se le pregunte directamente (por mail en realidad) a los usuarios acerca de su experiencia con *SetFusion*, de esta manera, tal como se muestra en el otro paper de esta semana, se puede realizar una evaluación centrada en el usuario, más alla del rendimiento de los algoritmos.
