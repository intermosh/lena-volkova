# _plantilla — Nuevo Setting
*(copiar este archivo, renombrar y completar; el sistema lo descubre
automáticamente al listar /settings/)*

---
tag: `nombre_setting`
uso: [una línea: cuándo aplica este setting]
planos:
- [plano característico 1]
- [plano característico 2]
- [plano característico 3]
---

## Instrucción técnica
```text
[Prompt técnico base en inglés: iluminación, composición, grano,
atmósfera, prohibiciones. Este bloque se inserta verbatim en el
prompt final.]
```

## Notas de escalado
- El bloque de cabecera (tag/uso/planos) es obligatorio y es lo único
  que lee el sistema antes de decidir.
- Mantener prohibiciones explícitas al final del bloque técnico
  ("Do not add...").
- Un setting = un look. No mezclar dos estéticas en un archivo.
