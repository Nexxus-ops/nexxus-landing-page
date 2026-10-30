# CeTe · Landing AV2

Sitio estático bilingüe (`en_US` por defecto y `es_419`), responsive, con captura real del producto y enlaces a registro y acceso. Propuesta comercial académica uniforme de S/80 por empresa al mes, sin cobro implementado.

`guide.html`, `terms.html`, `privacy.html` y `ethics.html` contienen recursos funcionales en ambos idiomas. El contacto usa el canal público del proyecto en GitHub. No se publican testimonios ficticios, cuentas sociales inexistentes ni formularios que simulen enviar mensajes.

```powershell
python -m http.server 5175
```

Abrir http://localhost:5175. `site.js` conserva el idioma y gestiona el menú móvil con atributos ARIA. El HTML incluye navegación por teclado, enlace para saltar al contenido, títulos y metadatos.

La captura `assets/workspace.png` proviene de la ejecución verificada del frontend con datos ficticios. No representa una empresa real. Revisar el destino del frontend en `site.js` si cambia su URL pública.

Verificado en Edge: ambos idiomas, persistencia tras recarga, cuatro páginas del footer, anclas internas, imagen del producto, menú móvil y ancho 390px sin desplazamiento horizontal. La versión pública se actualiza al publicar esta rama.
