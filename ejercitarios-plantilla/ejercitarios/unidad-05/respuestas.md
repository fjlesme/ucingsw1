# Respuestas — Ejercitario Unidad 05

> Completen cada pregunta debajo de su enunciado. Pueden borrar este bloque de instrucciones una vez que empiecen.

---

## Tema 1 · Utilidad y cualidades de las especificaciones

**1. Expliquen por qué se dice que una especificación funciona como un "contrato" entre quien produce un componente y quien lo utiliza. Ilustren la idea con un ejemplo de especificación de módulo en un sistema que conozcan.**

_Respuesta:_


**2. Mencionen al menos cuatro usos de una especificación a lo largo del ciclo de vida del software y expliquen brevemente cada uno.**

_Respuesta:_


**3. (Aplicación) Dado el requisito "El sistema notificará al cliente y al vendedor cuando el pedido supere los 5.000.000 Gs. o tenga más de 10 ítems y el cliente no sea mayorista", identifiquen la ambigüedad, escriban las dos (o más) lecturas posibles usando conectivos lógicos (∧, ∨, ¬) y propongan una redacción en lenguaje natural que admita una sola interpretación.**

_Respuesta:_


**4. (Verdadero o Falso — justifiquen) "Una especificación que define todos los términos que utiliza es necesariamente completa."**

_Respuesta:_


---

## Tema 2 · Estilos de especificación y su verificación

**5. Expliquen la diferencia entre una especificación operacional y una descriptiva. Para el problema "obtener el máximo de un arreglo de enteros", escriban una especificación de cada estilo.**

_Respuesta:_


**6. ¿Qué se entiende por grado de formalidad de una notación? Den un ejemplo de notación informal, uno de semiformal y uno de formal, justificando la clasificación.**

_Respuesta:_


**7. Distingan validación de verificación de una especificación. ¿Cuál de las dos puede realizarse sin participación del cliente? Justifiquen.**

_Respuesta:_


---

## Tema 3 · Especificaciones operacionales

**8. (DFD) Elaboren un DFD de nivel 1 para el proceso de préstamo de libros de una biblioteca universitaria, que incluya al menos: una entidad externa, tres procesos, dos almacenes y los flujos de datos correspondientes con sus nombres.**

_Respuesta:_


**9. A partir del DFD del ejercicio anterior, señalen dos preguntas sobre el comportamiento del sistema que el diagrama no permite responder. ¿Qué limitación de la notación pone en evidencia cada una?**

_Respuesta:_


**10. (MEF) Especifiquen mediante una máquina de estados finitos el comportamiento de una puerta automática con los estados _Cerrada_, _Abriendo_, _Abierta_ y _Cerrando_, y las entradas _sensor activado_, _fin de apertura_, _fin de cierre_ y _tiempo agotado_. Presenten el diagrama y la tabla de transición.**

_Respuesta:_


**11. (Redes de Petri) Modelen con una red de Petri un sistema productor–consumidor con un buffer de capacidad 2. Indiquen el marcado inicial y expliquen qué situación de la red corresponde a "buffer lleno".**

_Respuesta:_


---

## Tema 4 · Especificaciones descriptivas

**12. Escriban la pre y la postcondición de una operación `insertarOrdenado(a, n, x)` que inserta el valor `x` en un arreglo `a` de `n` elementos ordenado de menor a mayor, de modo que el resultado siga ordenado.**

_Respuesta:_


**13. Dada la especificación `{ x ≥ 0 } r := raiz(x) { r · r ≤ x }` de una función que calcula la raíz cuadrada entera, muestren un valor de `r` que satisfaga la postcondición sin ser el resultado esperado y corrijan la especificación.**

_Respuesta:_


**14. (Especificación algebraica) Especifiquen algebraicamente el TAD `Cola` con las operaciones `nueva`, `encolar`, `desencolar`, `frente` y `esVacía` (signatura y axiomas). Luego, usando sus axiomas, calculen por reescritura el valor de `frente(desencolar(encolar(encolar(nueva, 4), 9)))`.**

_Respuesta:_


---

## Tema 5 · Construcción y uso de especificaciones en la práctica

**15. Para un sistema de reserva de turnos médicos, indiquen qué notación vista en la unidad elegirían para especificar cada uno de los siguientes aspectos, justificando su elección: (a) los datos de pacientes, médicos y turnos; (b) los estados por los que pasa un turno; (c) el efecto de la operación "cancelar turno".**

_Respuesta:_


**16. Escriban una historia de usuario con dos escenarios de aceptación en formato Dado / Cuando / Entonces para la funcionalidad "cancelar turno". Indiquen qué parte de cada escenario corresponde a la precondición y cuál a la postcondición.**

_Respuesta:_


---

## Tema 6 · Especificación basada en modelos y otros modelos

**17. Comparen la especificación algebraica con la especificación basada en modelos: ¿cómo se describe el estado en cada una? Mencionen un lenguaje representativo de cada enfoque.**

_Respuesta:_


**18. (Z / OCL) Para una clase `CuentaBancaria` con un atributo `saldo` y una operación `extraer(monto)`, escriban en notación Z o en OCL: un invariante que impida saldos negativos, y la precondición y la postcondición de `extraer`.**

_Respuesta:_


---

## Cuadro de clasificación

**19. Clasifiquen cada notación según su estilo y su grado de formalidad, marcando con una X las columnas correspondientes (una por cada grupo).**

| Notación | Operacional | Descriptiva | Semiformal | Formal |
| --- | --- | --- | --- | --- |
| Diagrama de flujo de datos (DFD) | | | | |
| Máquina de estados finitos | | | | |
| Red de Petri | | | | |
| Diagrama Entidad-Relación | | | | |
| Pre y postcondiciones en lógica de primer orden | | | | |
| Especificación algebraica | | | | |
| Esquemas en notación Z | | | | |
| Escenarios Dado / Cuando / Entonces | | | | |

---

## Cuadro de relación

**20. Relacionen cada concepto de la columna A con su definición correspondiente de la columna B, escribiendo la letra que corresponda.**

| Columna A | Respuesta |
| --- | --- |
| 1. Completitud interna | |
| 2. Explosión de estados | |
| 3. Token | |
| 4. Axioma | |
| 5. Invariante | |
| 6. Precondición | |

a. Marca que indica que una condición se cumple en un lugar de una red de Petri
b. Ecuación que relaciona las operaciones de un tipo abstracto de datos
c. Todo término usado en la especificación está definido en ella
d. Condición que debe cumplirse siempre, antes y después de cada operación
e. Crecimiento multiplicativo del número de estados al componer máquinas
f. Lo que debe ser verdadero antes de invocar una operación para que esta garantice su resultado
