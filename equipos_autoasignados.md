# Equipos autoasignados

## Contexto
En muchos casos existe la necesidad de asignar personas a varios equipos, a lo largo del tiempo, y de balancear múltiples variables a la hora de decidir a qué equipo se incorpora cada persona.
En una empresa en la que participó uno de los autores los equipos permanecían estables a lo largo del tiempo y ocurrió que algunos de los miembros deseaban cambiar de proyecto en busca de un contexto más favorable o simplemente de nuevos desafíos.
En otro caso, una empresa de software deseaba cambiar el criterio de armado de sus equipos. Se buscaba pasar de equipos de especialistas a equipos autónomos y multidisciplinarios. Se trataba de un cambio masivo de asignaciones que involucraba a  entre 15 y 20 personas.

## Descripción
Como primer paso se define qué equipos participan de la asignación, qué restricciones existen y cuáles son los objetivos detrás del cambio. Luego se organiza un encuentro con todos los involucrados, se plantea el contexto y se identifica de forma participativa posibles soluciones registrando las alternativas. Finalmente se evalúan las mismas y se selecciona una para llevar a la práctica.
A modo de ejemplo se describe una implementación del patrón, que denominaremos **Tribus Caminantes**. El encuentro debe realizarse en un espacio amplio, en el que inicialmente se demarcan en el piso los equipos buscados y las restricciones de los mismos. Luego se reúne a todo el grupo en el centro del salón y se pide a la gente que camine entre los equipos eligiendo en cuál detenerse hasta que el grupo encuentre una combinación que cumpla con las restricciones. Se registra esta alternativa y se vuelve a buscar una nueva solución. Luego de una serie de iteraciones, se repasan todas las alternativas encontradas, analizando pros y contras a la luz de los objetivos buscados y se selecciona una de ellas.

## Consecuencias
Listamos a continuación algunas ventajas y desventajas de su uso.
Ventajas:
* Promueve que los miembros de los equipos se sientan satisfechos con la asignación resultante al haber participado de la decisión.
* La multiplicidad de miradas tiende a incorporar al proceso criterios no explicitados previamente. Por ejemplo, ciertos criterios difíciles de codificar y percibir externamente, como la afinidad entre dos personas, pueden afectar sensiblemente el resultado.
* Se analizan muchas alternativas en poco tiempo.
* Usar el cuerpo durante el proceso tiende a producir mayor compromiso e involucramiento.
* Se evitan errores porque cada alternativa es evaluada por más miradas.
Desventajas:

Advertencias:
* Los participantes pueden tener vergüenza de moverse al principio. Para evitar esto, puede servir indicar a los participantes que hagan al principio una ronda de caminata alrededor de todos los equipos.
* El encuentro puede hacer emerger ciertos conflictos subyacentes, en particular si hay personas de distinto nivel jerárquico o intereses contrapuestos.
* De acuerdo a la Ley de Conway la arquitectura del producto puede influenciar el armado de los equipos y viceversa.
* Este patrón puede requerir aplicación periódica, por ejemplo, cada tres meses.

## Patrones relacionados
Para la selección de la alternativa al final del patrón pueden utilizarse los patrones de **Decisión Participativa**. Para que la gente se conozca y pueda tomar decisiones informadas, puede utilizarse el patrón de **Polinización Cruzada**.