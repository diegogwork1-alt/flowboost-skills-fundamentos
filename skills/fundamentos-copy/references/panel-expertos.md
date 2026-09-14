# Panel de expertos con nota — la compuerta numérica final

Adaptado de `marketing-council` + `copy-editing` del repo marketingskills (decisión de Dirección, 06-09-2026). Se aplica como **última pasada** sobre guiones EGC, VSL y estáticos, DESPUÉS de los checks mecánicos y del juicio con cita.

## Cómo funciona
1. **Sentar 3-4 perspectivas + UN DISIDENTE obligatorio.** *"Un consejo que está de acuerdo es un espejo, no un consejo."*
   - Copy de anuncio / guion EGC: **Ogilvy + Schwartz + Halbert**, disidente **Sutherland** (probar lo ilógico).
   - VSL / oferta: **Hormozi + Schwartz**, disidente **Ogilvy** (la promesa sin prueba no vende).
2. Cada perspectiva **puntúa 1-10 su área** y da un **juicio con cita**: la **frase o el elemento concreto de la pieza, citado literal**, + **qué cambiar**. Ese es el único formato válido de crítica aquí — *«el titular "Invierte sin gestionar" no dice a quién habla → añadir el segmento»*, no *«el titular es flojo»*. Prohibido el "consejo con sabor a nombre": si la opinión sobrevive cambiándole el nombre, no es una opinión.
3. Se corrige empezando por la peor nota y se repite. **Umbral de aprobación: todas ≥7 y media ≥8.** Por debajo, no sale.

   > ### ⚠️ QUIÉN PUNTÚA, Y QUÉ SEPARA UN 7 DE UN 8 (11-09-2026)
   > **Puntúa el mismo agente que produjo la pieza. Es autoevaluación, y hay que decirlo** — no había
   > ningún árbitro externo escrito y por omisión quedaba así. Dos consecuencias prácticas:
   > - **Se puntúa leyendo la pieza terminada, no el plan.** Nada de juzgar por lo que pediste: eso es
   >   corregir el examen con el enunciado.
   > - **Ante la duda, la nota baja.** El sesgo de quien ha hecho la pieza va siempre hacia arriba, así
   >   que el empate se resuelve a la baja. Si dudas entre 7 y 8, es un 7.
   >
   > **La escala, para que el umbral signifique algo** (un ≥7 sobre una escala sin calibrar no es una
   > compuerta, es una impresión):
   >
   > | Nota | Qué significa en esa silla |
   > |---|---|
   > | **9-10** | No sabrías qué tocar. Lo defenderías delante del cliente tal cual |
   > | **8** | Correcto y sin peros. Lo que se toque es preferencia, no defecto |
   > | **7** | Aprobado justo: cumple, pero **sabes nombrar qué le falta** |
   > | **5-6** | Hay un defecto concreto que se puede escribir en una frase → **se corrige** |
   > | **1-4** | El defecto es de concepto, no de ejecución → **se rehace**, no se retoca |
   >
   > **Una nota sin la frase citada + qué cambiar no vale y no cuenta** (punto 2). Un «8» a secas es un
   > número inventado.
   >
   > **Tope de iteraciones: 3-4 pasadas**, el mismo que el auto-QC. «Se repite» no es un tope: si tras
   > la cuarta sigue por debajo, **se guarda el mejor intento, se marca con `_PEND` y se anota el motivo
   > en el specs**. No se itera indefinidamente ni se aprueba por cansancio.
4. **Mapa de desacuerdos**: si dos perspectivas chocan, nombrar el conflicto y **qué evidencia lo resolvería** (normalmente: los ganadores reales — `../../auditar-guiones-egc/references/ganadores/` para guiones, y `../../estaticos-meta/references/estaticos-ganadores.md` + `refs/` para estáticos. *La ruta `ganadores/` a secas no resolvía desde ninguna skill.*). No se promedia el desacuerdo: se decide con el dato.

## Preguntas firma (la rúbrica de cada silla)
**Ogilvy** — ¿El titular/gancho promete un beneficio y pararía a tu vecino? ¿Cada afirmación lleva su hecho o cifra? ¿Qué haría aquí un vendedor de respuesta directa y cómo mediremos si vendió?
**Schwartz** — ¿En qué **estado de consciencia** está este espectador y el gancho le llega exactamente ahí? ¿Cuántas veces ha oído ya esta promesa este mercado — hace falta mecanismo nuevo? ¿Está escrito con las palabras del mercado o desde nuestra cabeza?
**Halbert** — ¿Cuál es el **grabber**: por qué pararía alguien en los 3 primeros segundos? ¿La primera frase obliga a leer la segunda?
**Hormozi** — ¿Qué variable de la ecuación de valor está más floja: resultado, certeza, tiempo o esfuerzo? ¿La oferta lleva motivo?
 *Punto ciego documentado de Hormozi: el maximalismo de oferta (pilas de bonus, urgencia) suena a teletienda en marca, enterprise y lujo. El disidente lo vigila.*
**Sutherland (disidente)** — ¿Qué versión ilógica de esto funcionaría mejor? ¿Estamos optimizando lo que es fácil de medir en vez de lo que mueve al humano?

## Dos compuertas mecánicas que acompañan al panel
- **Test "Ahora puedes…"**: antepónlo a cualquier titular o bullet. Si el resultado es convincente Y verdadero, vale; si sale vago, obvio o exagerado, se reescribe. ("Plataforma potente de análisis" → falla. "Ve qué empresas visitan tu web" → pasa.)
- **Barrido "¿y qué?" (de Seven Sweeps)**: por cada afirmación, preguntar "¿y qué?" hasta que aparezca el beneficio para el espectador. La afirmación que no lo aguanta, fuera. Y el barrido de **especificidad**: "ahorra tiempo" → "ahorra 4 horas a la semana"; "muchos clientes" → la cifra real del brief.

## Reglas de honestidad del panel
- Las notas se dan a la PIEZA, no al esfuerzo. Un 5-6 = "funciona pero con huecos claros"; no se maquilla.
- Nada de citas inventadas ni de atribuir opiniones sobre este cliente concreto a las personas reales: son lentes de criterio, no personas opinando.
- **El panel llega EL ÚLTIMO, con la auditoría propia de cada skill ya pasada.** Qué es esa auditoría depende de quién llame:
  - `estaticos-meta` → **§0 (juicio de DC) + §G (checklist visual)** de su `calidad-y-autoqc.md`. **No tiene checks «V»**: esos son de la otra skill, y exigírselos aquí era pedirle una precondición que no existe.
  - `variaciones-estaticos-meta` → lo mismo **más los checks V-1 a V-5** (son cinco, no seis).
  - Guiones y VSL → su propia auditoría.
