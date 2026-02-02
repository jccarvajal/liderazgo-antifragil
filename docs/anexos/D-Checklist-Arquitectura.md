# ANEXO D: CHECKLIST DE ARQUITECTURA DE RESPONSABILIDAD
### Auditoría Estructural del Organigrama y Flujos de Decisión

**Instrucciones de Uso:**
Seleccione un proceso crítico o un departamento. Responda "SÍ" o "NO" a las siguientes preguntas de verificación.
**Regla de Oro:** Cualquier respuesta "NO" indica una "Falla de Diseño" (Bug) en su arquitectura organizacional que generará latencia, error o abdicación.

---

## 1. ALINEACIÓN DE AUTORIDAD Y DATOS (Proximidad)
*El principio: La decisión debe vivir donde vive la información.*

| Check | Pregunta de Auditoría | Por qué importa (Riesgo) |
| :---: | :--- | :--- |
| [ ] | **¿La persona que toma la decisión tiene acceso directo a la fuente primaria de datos?** | Si decide leyendo un resumen de un resumen, decide sobre una ficción (Teléfono descompuesto). |
| [ ] | **¿Las decisiones rutinarias (Zona Verde) están delegadas al nivel más bajo posible?** | Si el Director aprueba vacaciones o compra de insumos básicos, es un cuello de botella costoso. |
| [ ] | **¿El tiempo entre la detección del problema y la acción correctiva es menor a X horas?** | Mide la latencia. Si el trámite tarda más que la evolución del problema, el control es inútil. |

---

## 2. CLARIDAD DE PROPIEDAD (Accountability)
*El principio: Responsabilidad Indivisible.*

| Check | Pregunta de Auditoría | Por qué importa (Riesgo) |
| :---: | :--- | :--- |
| [ ] | **¿Existe una ÚNICA persona con nombre y apellido responsable del resultado final?** | Si la responsabilidad es de un "Comité" o un "Departamento", nadie es responsable. |
| [ ] | **¿Esa persona tiene la autoridad (presupuesto/recursos) para cumplir esa responsabilidad?** | Responsabilidad sin Autoridad es una trampa mortal (Chivo Expiatorio). |
| [ ] | **¿Están definidos claramente los límites entre el Dueño del Riesgo (Negocio) y el Gestor del Riesgo (TI/Legal)?** | Evita el clásico "Yo pensé que Ciberseguridad decidía el apetito de riesgo". |

---

## 3. MECANISMOS DE SEGURIDAD (Frenos de Emergencia)
*El principio: Soberanía y Protección.*

| Check | Pregunta de Auditoría | Por qué importa (Riesgo) |
| :---: | :--- | :--- |
| [ ] | **¿Tiene el personal de línea autoridad formal para DETENER el proceso (Stop-Work Authority) ante un peligro inminente?** | Si deben pedir permiso para no estrellarse, se estrellarán. |
| [ ] | **¿Existen "Líneas Rojas" explícitas (qué NO hacer) en lugar de micro-gestión (cómo hacerlo)?** | Permite el Mando de Misión (Autonomía segura). |
| [ ] | **¿Existe un canal seguro y probado para escalar malas noticias sin represalias?** | Sin esto, el "Iceberg de la Ignorancia" crece. |

---

## 4. RESILIENCIA Y CONTINUIDAD (Bus Factor)
*El principio: Antifragilidad y redundancia.*

| Check | Pregunta de Auditoría | Por qué importa (Riesgo) |
| :---: | :--- | :--- |
| [ ] | **¿Si el líder del área desaparece hoy por un mes, el equipo puede seguir tomando decisiones operativas?** | Mide la dependencia de héroes (SPOF / Bus Factor). |
| [ ] | **¿Están documentados los criterios de decisión, no solo los pasos del proceso?** | Permite que otros repliquen el juicio, no solo la tarea. |
| [ ] | **¿Se realizan pruebas de estrés o simulacros de falla en este flujo de decisión?** | La única forma de probar la estructura es someterla a carga. |

---

## DIAGNÓSTICO RÁPIDO

* **0-3 Respuestas "NO":** **Estructura Saludable.** Requiere mantenimiento y vigilancia, pero el diseño es robusto.
* **4-6 Respuestas "NO":** **Estructura Burocrática/Lenta.** El sistema funciona pero con alta fricción. Riesgo de parálisis ante crisis rápidas.
* **7+ Respuestas "NO":** **Falla Estructural Crítica.** Su organigrama **no representa la estructura real de decisión**.
    * Está centralizando decisiones donde no hay datos.
    * Está asignando culpas donde no hay autoridad.
    * **Acción:** Detener iniciativas nuevas y rediseñar la gobernanza inmediatamente.
