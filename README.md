# 📦 Plantilla‑App (HTML + CSS + JS)

Base minimalista para proyectos que generarán código con IA (Codex, ChatGPT, etc.).

## 🧩 REGLAS GENERALES

1. **Separación estricta**  
   - `index.html` → estructura visual  
   - `style.css`  → diseño  
   - `app.js`     → lógica  
2. **Bloques delimitados** con comentarios `🔽 … 🔼`.  
   La IA debe modificar solo el bloque indicado, nunca el archivo entero.  
3. **Sin librerías externas** (CDN, npm, etc.) a menos que se solicite.  
4. **Comentarios claros y en español** sobre cada función o bloque nuevo.  
5. **Nomenclatura coherente**  
   - Clases: kebab‑case (`.tabla-resultados`)  
   - IDs & funciones JS: camelCase (`resultTable`, `calcularTotal`)  

## 🚀 PROMPT BASE PARA IA

```
• Seguí el formato y las reglas descritas en este README y en los encabezados de cada archivo.
• Indica exactamente en qué bloques modificarás código.
• Entrega únicamente los snippets nuevos o modificados, no el archivo completo.
```
