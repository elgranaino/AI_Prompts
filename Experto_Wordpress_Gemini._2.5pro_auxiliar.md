## Prompt Auxiliar — Organización de Fuentes WP

Tu tarea es recopilar, estructurar y organizar en formato **CSV y JSON** la información clave de las siguientes fuentes de referencia de WordPress y su ecosistema:

### Fuentes principales (Core & Docs)
1. https://codex.wordpress.org/
2. https://developer.wordpress.org/
3. https://developer.wordpress.org/plugins/
4. https://developer.wordpress.org/themes/
5. https://make.wordpress.org/core/
6. https://make.wordpress.org/cli/handbook/

### Fuentes de plugins y optimización
7. https://woocommerce.com/document/
8. https://yoast.com/help/
9. https://litespeedtech.com/support/wiki/doku.php/litespeed_wiki:cache:lscwp
10. https://docs.wordfence.com/en/Wordfence_FAQ

### Hosting, performance y seguridad
11. https://kinsta.com/blog/
12. https://wpengine.com/resources/
13. https://sucuri.net/guides/
14. https://www.cloudflare.com/learning/
15. https://www.smashingmagazine.com/tag/wordpress/

---

### Instrucciones
1. Para cada fuente, extrae:
   - `Nombre`
   - `Tipo` (Doc oficial, Blog técnico, Guía práctica, Seguridad, Hosting)
   - `URL`
   - `Resumen` (máx. 3 frases claras con la utilidad principal)
   - `Última actualización` (si está disponible en la fuente)
   - `Categoría` (Core, Plugins, SEO, Seguridad, Performance, Hosting, Marketing)

2. Genera dos salidas:
   - **CSV** con columnas:  
     `Nombre,Tipo,URL,Resumen,Última actualización,Categoría`
   - **JSON** con estructura:  
     ```json
     {
       "nombre": "",
       "tipo": "",
       "url": "",
       "resumen": "",
       "ultima_actualizacion": "",
       "categoria": ""
     }
     ```

3. Reglas de extracción:
   - Si falta la fecha de última actualización, deja el campo vacío.
   - No inventes información.
   - Resume solo con lo explícito en la fuente.
   - Prioriza datos técnicos y aplicables a proyectos WordPress reales.

4. Formato de salida:
   - Primero CSV plano.
   - Luego JSON estructurado.
   - Sin comentarios adicionales ni publicidad.
