# Cómo agregar tu grupo a la tabla de trabajos

Este repositorio es de la cátedra: los grupos **no suben sus archivos acá**, solo agregan un enlace a su propio sitio mediante un Pull Request. Así cada grupo mantiene control total de su propio repositorio, y la cátedra mantiene control de este.

## Pasos

1. **Hacé un fork** de este repositorio (botón "Fork" arriba a la derecha en GitHub).

2. En tu fork, editá el archivo [`README.md`](README.md) y agregá **una sola fila** a la tabla de la sección **"👥 Grupos y trabajos"**, con el siguiente formato:

   ```
   | Grupo N | Nombre 1, Nombre 2, Nombre 3 | [Nombre del sistema] | https://usuario.github.io/repositorio/ |
   ```

   - `Grupo N`: un identificador simple (ej. `Grupo 4`).
   - Integrantes: nombres completos de los tres integrantes.
   - Sistema: una frase corta describiendo qué sistema desarrollaron.
   - Sitio del grupo: el enlace a **su** sitio de GitHub Pages (no un repositorio privado, no un enlace a Drive).

3. Guardá el cambio y creá un **Pull Request** hacia este repositorio (`fjlesme/ucingsw1`, rama `main`).

4. En la descripción del Pull Request, indicá el número de grupo y la comisión (si aplica).

5. Esperá la revisión. Una vez aprobado, tu fila quedará visible en la tabla para toda la clase.

## Reglas

- ✅ Un Pull Request agrega o actualiza **únicamente la fila de tu propio grupo**.
- ❌ No modifiques filas de otros grupos, ni otras secciones del `README.md`, ni ningún otro archivo del repositorio.
- ❌ No subas archivos (`.pptx`, `.docx`, imágenes, etc.) a este repositorio — esos van en el repositorio propio de tu grupo.
- 🔄 Si tu enlace cambia (por ejemplo, renombraron el repositorio), abrí un nuevo Pull Request actualizando tu fila.

Un Pull Request que no siga estas reglas será rechazado o editado por la cátedra antes de aprobarse.

---

# Cómo entregar los ejercitarios

Los ejercitarios **no se entregan en este repositorio** ni por Pull Request: se completan directamente en el repositorio propio de cada grupo (el mismo que usan para el Trabajo Práctico).

## Pasos (una sola vez, al principio del cuatrimestre)

1. Descarguen la carpeta de plantilla: [`ejercitarios-plantilla/ejercitarios_carpeta.zip`](ejercitarios-plantilla/ejercitarios_carpeta.zip).
2. Descomprímanla y arrastren la carpeta `ejercitarios/` a la raíz de **su propio repositorio** (el del TP), usando "Add file → Upload files" como ya hicieron con el resto de su repo.
3. Confirmen el commit.

## Por cada unidad

1. Entren a `ejercitarios/unidad-0X/respuestas.md` dentro de **su propio repositorio**.
2. Edítenlo directo desde la web (ícono de lápiz) y completen las respuestas.
3. Guarden el cambio. El commit con fecha anterior al cierre de esa unidad es la entrega válida — no hay ningún paso adicional.

## Reglas

- ✅ Las respuestas se editan y viven en el repositorio del grupo, no acá.
- ❌ No hace falta (ni corresponde) abrir un Pull Request para esto — a diferencia del listado de grupos del TP, acá no hay una tabla central que actualizar.
- 📬 La corrección la hace la cátedra entrando directamente al repositorio del grupo, usando el enlace ya publicado en la tabla de [Grupos y trabajos](README.md#-grupos-y-trabajos).

