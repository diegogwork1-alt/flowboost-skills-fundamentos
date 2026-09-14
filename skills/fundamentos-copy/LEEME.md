# LEEME — `fundamentos-copy`

> Paquete **fundamentos**. Esto es lo que hay que tener en cuenta **antes** de usar la skill.
> Las instrucciones de trabajo están en `SKILL.md`; esto son las condiciones y los límites.

## Qué hace

Base compartida de persuasión de Flowboost — Ogilvy (principios destilados + los 16 checks reales O1-O16 extraídos del libro), Breakthrough Advertising de Schwartz (niveles de consciencia y sofisticación de mercado), el playbook de titulares, y el panel de expertos (Ogilvy + Schwartz + Halbert + Sutherland de disidente) que puntúa cualquier pieza antes de aprobarla. NO produce nada por sí sola: la leen las skills de estáticos, copy de anuncios, guiones, VSL y landings.

**Qué NO hace:** NO produce nada por sí sola: la leen las skills de estáticos, copy de anuncios, guiones, VSL y landings.

## Antes de empezar necesitás

- La skill **`auditar-guiones-egc`** (paquete *guiones*): lee ficheros suyos.
- La skill **`estaticos-meta`** (paquete *creatividades*): lee ficheros suyos.

## Lo que NO se puede hacer

- ⛔ Duplicar estos ficheros dentro de otra skill. Hasta el 10-09-2026 había cuatro copias divergentes de `ogilvy-principios.md`; si aparece otra, se borra y se apunta aquí.
- ⛔ Leer los PDFs enteros: son 18,5 MB. Se abren con `pages` para la cita exacta.

## Ojo con esto

- **No se invoca sola**: la leen las skills de estáticos, copy, guiones, VSL y landings.
- Resumen para REDACTAR, `ogilvy-reglas-reales.md` para AUDITAR. Si chocan, ganan las reglas reales.

## Accesos que toca

Google Drive del cliente (solo lectura salvo entregables), n8n, Tally (formulario).

## Reglas de la casa (valen para todas las skills)

- **Todo el texto para clientes en español de España** (tú/vosotros). Nunca voseo ni LATAM.
- **No se inventa nada**: cifras, testimonios, fechas, garantías o casos. Lo que falte se marca `[FALTA]` y se pide.
- **Las fechas salen del reloj del sistema** (`date +%d/%m/%Y`), nunca de memoria.
- **Los ficheros de un cliente van a `~/Desktop/CLIENTES/<cliente>/`**, nunca sueltos en Descargas.
- **El Drive del cliente es de SOLO LECTURA**, salvo los entregables en su subcarpeta correcta. No se mueve, borra ni renombra nada.
- **Nunca se sube un `.md` crudo al Drive del cliente**: se convierte a Google Doc.
- **Nunca se teclean contraseñas, claves de API ni tokens**, aunque te los den. Los pone Dirección.
- **Para avisar a Dirección se usa `avisar.py`** (`--nivel urgente|aviso|info`), no un mensaje suelto que nadie lee.

---

*Generado el 10-09-2026 desde el sistema de Flowboost. Se regenera con `gen_leeme.py`; no editar a mano.*
