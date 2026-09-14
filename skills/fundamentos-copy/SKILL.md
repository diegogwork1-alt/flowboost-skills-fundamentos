---
name: fundamentos-copy
description: Base compartida de persuasión de Flowboost — Ogilvy (principios destilados + los 16 checks reales O1-O16 extraídos del libro), Breakthrough Advertising de Schwartz (niveles de consciencia y sofisticación de mercado), el playbook de titulares, y el panel de expertos (Ogilvy + Schwartz + Halbert + Sutherland de disidente) que puntúa cualquier pieza antes de aprobarla. NO produce nada por sí sola: la leen las skills de estáticos, copy de anuncios, guiones, VSL y landings. Es el paquete que va con TODAS las áreas. Usar cuando haya que redactar o auditar cualquier texto persuasivo, o cuando otra skill apunte aquí.
---

# Fundamentos de copy y persuasión (base compartida)

Esto **no es una skill que se invoque sola**: es la capa que leen las demás. Vivía repartida dentro de
`estaticos-meta` y `auditar-guiones-egc` por accidente histórico, y eso rompía cualquier intento de
repartir las skills por áreas —el maquetador de landings necesitaba tener instalada la skill de
estáticos solo para poder leer a Ogilvy—. Se extrajo el **10-09-2026**.

## Qué hay aquí

| Fichero | Qué es | Cuándo se lee |
|---|---|---|
| `references/ogilvy-principios.md` | Resumen destilado, útil para **REDACTAR** | Al escribir cualquier copy |
| `references/ogilvy-reglas-reales.md` | **16 checks O1-O16** con severidad, extraídos del libro (cap. 2 y 7) | Al **AUDITAR**. **Ante cualquier contradicción con el resumen, manda este** |
| `references/ogilvy-on-advertising.pdf` | El libro. **Una sola copia para todo el agente** | Solo para una **cita literal**; abrir con `pages`, nunca entero |
| `references/breakthrough-schwartz.md` | Niveles de consciencia y **sofisticación de mercado** | Al decidir **por dónde entra** el mensaje (hook, hero, ángulo) |
| `references/breakthrough-advertising.pdf` | El libro de Schwartz | Cita literal, con `pages` |
| `references/headlines-playbook.md` | Patrones de titular que rinden | Al escribir titulares |
| `references/lo-que-no-funciona.md` | **Anti-patrones y compliance de Meta** (A-G): lo que hunde el rendimiento, el copy que no convierte, las políticas que provocan desaprobación | Antes de dar por buena cualquier pieza |
| `references/panel-expertos.md` | **Ogilvy + Schwartz + Halbert + Sutherland de disidente** | **Compuerta antes de aprobar** una pieza: todas ≥7 y media ≥8 |

## Reglas de esta base

1. **Una sola copia de cada cosa.** Hasta el 10-09-2026 había **cuatro** `references/ogilvy-principios.md` en el
   agente, con contenido divergente (la de `landing-b2b-copy-html` había perdido el bloque *Voice of
   Customer*). Si vuelve a aparecer una copia dentro de otra skill, se borra y se apunta aquí.
2. **Resumen para redactar, reglas reales para auditar.** Si `references/ogilvy-principios.md` dice algo distinto
   de `references/ogilvy-reglas-reales.md`, **ganan las reglas reales**: están extraídas del libro, no de memoria.
3. **Los PDFs no se leen enteros.** Son 18,5 MB entre los dos. Se abren con `pages` para la cita exacta.
4. **Fechas y años SIEMPRE del reloj del sistema** (`date +%d/%m/%Y`, `date +%Y`), nunca de memoria.
   Una fecha pasada o un año viejo en una pieza = reescribir: una landing o un anuncio viven meses.
5. **El panel es compuerta, no opinión.** Aprobado solo con **todas las notas ≥7 y media ≥8**. La nota
   se anota en el fichero de specs de la pieza.

## Cómo se apunta aquí desde otra skill

Siempre en relativo desde la carpeta de skills, porque todas se instalan al mismo nivel:

```
../fundamentos-copy/references/<fichero>          # desde la raíz de una skill
../../fundamentos-copy/references/<fichero>       # desde references/ o una subcarpeta
```

**Si trabajás con una skill de un área y estos ficheros no existen**, falta instalar este paquete:
`npx skills add <repo-de-fundamentos>`. **No sigas sin ellos y no los reconstruyas de memoria** —
el copy saldría sin las reglas de Ogilvy y sin el nivel de consciencia de Schwartz, y no se nota
hasta que el anuncio no convierte.
