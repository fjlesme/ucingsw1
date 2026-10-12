# Unidad 5 — Especificación del Software

## Ejercitario

| Campo | Detalle |
|---|---|
| **Materia** | Ingeniería de Software 1 |
| **Unidad** | 5 — Especificación del software |
| **Temas cubiertos** | Utilidad de las especificaciones · Especificación de cualidades · Estilos de especificación · Verificación de las especificaciones · Especificaciones operacionales · Especificaciones descriptivas · Construcción y uso en la práctica · Especificación basada en modelos · Otros modelos |
| **Cantidad de preguntas** | 18 |

---

## Tema 1 — Utilidad y cualidades de las especificaciones

**1.** Explique por qué se dice que una especificación funciona como un "contrato" entre quien produce un componente y quien lo utiliza. Ilustre la idea con un ejemplo de especificación de módulo en un sistema que usted conozca.

**2.** Mencione al menos cuatro usos de una especificación a lo largo del ciclo de vida del software y explique brevemente cada uno.

**3.** *(Aplicación)* El siguiente requisito fue extraído de un documento real:

> "El sistema notificará al cliente y al vendedor cuando el pedido supere los 5.000.000 Gs. o tenga más de 10 ítems y el cliente no sea mayorista."

Identifique la ambigüedad, escriba las dos (o más) lecturas posibles usando conectivos lógicos (∧, ∨, ¬) y proponga una redacción en lenguaje natural que admita una sola interpretación.

**4.** *(Verdadero o Falso — justifique su respuesta)*
"Una especificación que define todos los términos que utiliza es necesariamente completa."

---

## Tema 2 — Estilos de especificación y su verificación

**5.** Explique la diferencia entre una especificación operacional y una descriptiva. Para el problema "obtener el máximo de un arreglo de enteros", escriba una especificación de cada estilo.

**6.** ¿Qué se entiende por grado de formalidad de una notación? Dé un ejemplo de notación informal, uno de semiformal y uno de formal, justificando la clasificación.

**7.** Distinga validación de verificación de una especificación. ¿Cuál de las dos puede realizarse sin participación del cliente? Justifique.

---

## Tema 3 — Especificaciones operacionales

**8.** *(Aplicación — DFD)* Elabore un DFD de nivel 1 para el proceso de préstamo de libros de una biblioteca universitaria, que incluya al menos: una entidad externa, tres procesos, dos almacenes y los flujos de datos correspondientes con sus nombres.

**9.** A partir del DFD del ejercicio anterior, señale dos preguntas sobre el comportamiento del sistema que el diagrama no permite responder. ¿Qué limitación de la notación pone en evidencia cada una?

**10.** *(Aplicación — MEF)* Especifique mediante una máquina de estados finitos el comportamiento de una puerta automática con los estados *Cerrada*, *Abriendo*, *Abierta* y *Cerrando*, y las entradas *sensor activado*, *fin de apertura*, *fin de cierre* y *tiempo agotado*. Presente el diagrama y la tabla de transición.

**11.** *(Aplicación — Redes de Petri)* Modele con una red de Petri un sistema productor–consumidor con un buffer de capacidad 2. Indique el marcado inicial y explique qué situación de la red corresponde a "buffer lleno".

---

## Tema 4 — Especificaciones descriptivas

**12.** Escriba la pre y la postcondición de una operación `insertarOrdenado(a, n, x)` que inserta el valor `x` en un arreglo `a` de `n` elementos ordenado de menor a mayor, de modo que el resultado siga ordenado.

**13.** Considere la siguiente especificación de una función que calcula la raíz cuadrada entera:

> { x ≥ 0 } r := raiz(x) { r · r ≤ x }

Muestre un valor de `r` que satisfaga la postcondición sin ser el resultado esperado y corrija la especificación.

**14.** *(Aplicación — especificación algebraica)* Especifique algebraicamente el TAD `Cola` con las operaciones `nueva`, `encolar`, `desencolar`, `frente` y `esVacía` (signatura y axiomas). Luego, usando sus axiomas, calcule por reescritura el valor de:

> frente(desencolar(encolar(encolar(nueva, 4), 9)))

---

## Tema 5 — Construcción y uso de especificaciones en la práctica

**15.** Para un sistema de reserva de turnos médicos, indique qué notación vista en la unidad elegiría para especificar cada uno de los siguientes aspectos, justificando su elección: (a) los datos de pacientes, médicos y turnos; (b) los estados por los que pasa un turno; (c) el efecto de la operación "cancelar turno".

**16.** Escriba una historia de usuario con dos escenarios de aceptación en formato Dado / Cuando / Entonces para la funcionalidad "cancelar turno". Indique qué parte de cada escenario corresponde a la precondición y cuál a la postcondición.

---

## Tema 6 — Especificación basada en modelos y otros modelos

**17.** Compare la especificación algebraica con la especificación basada en modelos: ¿cómo se describe el estado en cada una? Mencione un lenguaje representativo de cada enfoque.

**18.** *(Aplicación — Z / OCL)* Para una clase `CuentaBancaria` con un atributo `saldo` y una operación `extraer(monto)`, escriba en notación Z o en OCL:
- un invariante que impida saldos negativos;
- la precondición y la postcondición de `extraer`.

---

## Cuadro de clasificación

Clasifique cada notación según su estilo y su grado de formalidad, marcando con una X las columnas correspondientes (una por cada grupo).

| Notación | Operacional | Descriptiva | Semiformal | Formal |
|---|---|---|---|---|
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

Relacione cada concepto de la columna A con su definición correspondiente de la columna B, escribiendo en la tercera columna la letra que corresponda.

| Columna A | Columna B | Respuesta |
|---|---|---|
| 1. Completitud interna | a. Marca que indica que una condición se cumple en un lugar de una red de Petri | |
| 2. Explosión de estados | b. Ecuación que relaciona las operaciones de un tipo abstracto de datos | |
| 3. Token | c. Todo término usado en la especificación está definido en ella | |
| 4. Axioma | d. Condición que debe cumplirse siempre, antes y después de cada operación | |
| 5. Invariante | e. Crecimiento multiplicativo del número de estados al componer máquinas | |
| 6. Precondición | f. Lo que debe ser verdadero antes de invocar una operación para que esta garantice su resultado | |
