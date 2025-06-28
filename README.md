# 📦 Plantilla‑App (HTML + CSS + JS)

Plantilla mínima pero **completa** para apps front‑end simples generadas (o mantenidas) con IA.

## 📁 Estructura de carpetas

```
plantilla-app/
├─ index.html          # Estructura visual
├─ style.css           # Diseño (CSS)
├─ app.js              # Lógica (JS)
├─ .gitignore          # Archivos a excluir del repo
├─ LICENSE             # MIT
├─ README.md           # Esta guía
│
├─ /img/               # Imágenes e íconos estáticos
├─ /modules/           # Scripts JS reutilizables (se importan desde app.js)
├─ /data/              # Archivos de datos (JSON, CSV, etc.)
├─ /docs/              # Documentación extensa, diagramas, mockups
└─ /tests/             # Pruebas automáticas (Jest u otra)
```

## 🧩 Reglas para IA y colaboradores

1. **Separación estricta**
   * `index.html`  = estructura y contenido visual (sin lógica ni estilos)
   * `style.css`   = diseño (sin lógica)
   * `app.js`      = lógica principal
   * Archivos en `/modules/` cuando el código JS pueda reutilizarse
2. **Bloques delimitados** con comentarios `🔽 … 🔼`.
   * La IA debe modificar solo el bloque indicado, nunca sobreescribir todo el archivo.
3. **Sin librerías externas** (CDN, npm, etc.) excepto si el autor las solicita.
4. **Comentarios breves en español** antes de cada función o bloque nuevo.
5. **Nomenclatura coherente**
   * Clases CSS → kebab‑case (`.tabla-resultados`)
   * IDs y funciones JS → camelCase (`resultTable`, `calcularTotal`)
6. **Pull Requests pequeños** y descripciones claras (`feat: añadir export PDF`).

## 🚀 Prompt base sugerido para Codex / ChatGPT

```
Usá la plantilla-app. Respetá:
• Separación de archivos y bloques 🔽 … 🔼
• Comentarios descriptivos
• No uses librerías externas salvo pedido
• Entregá solo los snippets modificados (no todo el archivo)
```

## 🧪 Tests (opcional)

Si incluís Jest:

* `npm install --save-dev jest`
* Crear tests dentro de `/tests/` con nombre `*.test.js`
* Ejecutar `npm test`

---

¡A clonar esta template y a codificar rápido! 💪
