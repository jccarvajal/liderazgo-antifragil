# Anexo G: Checklist de Auditoría de Liderazgo Antifrágil
## Herramienta de Diagnóstico Estructural

!!! info "Ficha Técnica del Instrumento"
    **Propósito:** Evaluar si el "liderazgo" es una propiedad emergente del sistema o una dependencia frágil de individuos clave.

    **Uso:** Directivo / Auditoría Interna / Arquitectura Organizacional.

    **Criterio:** Marque **Sí** / **No**. Los "Parciales" se computan automáticamente como **No** (un sistema intermitente es un sistema fallido).

---

### 1. Arquitectura de Decisión

- [ ] **Propiedad Nominal:** Las decisiones operativas tienen un dueño explícito con nombre y apellido (no "consenso difuso" ni comités).
- [ ] **Fronteras (Boundaries):** Existe una distinción formal y documentada entre decisiones delegables y no delegables.
- [ ] **Excepción:** La escalada jerárquica es un mecanismo de excepción, no el flujo normal de trabajo.
- [ ] **Autonomía:** Las decisiones críticas dentro de los límites predefinidos pueden ejecutarse sin esperar la aprobación del "jefe correcto".
- [ ] **Latencia:** El tiempo de decisión está definido y es medible (SLA de Decisión).

!!! failure "Alerta Antifrágil: SPOF Humano"
    Si la organización entra en pausa operativa porque alguien específico está de vacaciones, no tiene un equipo: tiene un **Punto Único de Fallo**.

---

### 2. Responsabilidad y Skin in the Game

- [ ] **Consecuencia:** Quien tiene la autoridad para decidir, asume consecuencias reales por el resultado (no simbólicas).
- [ ] **Veto:** No existen roles con poder de veto que no tengan responsabilidad directa sobre la pérdida de oportunidad.
- [ ] **Trazabilidad:** Los errores son trazables a decisiones específicas de personas, no se diluyen en reportes genéricos.
- [ ] **Costo:** El "aprendizaje" incluye un coste visible y asumido, no solo retrospectivas narrativas.

!!! failure "Alerta Antifrágil: Riesgo Sistémico"
    Autoridad sin costo = Riesgo Sistémico. Responsabilidad sin autoridad = Negligencia de Diseño.

---

### 3. Incentivos y Métricas

- [ ] **Fricción:** Las métricas no castigan la toma de decisiones difíciles (riesgo controlado).
- [ ] **Inacción:** El sistema no premia la inacción "segura" por encima de la acción responsable.
- [ ] **Teatro:** Los KPIs miden impacto real de negocio y no "Teatro de Cumplimiento" (reuniones, horas, correos).
- [ ] **Coherencia:** Existe alineación total entre lo que la estrategia declara y lo que el bono anual recompensa.
- [ ] **Kill Switch:** Las métricas se desactivan o revisan inmediatamente si se demuestra que generan incentivos perversos.

!!! failure "Alerta Antifrágil: Parálisis por KPI"
    Si nadie decide por miedo a "cómo se va a ver el número" a fin de mes, el sistema de incentivos es la amenaza, no el mercado.

---

### 4. Gestión del Error

- [ ] **Telemetría:** El error se trata como dato (información del sistema), no como falla moral.
- [ ] **Alerta Temprana:** Existen mecanismos seguros para exponer errores o riesgos antes de que exploten.
- [ ] **Sin Heroísmo:** No se requiere valentía personal para reportar problemas reales; es el procedimiento estándar.
- [ ] **Cambio Estructural:** Las lecciones aprendidas se traducen en cambios de procesos/reglas, no en discursos motivacionales.
- [ ] **Rediseño:** Los errores repetidos activan automáticamente una revisión de arquitectura, no un aumento de supervisión manual.

!!! failure "Alerta Antifrágil: Espiral de Control"
    Responder al error humano agregando más controles manuales solo incrementa la fragilidad y la burocracia.

---

### 5. Dependencia de Héroes

- [ ] **Operación Estándar:** La operación diaria (BAU) no depende de la intervención de individuos extraordinarios.
- [ ] **Falla de Diseño:** Los "imprescindibles" son tratados como riesgos operativos a mitigar, no como activos culturales a celebrar.
- [ ] **Continuidad:** La salida abrupta de una persona clave no paraliza la toma de decisiones críticas (Factor de Bus).
- [ ] **Código:** El conocimiento está codificado en el sistema, no retenido informalmente en la memoria de los veteranos.
- [ ] **Evolución:** La organización puede mejorar sus procesos sin esperar a que alguien "salve el día".

!!! failure "Alerta Antifrágil: Deuda Técnica"
    El heroísmo recurrente es la evidencia de una arquitectura defectuosa.

---

### Evaluación Global

**Sume la cantidad de ítems NO cumplidos (casillas vacías):**

* **0 – 2 Fallos:** ✅ **Sistema Funcional.** Capacidad antifrágil operativa.
* **3 – 5 Fallos:** ⚠️ **Fragilidad Latente.** Rediseño de arquitectura recomendado.
* **6+ Fallos:** ⛔ **Riesgo Estructural Severo.** El liderazgo es un mito narrativo; la operación es puramente inercial.

> *Nota Doctrinal: Cuando el sistema necesita líderes excepcionales para sobrevivir, el problema no es humano: es arquitectónico.*
