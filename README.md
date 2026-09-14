# flowboost-skills-fundamentos

Base compartida de persuasión — va con TODAS las áreas

---

## Instalar (2 minutos)

Abre **Claude Code** y pégale esto tal cual:

```
Instálame las skills de Flowboost de este repo y guíame en la primera configuración:
https://github.com/<usuario-github>/flowboost-skills-fundamentos
```

Claude clona el repo, instala las skills y te va pidiendo lo que falte en tu ordenador.
No hace falta que sepas nada de terminal: te da los comandos ya escritos.



### Si lo prefieres a mano

```bash
git clone https://github.com/<usuario-github>/flowboost-skills-fundamentos.git
cd flowboost-skills-fundamentos
python3 instalar.py
```

Y después, en Claude: `guíame en la primera configuración`

---

## Qué hay aquí

| Skill | Qué hace |
|---|---|
| `fundamentos-copy` | Base compartida de persuasión de Flowboost — Ogilvy (principios destilados + los 16 checks reales O1-O16 extraídos del libro), Breakthrough Advertisin… |

Cada skill lleva un **`LEEME.md`** con lo que hay que tener en cuenta antes de usarla: qué
necesita, qué no puede hacer y dónde deja las cosas.

---

## Lo que vas a necesitar

| | Para qué |
|---|---|
| **rclone + el Drive de Flowboost** | de ahí salen el brief, el branding y las fotos; ahí se dejan los entregables |
| **Python 3** | ya viene en el Mac |


La primera configuración te la monta Claude paso a paso. Lo único que tiene que darte Dirección son
los accesos: el Google del Drive y, si llevas campañas, la cuenta de Meta.

**Nunca le des una contraseña o una clave por chat.** Si algo la necesita, la pones tú en tu
ordenador y Claude te dice dónde.

---

## Reglas de la casa que aplican aquí

- Todo el texto para clientes en **español de España** (tú/vosotros), nunca voseo.
- **No se inventa** nada: cifras, testimonios, fechas ni garantías. Lo que falte se marca `[FALTA]`.
- Los ficheros de un cliente van a `~/Desktop/CLIENTES/<cliente>/`.
- El **Drive del cliente es de solo lectura**, salvo los entregables en su subcarpeta.
- **Activar una campaña de Meta es siempre de Dirección.** Las skills las dejan en pausa.

---

*Generado desde el sistema de Flowboost. No se edita aquí: se edita en el origen y se regenera.*
