# mis-skills

Mis skills para Claude Code. Ayudo a transformar ideas en proyectos con identidad.

## Skills incluidas

| Skill | Qué hace | Fuente |
|---|---|---|
| `voz-guillermina` | Mi tono de voz. Cercano, claro, rosarino y sin palabras en inglés. También revisa textos y marca errores. | Propia |
| `estrategia-comunicacion` | Mi método en 6 pasos para armar estrategias de comunicación para clientes. | Propia |
| `copy-clientes` | Copys por canal (Instagram, LinkedIn, newsletter, WhatsApp) pensados para generar comunidad. | Propia |
| `frontend-design` | Diseño con criterio propio, sin plantillas. Paleta, tipografía y estructura pensadas para cada proyecto. | [anthropics/skills](https://github.com/anthropics/skills) |

Las skills propias se usan juntas: la estrategia define el mensaje, el copy lo escribe y la voz le da el tono.

## Cómo usarlas

**En la nube (claude.ai/code):** abrí una sesión con este repo seleccionado. Las skills de `.claude/skills/` se cargan solas.

**En tu compu:** cloná el repo y abrí Claude Code adentro de la carpeta:

```bash
git clone https://github.com/guillerminaygelman/mis-skills.git
cd mis-skills
claude
```

Si las querés en todos tus proyectos, copialas a `~/.claude/skills/`.
