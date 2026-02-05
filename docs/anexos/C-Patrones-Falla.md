# ANEXO C: CATÁLOGO DE PATRONES DE FALLA ORGANIZACIONAL
### Diagnóstico Clínico de Patologías Comunes (Anti-Patrones)

**Instrucciones de Uso:**
Use este catálogo para identificar la enfermedad raíz detrás de los síntomas visibles. No trate el síntoma (ej: despedir gente); trate el diseño defectuoso que lo provoca.

> **Nota:** Los siguientes anti-patrones describen fallas de diseño organizacional ampliamente documentadas en literatura de gestión, ingeniería de sistemas y gobernanza, independientemente del sector o país.

---

## 1. EL CULTO AL HÉROE (Dependencia Crítica de Punto Único de Fallo – SPOF)
**Descripción:** La organización depende sistemáticamente de individuos que trabajan horas extras excesivas o saltan procedimientos para "salvar el día".

* **Síntoma Visible:** Se premia y aplaude públicamente al que se queda hasta las 3 AM arreglando un problema. "Sin Juan, esto se cae".
* **Diagnóstico Técnico:** **Dependencia de Punto Único de Fallo (SPOF).** Fragilidad estructural extrema. Incentivos perversos hacia la corrección reactiva en lugar de la prevención.
* **Causa Raíz:** Falta de procesos robustos y redundancia. Glorificación del esfuerzo visible sobre la eficacia invisible.
* **Corrección GRC:**
    1.  Eliminar la dependencia estructural del "heroísmo" recurrente. Si alguien debe salvar el día, el proceso falló.
    2.  Implementar bonos por "Transferencia de Conocimiento" (hacerse prescindible).
    3.  Documentación obligatoria.

---

## 2. LA CÁMARA DE ECO (Falta de Redundancia Cognitiva / Groupthink)
**Descripción:** Un equipo directivo donde nunca hay desacuerdo y todas las ideas del líder son aprobadas de inmediato.

* **Síntoma Visible:** Reuniones rápidas, "armonía artificial", nadie hace preguntas difíciles. Los proyectos fallan por obviedades que nadie mencionó.
* **Diagnóstico Técnico:** **Falta de Redundancia Cognitiva / Groupthink.** El sistema de sensores está apagado. Alta probabilidad de ceguera estratégica.
* **Causa Raíz:** Selección de personal basada en afinidad/lealtad (amiguismo) y castigo sutil a la disidencia.
* **Corrección GRC:**
    1.  Institucionalizar la "Regla del Décimo Hombre" (Cap 8).
    2.  Designar un *Red Team* rotativo.
    3.  Diversificar el comité de decisión.

---

## 3. TEATRO DEL CUMPLIMIENTO (Desacople Normativo / Compliance Theater)
**Descripción:** La organización genera toneladas de papel y evidencia para auditores, pero la operación real funciona por caminos informales inseguros.

* **Síntoma Visible:** Manuales perfectos que nadie lee. "Firma aquí para cumplir". Procedimientos tan rígidos que la gente los "hackea" para poder trabajar.
* **Diagnóstico Técnico:** **Desacople Normativo.** La fricción burocrática es tan alta que incentiva la creación de una "Shadow IT" u "Organización en la Sombra".
* **Causa Raíz:** Diseño de controles hecho por abogados/burócratas desconectados de la realidad operativa (Trinchera).
* **Corrección GRC:**
    1.  Auditoría de Procesos: Eliminar cualquier control que no mitigue un riesgo real.
    2.  Diseño Centrado en el Usuario (operadores reales, no supuestos): Si es difícil de cumplir, será evadido.

---

## 4. GESTIÓN POR TERROR (Interferencia Sistemática del Canal de Información)
**Descripción:** Modelo de liderazgo que introduce ruido sistemático en la comunicación mediante intimidación o inestabilidad.

* **Síntoma Visible:** Silencio sepulcral en reuniones. Rotación alta de talento. Reportes "todo en verde" (falsos) porque nadie se atreve a dar malas noticias.
* **Diagnóstico Técnico:** **Interferencia de Señal (Signal Jamming).** El miedo introduce ruido en el canal de comunicación. El líder pierde telemetría real de la operación.
* **Causa Raíz:** Inseguridad del diseño de mando y falta de métricas objetivas.
* **Corrección GRC:**
    1.  Implementar canales de denuncia anónima reales.
    2.  Evaluar al líder por la tasa de retención de talento y clima (Safety Check).
    3.  Remover al "nodo tóxico" si no cambia.

---

## 5. SELECCIÓN ADVERSA (Degradación Sistémica del Capital Cognitivo)
**Descripción:** Los empleados competentes y con opciones de mercado se van; se quedan los que no tienen opciones o los leales políticamente.

* **Síntoma Visible:** Degradación progresiva de la calidad técnica. Ascensos basados en antigüedad o política, no mérito.
* **Diagnóstico Técnico:** **Drenaje de Capital Cognitivo.** La organización está expulsando activamente a sus mejores activos. Inversión de la curva de talento.
* **Causa Raíz:** Fallas de diseño en la propuesta de valor al empleado y falta de meritocracia técnica.
* **Corrección GRC:**
    1.  Cambiar la moneda de estatus: premiar la competencia técnica explícitamente.
    2.  Entrevistas de salida obligatorias y analizadas por un tercero neutral.

---

## 6. EL ALGORITMO OPACO (Pérdida de Soberanía / Black Box Abdication)
**Descripción:** Decisiones críticas se delegan a herramientas de software o IA sin entender cómo funcionan.

* **Síntoma Visible:** "El sistema lo rechazó y no sé por qué". "La IA dice que invirtamos aquí". Nadie puede explicar la lógica detrás de una decisión.
* **Diagnóstico Técnico:** **Pérdida de Soberanía del Juicio.** Riesgo legal y ético incontrolable. Vulnerabilidad ante sesgos algorítmicos.
* **Causa Raíz:** Fascinación tecnológica (solucionismo) o pereza intelectual para asumir la responsabilidad.
* **Corrección GRC:**
    1.  Aplicar el Mapa de Decisiones No Delegables (Anexo B).
    2.  Exigir "Explicabilidad" a todo proveedor de software.

---

## 7. EL SILO FORTIFICADO (Fragmentación de la Verdad / Data Hoarding)
**Descripción:** Departamentos que no comparten información con otros para mantener cuotas de poder.

* **Síntoma Visible:** "Esa es mi data". TI no habla con Negocio. Legal no habla con Operaciones. Duplicidad de esfuerzos.
* **Diagnóstico Técnico:** **Fragmentación de la Verdad.** Imposibilidad de tener una visión holística del riesgo. Esto impide la gestión integrada de riesgos y genera puntos ciegos sistémicos.
* **Causa Raíz:** Incentivos de competencia interna (suma cero) en lugar de colaboración.
* **Corrección GRC:**
    1.  Unificar la data en una fuente única de verdad.
    2.  Cambiar incentivos: bonos grupales/corporativos, no solo departamentales.
    