# 📦 Plantilla‑App (Simple)

Estructura mínima para proyectos HTML + CSS + JS mantenidos con IA (Codex, ChatGPT, etc.).

## 🗂️ Carpetas / Archivos incluidos

| Ruta           | Uso                                             |
|----------------|-------------------------------------------------|
| `index.html`   | Estructura visual (HTML)                        |
| `style.css`    | Diseño (CSS)                                    |
| `app.js`       | Lógica (JavaScript)                             |
| `/img/`        | (vacío) Guarda logos o imágenes estáticas       |
| `/modules/`    | (vacío) JS extra cuando `app.js` se haga grande |
| `.gitignore`   | Archivos a excluir del repo                     |
| `LICENSE`      | MIT                                             |

*(No se incluyen carpetas de tests ni configuraciones avanzadas para mantenerlo simple).*

## 📏 Reglas que la IA **debe** seguir

1. **Separación estricta**  
   `index.html` (HTML) | `style.css` (CSS) | `app.js` (JS)
2. **Bloques marcados** con `🔽 ... 🔼`  
   IA modifica solo dentro de esos bloques.
3. **Cero librerías externas** salvo que se solicite.
4. **Comentarios breves en español** antes de cada función o bloque.

## 🎤 Prompt base para pedir cambios a la IA

> **INSTRUCCIONES GENERALES:**  
> • Mantener formato y reglas descritas arriba.  
> • Entregar solo el **snippet** nuevo o modificado, indicando nombre de archivo y bloque.  
> • No reescribir archivos completos.  
> **CAMBIO SOLICITADO:**  
> _\<describe tu cambio aquí, por ejemplo: “Agregar campo input para ‘Monto Neto’ debajo del botón ‘Calcular’ y actualizar cálculo en app.js”>_

Copia este prompt, ajusta el cambio que querés, y pegalo en Codex o ChatGPT. La IA responderá con los fragmentos exactos que debés copiar y pegar. ¡Así trabajás rápido sin romper nada!