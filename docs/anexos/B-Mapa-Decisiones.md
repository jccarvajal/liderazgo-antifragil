# ANEXO B: MAPA DE DECISIONES NO DELEGABLES
### Guía de "Líneas Rojas" para la Automatización y Delegación

**Principio Rector:**
La eficiencia nunca debe estar por encima de la responsabilidad. Existen dominios donde la velocidad de una máquina o la obediencia ciega de un proceso son un riesgo, no una ventaja. Use este mapa para clasificar cualquier decisión antes de diseñar el sistema.

> **Nota:** Este mapa no surge de casos particulares, sino de la sistematización de patrones recurrentes observados en fallas de automatización, auditoría y gobernanza a nivel global.

---

## EL SEMÁFORO DE SOBERANÍA

> **Aviso de Diseño:** Este modelo no evalúa la competencia moral de las personas, sino los límites estructurales de cualquier sistema automatizado o jerárquico.

### 🔴 ZONA ROJA: SOBERANÍA HUMANA EXCLUSIVA
**Definición:** Decisiones irreversibles, éticas o que afectan derechos fundamentales.
**Protocolo:** Prohibido automatizar. Prohibido delegar sin supervisión directa (Nivel 1). Requiere firma manuscrita o digital de un humano responsable (Accountable).

| Tipo de Decisión | Por qué es Zona Roja | Ejemplo de "No Hacer" (Anti-Patrón) |
| :--- | :--- | :--- |
| **Integridad Física y Vida** | La máquina no entiende el valor de la vida, solo probabilidades. | Un algoritmo médico que deniega tratamiento automáticamente por "baja probabilidad de éxito" sin revisión de un doctor. |
| **Dignidad y Sustento** | Despedir o sancionar tiene impactos socioeconómicos severos e irreversibles para terceros. Requiere empatía y contexto. | Despidos masivos por email generados por un algoritmo de productividad (caso empresas Tech/Gig economy). |
| **Excepción Normativa** | La justicia requiere entender el "Espíritu de la Ley", no solo la letra. | Un sistema que rechaza una beca a un estudiante huérfano porque le faltó un papel irrelevante, sin posibilidad de apelación humana. |
| **Estrategia y Propósito** | Definir el "Para Qué" de la organización es un acto de voluntad, no de cálculo. | Pedirle a una IA que defina la Misión y Visión de la empresa. |
| **Gestión de Crisis (Kill Switch)** | Apagar el sistema cuando daña a la sociedad requiere coraje moral, no código. | Flash Crash bursátil donde los algoritmos siguieron vendiendo hasta destruir el valor, porque nadie tenía el "botón rojo". |

---

### 🟡 ZONA AMARILLA: HUMAN-IN-THE-LOOP (HITL)
**Definición:** Decisiones complejas, técnicas o de alto impacto financiero.
**Protocolo:** La máquina o el proceso *recomienda* y *prepara* los datos. El humano *valida* y *ejecuta*.

| Tipo de Decisión | Rol de la Máquina / Proceso | Rol del Humano (Soberano) |
| :--- | :--- | :--- |
| **Contratación de Talento** | Filtrar CVs por requisitos técnicos duros. | Entrevistar, evaluar cultura y decidir quién entra. (Evitar sesgo algorítmico). |
| **Inversiones Grandes** | Calcular ROI, riesgos y escenarios financieros. | Decidir si el riesgo es aceptable según la estrategia y el "apetito de riesgo". |
| **Auditoría y Compliance** | Detectar anomalías (patrones sospechosos). | Investigar si es fraude o un error honesto. Juzgar la intención (dolo vs. error). |
| **Diagnóstico Complejo** | Analizar imágenes o datos y sugerir probabilidades. | Integrar la sugerencia con el contexto del paciente/cliente y decidir el curso de acción. |

---

### 🟢 ZONA VERDE: DELEGACIÓN Y AUTOMATIZACIÓN TOTAL
**Definición:** Decisiones repetitivas, de bajo riesgo, reversibles y de alto volumen.
**Protocolo:** Automatización permitida (Human-out-of-the-Loop). Auditoría muestral periódica (Spot Checks).

* Asignación de turnos (basado en reglas claras).
* Reposición de inventario estándar.
* Aprobación de gastos menores (bajo un umbral definido).
* Respuestas a preguntas frecuentes (Chatbots de nivel 1).
* Procesamiento de transacciones rutinarias.

---

## LA PRUEBA DE ÁCIDO (THE LITMUS TEST)

Si tiene dudas sobre si una decisión cae en Zona Roja o Amarilla, hágase estas 3 preguntas. Si la respuesta es "SÍ" a cualquiera de ellas, **la decisión es humana**.

1.  **La Prueba de la Cárcel/Prensa:**
    *"Si esta decisión sale terriblemente mal, ¿necesito poder señalar a una persona específica que explique el 'por qué' ante un juez o ante la prensa?"*
    *(Si la respuesta es "fue el algoritmo", usted perderá el juicio/reputación).*

2.  **La Prueba de la Reversibilidad:**
    *"¿Es esta decisión irreversible o el costo de deshacerla es catastrófico?"*
    *(Ej: Cortar un servicio vital vs. enviar un correo equivocado).*

3.  **La Prueba del Contexto:**
    *"¿Existe alguna circunstancia rara, humana o emocional que, de saberse, cambiaría mi decisión, pero que no está en la base de datos?"*
    *(La máquina solo ve datos; el humano ve el mundo).*
    