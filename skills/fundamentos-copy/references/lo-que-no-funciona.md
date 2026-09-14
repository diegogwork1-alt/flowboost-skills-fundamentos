# Lo que NO funciona en estáticos de Meta (para NO repetirlo)

> **Fuente, corregida el 11-09-2026.** Este fichero se escribió a partir de los dos informes B2B de
> 2026, que **ya no son doctrina** (son consulta: ordenan cosas contrarias a la casa y perdieron
> cifras al extraerse). Se ha **re-anclado al NotebookLM «Creativos Meta» de Dirección (80 fuentes)**, que
> confirma casi todo y añade lo que faltaba. Cada dato con impacto lleva su cifra.
>
> **Este fichero se ABRE en la fase de auditoría** (`calidad-y-autoqc.md §H.7`). Antes estaba en el
> índice y en ninguna fase: por eso nadie leía la parte de compliance, que es la que tumba cuentas.

---

## A. Errores que matan el rendimiento (aplican a TODO cliente)
1. **Foto de stock corporativa estéril** — gente sonriendo, apretón de manos, señalando una laptop, ejecutivos en mesa de cristal. **Reduce la conversión ~11%**: el cerebro la filtra como "publicidad" (ceguera de banner). → Usar **foto real** del avatar/contexto, con imperfección natural. (Los ganadores de Flowboost usan foto real, nunca stock obvio.)
2. **Exceso de texto (>20% de la superficie)** — Meta no lo rechaza directo pero **penaliza la entrega y sube el CPM**. → Máx 3 niveles de texto, <35 palabras en el canvas *(techo técnico; la doctrina de la casa ≤8 palabras manda — `reglas-tecnicas-y-copy.md §5`)*.
3. **Baja resolución / captura comprimida ilegible** — daña la puntuación de calidad de subasta y se abandona al instante.
4. **Optimizar la campaña para "Tráfico"** cuando buscás leads — Meta manda clics baratos y bots que jamás llenan el form. Es el peor error estratégico. (Ojo: es de configuración de campaña, pero mata el rendimiento del estático igual.)
5. **No rotar creativos** — colapsa el CTR por fatiga visual. Y **matar de golpe al ganador fatigado** reinicia el aprendizaje del algoritmo y encarece todo → usar efecto sustitución (bajar presupuesto al viejo, meter challengers al lado).
6. **Múltiples ideas / lista de 10 funciones en un solo canvas** — sobrecarga cognitiva, el usuario sigue scrolleando. Una sola idea por anuncio; máximo 3-5 puntos en una lista, nunca más de 5.
7. **Dos o más centros visuales compitiendo** (titular gigante + UI + diagrama + sellos a la vez) — dispersión atencional, abandono. Una sola fuerza gravitatoria.

## B. Copy que hunde la conversión
8. **Jerga vacía / eslóganes genéricos** — "transforma la eficiencia de tu negocio", "trabaja más inteligente", "impulsa tus sinergias". No dicen qué hace ni para quién. Sustituir por afirmación concreta.
9. **"AI tells"** — palabras como *delve, leverage, synergize, "optimiza tu experiencia"* → **−8% conversión**. Prohibidas.
10. **Superlativos sin respaldo** — *amazing, innovador, cutting-edge, revolucionario* → **−4%**.
11. **Más de 2 guiones largos (—) por cada 100 palabras** → **−5%**.
12. **Marca en la primera frase** — sube el scroll-past. La marca va discreta y al final; el hook va primero.
13. **Números redondos** (50%, 90%, "cientos de clientes") — se ignoran como marketing. Los **específicos/impares** ("74 leads", "cero okupas en 4 años", "+120 reformas") registran como dato real.
14. **Promesa de resultado/ROI sin fuente** ("ahorra 500%", "resultados garantizados") — rechazo por escepticismo **y** puede violar la política de Meta de reclamos engañosos.

## C. Políticas de Meta que provocan desaprobación (compliance obligatorio)
15. **Política de Atributos Personales — la causa #1 de desaprobación B2B.** Meta prohíbe **afirmar o insinuar** que conocés una característica/vulnerabilidad privada del lector con **2ª persona acusatoria**: "¿Estás cansado de que tu equipo no llegue a objetivos?", "¿Tu empresa corre riesgo de sanción?".
    - **Reencuadre seguro:** población/aspiracional o mecanismo → "Por qué los equipos de alto rendimiento están automatizando su prospección en 2026".
    - **Matiz Flowboost (lo que vi que SÍ pasa y convierte):** en B2C emocional, el hook de dolor en 2ª persona empático **puede** pasar y gana (MMS "¿Te atracas… y después te odias por ello?" → 74 leads @€2,92). La línea es: **dolor compartido/relatable ("el ciclo atracón-culpa")**, no **acusación de un fracaso o deficiencia** del lector. Tratar esto como **checkpoint de riesgo**, no como vía libre: si el hook acusa o asume una carencia privada, reformular.
16. **Incoherencia anuncio ↔ landing (bait-and-switch)** — si el titular, la oferta, el precio o la razón social de la landing no coinciden con el creativo, Meta lo marca como engañoso → sube el CPM o suspende. El estático y la landing deben decir lo mismo.
17. **Categoría especial no declarada** — vivienda/inmobiliaria, crédito/finanzas, empleo, temas sociales. No declararla cuando aplica = rechazo o baneo de cuenta. (Se ve en varios clientes de Flowboost: inmobiliaria, inversión.)
18. **IA generativa sin declarar (C2PA)** — si se generan/retocan fotos fotorrealistas de personas con IA, hay que declararlo en Ads Manager o Meta desaprueba y acumula penalizaciones.

## D. Estética que resta (parece barato / inmaduro)
19. **"AI slop" corporativo** — pieles plásticas, oficinas de cristal inverosímiles, sonrisas forzadas, interfaces/paneles con texto ininteligible generados por IA. Degrada la percepción de solidez.
20. **Prohibido usar IA para dibujar interfaces/UI, botones o paneles** — se ven falsos. Si hay que mostrar producto/UI (cliente B2B), sale de capturas reales vectorizadas.
21. **Metáfora de neón/candado 3D infantil ("cyber glow")**, figuras geométricas flotando en azul — comunica inmadurez.
22. **Maqueta 3D llamativa de ebook** — evoca infoproducto de consumo barato; usar presentación limpia.
23. **Degradados azul→violeta genéricos** — se funden con el wallpaper del feed, se ignoran.

## E. Prueba social débil (no perder espacio en esto)
24. **"Confían miles" / social proof sin cuantificar** — indistinguible de no tener prueba.
25. **Muro de logos de clientes** solo (+8%) y **logos de prensa "visto en…"** (+5%) — impacto modesto; los usuarios los leen como decoración. Muy por debajo del **testimonio individual real** (+14%) y el **recuento nombrado/segmentado** (+22%). Priorizar testimonio con cara+nombre+cifra.

## F. Testing que no sirve
26. **Variaciones cosméticas** (color del botón, mover el titular) — sin impacto en la subasta. No gastar presupuesto de test ahí. Testear concepto → ángulo → hook → formato (en ese orden de impacto).
27. **Mezclar estáticos y videos en el mismo conjunto de test** — el algoritmo desvía el presupuesto al formato que maximiza tiempo de reproducción (video) y ahoga al estático. Testear estáticos aislados.

---

## G. Qué del B2B SaaS de los informes se usa SOLO si el cliente es B2B (no forzar en B2C)
Estos formatos/recursos son válidos y potentes **para clientes B2B** de Flowboost, pero **no van en un cliente B2C local** (sería una fuga): capturas de dashboard/UI con micro-zoom y device frames, mapas de integración/ecosistema, diagramas de arquitectura, estética "terminal dark"/bloques de código, tarjetas de ROI/TEI y ahorro de Opex, sellos SOC2/ISO/G2/Gartner/Forrester, muros de logos corporativos, personas de comité (CFO/CISO/CIO/Procurement), CTAs de "descargar informe/whitepaper/demo comercial", y el encuadre estratégico 95-5 / disponibilidad mental (Flowboost hace respuesta directa a corto plazo). → El SKILL.md decide con la "Ruta B2C vs B2B" cuál set aplicar. Un cliente B2C (adicciones, cuidadoras, reformas, tatuaje, viajes, baile) usa los **4 formatos maestros** de `patrones-diseno-estaticos.md` *(paquete **creatividades**; si no lo tienes instalado, esta parte no aplica)*, no estos.

---

## H. LO QUE AÑADEN LAS FUENTES DE DIRECCIÓN (NotebookLM, 11-09-2026)

### H.1 · ⛔ ANTES/DESPUÉS EN SECTORES REGULADOS — esto nos toca de lleno
En **salud, estética, odontología, nutrición y fitness**, Meta **rechaza o restringe** los
antes/después. Nos afecta directo: **Cliente 03** (adicciones y salud emocional) y cualquier
cliente de bienestar. Condiciones para que pase:
- **Mismo encuadre, misma iluminación y misma distancia** en las dos fotos. Si cambian, se lee como
  transformación exagerada y cae.
- **Prohibido prometer resultado médico o curativo.** El «después» es un estado del avatar, no una
  cura.
- En esos sectores, **el formato 2 es el más arriesgado de los 9**: si hay duda, se elige otro.
- Y añadido de las fuentes: en salud y bienestar **el 77 % de los usuarios exige contenido revisado
  por un profesional**. Un testimonio sin respaldo pesa menos ahí que en cualquier otro sector.

### H.2 · COMPETIDORES: cómo se compara sin que te tumben (con la prueba)
Nombrar una marca rival o poner su logo **activa la revisión de marcas registradas** → rechazo o
reclamación. La forma segura, con evidencia de cuánto aguanta:
- **Comparar contra una columna genérica de dolor**: «Sin automatización», «Proceso manual».
  Zapier corrió un estático así **386 días** sin bloqueos.
- **Comparación de concepto de categoría** (sin acusar): Framer, *«Es como Figma pero te llevas una
  web de verdad»*, **479 días** activo. Es el filo: funciona, pero es la excepción, no la norma.
- **La norma de la casa sigue siendo: no se nombra a nadie.**

### H.3 · LO QUE SUBE EL CPM SIN LLEGAR A DESAPROBAR
Estas no rechazan el anuncio: lo encarecen, que a la larga es peor porque no se ve.
| Práctica | Qué provoca |
|---|---|
| **Exceso de texto sobre la imagen** | entrega reducida y **CPM más alto**. La regla dura del 20 % desapareció; **la penalización no** |
| **Creativo que no engancha en el primer segundo** | cae la puntuación de calidad → el algoritmo **compensa cobrando más CPM** |
| **Fatiga** (frecuencia 2,0-2,5 en frío + CTR −20 % sostenido 3 días) | **CPM +15-20 %** |
| **Urgencia falsa** («último día» en un anuncio que corre siempre) | la gente **reporta u oculta** → destroza la calidad y encarece la cuenta entera |
| **Hipersegmentación** (demasiados intereses, ubicaciones a mano) | público minúsculo → CPM innecesariamente alto |

### H.4 · ERRORES DE CREATIVO, con su caída medida
- **Foto de stock corporativo** (equipo sonriendo, apretón de manos) → **−11 %**.
- **Muletillas de IA** (delve, leverage, «optimiza tu experiencia») → **−8 %**.
- **>2 rayas largas por 100 palabras** → **−5 %**.
- **«Compra ahora» en venta considerada** → **−4 %** (demasiado transaccional).
- **Vídeo con autoplay de héroe** frente a imagen fija → **−7 %** (el retraso de carga lo arruina).
- **Gastar los primeros 3 s en el logo** → hunde el *hook rate*. El logo no es el gancho.
- **Captura completa de escritorio** en un anuncio móvil → texto microscópico a 375 px, ilegible.
- **El 85 % de los vídeos se ven SIN SONIDO** → lo que no esté en pantalla, no existe.

### H.5 · PRUEBA SOCIAL: lo que pesa y lo que no
| Recurso | Impacto |
|---|---|
| **Recuento de clientes del segmento** («lo usan 8 de las Fortune 50») | **+22 %** |
| **Testimonio con cara, nombre y cargo reales** | **+14 %** |
| Logos de prensa («visto en…») | **+5 %** — casi nada |
| **Cita anónima** («— J. S.») | no convierte. Y en la casa, además, **no es publicable** |

### H.6 · PROMESAS: qué se puede afirmar y qué no
- **SÍ:** métricas específicas, impares o con decimal, salidas de un caso real, **con su línea de
  fuente en pequeño** al pie.
- **NO:** cifras redondeadas o inventadas («mejora un 100 %»). Se descartan como propaganda **y**
  activan la política de reclamaciones engañosas — que es motivo de **desaprobación**, no solo de
  mal rendimiento.
- **El error clásico:** prometer algo gratis en el anuncio y pedir datos de pago al registrarse.
  Dispara el rebote.

### H.7 · FORMULARIO NATIVO vs LANDING — el dato que cambia la discusión
No es creativo, pero decide el resultado de la pieza y no estaba escrito en ningún sitio:
- **Formulario nativo:** **+40-55 % de volumen** de leads y **CPL un 30-45 % más barato**… pero su
  conversión a lead cualificado es **entre un 35 % y un 55 % MENOR**. Sin fricción entran curiosos.
- **Landing:** CPL más caro, pero **medido por coste por lead cualificado gana por un 20-35 %** en
  tickets altos.
- **Y si es landing:** cada campo del formulario por encima de 4 **parte por la mitad** la conversión
  (1 campo → **12,4 %**; 6 o más → **3,1 %**), y **si tarda más de 2 s en cargar** se desploma.
  → Esto es de `landing-*` y `armar-campana-meta`, y se apunta aquí para que no se pierda.
