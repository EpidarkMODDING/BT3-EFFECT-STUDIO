# BT3 Effect Studio v0.19 (archivo único)

Todo el programa está en `bt3_effect_studio.py`: interfaz en tema oscuro, núcleo de `.pak`,
texturas PS2, idiomas, `recursos.dat` (sigue cifrado) e ícono, todo incrustado.

- Ejecutar: `python bt3_effect_studio.py`
- Compilar: sube el repo a GitHub → pestaña **Actions** → *Build BT3 Effect Studio* → descarga el `.exe`
  en *Artifacts*. Con un tag `v0.19` además se publica en *Releases*.
- Las carpetas opcionales (`modelos/`, `extras/`, `cenas/`, `auras/`, `suportes/`, `pre_disparo/`) y
  `config.json` se leen/guardan junto al `.exe`.
