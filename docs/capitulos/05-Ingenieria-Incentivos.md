# CAPÍTULO 5: INGENIERÍA DE INCENTIVOS
### Por qué la cultura se come a la estrategia (y el bono se come a la ética).

> **Axioma de Comportamiento:**
> La gente no hace lo que la organización *predica* (Valores, Misión, Posters).
> La gente hace aquello por lo que la organización *paga* (Bonos, Promociones, Estatus).
>
> Si existe una discrepancia entre el discurso ético y el incentivo financiero, el incentivo ganará el 100% de las veces.
> **No intente cambiar la cultura con charlas motivacionales. Cambie la estructura de recompensas.**

Diseñar una organización distribuida (Capítulo 4) sin corregir los incentivos es un suicidio arquitectónico. Si usted le da autonomía a un agente cuyos intereses personales chocan con los de la organización, no está creando agilidad; está financiando el sabotaje.

Los incentivos son el **Código Fuente** del comportamiento humano.

En gestión de riesgos, la mayoría de los desastres no ocurren por "maldad"; ocurren por **incentivos perversos**. Personas racionales siguiendo la lógica del sistema hasta el precipicio.

---

## 5.1. La Ley de la Cobra (El Efecto de los Incentivos Perversos)

El ejemplo clásico de la gestión fallida: El gobierno colonial británico en India quería reducir la población de cobras. Ofreció una recompensa por cada piel de cobra entregada.
¿El resultado? La gente comenzó a criar cobras en sus casas para matarlas y cobrar. Cuando el gobierno se dio cuenta y canceló el programa, los criadores soltaron las cobras inútiles a la calle.
Resultado final: **Más cobras que al principio.**

En la empresa moderna, criamos cobras todos los días:

* Si paga a los desarrolladores por "cantidad de bugs corregidos", escribirán código con errores para luego arreglarlos y cobrar.
* Si paga a Ventas solo por "volumen de cierre" sin penalizar el riesgo legal, traerán contratos tóxicos que explotarán en 2 años.
* Si mide a Ciberseguridad por "vulnerabilidades reportadas", bombardearán a TI con falsos positivos irrelevantes.

La Ley de Goodhart se activa: **"Cuando una métrica se convierte en el objetivo, deja de ser una buena métrica".**
Un sistema de incentivos lineal en un entorno complejo siempre genera efectos secundarios no deseados.

---

## 5.2. El Problema de Agencia y la Asimetría

El defecto crítico en la estructura corporativa es la **Asimetría de Riesgo**.

Ocurre cuando el agente (empleado/directivo) tiene toda la ganancia potencial (*Upside*) si las cosas salen bien, pero transfiere toda la pérdida potencial (*Downside*) a la organización si salen mal.

Esto genera el **Comportamiento de Apuesta Gratuita**:

El VP de Ventas cierra un trato agresivo saltándose los controles de cumplimiento.

* **Escenario A (Sale bien):** El VP cobra su bono anual y es ascendido.
* **Escenario B (Sale mal):** La empresa recibe una multa millonaria regulatoria tres años después. El VP ya no está en ese puesto, o la multa la paga la "caja de la empresa", no su bolsillo.

Mientras exista esta asimetría, la gestión de riesgos es una ficción.
Ningún manual de ética puede competir contra un bono de desempeño mal diseñado. El directivo racional tomará el riesgo porque la ganancia es privada y la pérdida es socializada.

---

## 5.3. Skin in the Game (Jugarse la Piel)

La única forma de corregir la asimetría no es con más vigilancia (burocracia), sino con **Alineación de Destino**.
El principio de *Skin in the Game* (Jugarse la Piel) debe ser la base de la remuneración ejecutiva y operativa en un sistema antifrágil.

Si usted toma decisiones de riesgo, debe participar en las consecuencias de ese riesgo.
No se trata de crueldad; se trata de física. Un puente diseñado por un ingeniero que debe vivir debajo de él es un puente que no se cae.

> **⚠️ Cláusula Operativa y Legal (Límite del Incentivo):**
> 
> Los mecanismos de castigo (*Malus/Clawback*) se aplican **exclusivamente sobre la remuneración variable** (bonos, comisiones, *stock options*). El sueldo base es un derecho laboral inalienable y no debe ser tocado. Usted no puede "multar" el salario de un empleado; solo puede retener o cancelar el bono que aún no se ha consolidado.

**Mecanismos de Corrección:**

1.  **Clawbacks (Recuperación Contractual):** Los bonos por desempeño no se "ganan" irrevocablemente el día del cierre. Se añade una cláusula que permite a la empresa recuperar el dinero si se descubre fraude o negligencia grave posterior.
2.  **Vesting (Maduración) a Largo Plazo con Retención:** El incentivo variable se deposita en una cuenta de garantía (*Escrow*) y se libera en ciclos largos (3-5 años). Esto asegura que la decisión generó valor real, no solo un pico trimestral ficticio.
3. **Dogfooding (Consumo Obligatorio):** Quien diseña o aprueba un sistema debe estar obligado a usarlo diariamente. Si el Gerente de Operaciones compra un software que es lento o burocrático, él debe ser el primero en sufrir esa lentitud. Si duele usarlo, se arreglará rápido.
4. **Cuarentena de Ascenso:** Se prohíbe transferir o ascender al líder de un proyecto hasta que su implementación lleve 6 meses operando sin fallas. Nadie puede cobrar el bono por "lanzar" y huir antes de que el sistema explote.

---

## 5.4. El Peligro del Incentivo Individual en Redes Colaborativas

El último error común es incentivar al "Héroe Solitario" en una estructura que requiere colaboración en red.
Si su modelo operativo (Cap 4) pide orquestación y flujo, pero su modelo de compensación es un ranking individual forzado (*Stack Ranking*), usted ha diseñado una guerra civil interna.

En sistemas complejos, el resultado rara vez es atribuible a una sola persona. Si incentiva la competencia individual, destruye el flujo de información. Nadie comparte un hallazgo de error si ocultarlo le da ventaja en la evaluación de desempeño.

**El incentivo debe moverse del individuo al equipo y del volumen (*output*) al impacto real en la salud del sistema (*outcome*).**

Pero existe un daño colateral aún más grave: la **Corrupción de la Información**.

Un incentivo mal diseñado no solo genera malas decisiones; ensucia la señal. Si el sistema castiga la verdad o premia el maquillaje de cifras, usted pierde la visibilidad real. Y cuando la señal de entrada está corrompida por el bono, ningún sistema de control posterior puede salvar la operación.

---

## Veredicto: Auditoría de la Codicia Racional

Cierre este capítulo auditando su nómina, no sus valores.

Tome las tres peores conductas que observa en su organización hoy (silos, ocultamiento de errores, cortoplacismo) y pregúntese:

**¿De qué manera el sistema de bonos y promociones está pagando actualmente por este comportamiento?**

Casi siempre descubrirá que la organización está obteniendo exactamente aquello por lo que está pagando.
Si quiere cambiar el comportamiento, deje de exigir lealtad.

**Cambie la ecuación de pago. Alinee el riesgo. Ponga piel en juego.**
