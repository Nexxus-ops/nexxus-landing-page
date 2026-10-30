<div align="center">
  <h1> CeTe by Nexxus - Landing Page</h1>
  <p><em>El sistema nervioso central de tu logística MYPE</em></p>

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![Despliegue](https://img.shields.io/badge/Deploy-Render-000000?style=for-the-badge&logo=render&logoColor=white)
</div>

---

## Sobre el Proyecto

Esta es la página de presentación (Landing Page) oficial de **CeTe**, una plataforma SaaS B2B desarrollada por el equipo **Nexxus**. Su propósito principal es comunicar la propuesta de valor comercial, presentar las funcionalidades y la propuesta de suscripción, y servir como puerta de enlace directa hacia la aplicación web principal.

**Sitio publicado:** [CeTe - Landing Page](https://cete-landing-av2.onrender.com/).

## Características Principales

* **Diseño Corporativo (B2B):** Interfaz estructurada bajo la identidad visual de Nexxus, con *Primary Blue* `#0A2540` y una variante naranja `#A94300` para mejorar el contraste de los controles.
* **Responsive Design:** Adaptación a móviles, tablets y escritorio mediante CSS3, sin frameworks externos.
* **Internacionalización (EN/ES):** Inglés predeterminado (`en_US`) y español latinoamericano (`es_419`), con preferencia conservada al recargar y navegar entre recursos.
* **Navegación Fluida (Smooth Scroll):** Enlaces internos a funcionalidades, flujo de trabajo, propuesta comercial y contacto, con menú móvil accesible.
* **Integración Directa con la SPA:** Los *Call-to-Actions* de registro e inicio de sesión enlazan al frontend transaccional publicado.
* **Propuesta Comercial MYPE:** Presentación de una tarifa académica de **S/80 por empresa al mes**, alineada con el modelo del proyecto. El registro actual permite explorar el producto sin ejecutar cobros de suscripción.
* **Vista Real del Producto:** Captura del dashboard obtenida durante la verificación de la aplicación con datos ficticios.
* **Footer Funcional:** Acceso a guía de uso, términos, privacidad y ética, con contenido disponible en ambos idiomas.

## Stack Tecnológico

* **Estructura:** HTML5 semántico.
* **Estilos:** CSS3 (Vanilla puro) con variables globales (`:root`), Grid, Flexbox y media queries.
* **Interacción e Idiomas:** JavaScript para traducciones, persistencia de idioma y menú móvil.
* **Tipografía:** Google Fonts: Roboto para lectura y Montserrat para encabezados.
* **Accesibilidad:** Enlace para saltar al contenido, navegación por teclado, estados ARIA y soporte de movimiento reducido.
* **Alojamiento Actual:** Render Static Site. Los archivos también pueden publicarse en GitHub Pages como sitio estático.

## Instalación y Ejecución Local

La landing utiliza archivos estáticos. Para revisarla mediante un servidor local, ejecutar desde la raíz del repositorio:

```powershell
python -m http.server 5175
```

Abrir [http://localhost:5175](http://localhost:5175). Python 3 es una opción para servir los archivos; también puede utilizarse otro servidor estático.

**Archivos principales:**

* `index.html`: estructura, contenido y enlaces de registro e ingreso.
* `styles.css`: identidad visual, estilos responsive y accesibilidad.
* `site.js`: diccionarios, selección de idioma y navegación móvil.
* `assets/workspace.png`: captura de la aplicación con datos de demostración.
* `guide.html`, `terms.html`, `privacy.html` y `ethics.html`: recursos del footer.

Si cambia la URL pública del frontend, actualizar sus enlaces en `index.html`.

## Verificación de la Versión AV2

La revisión en Edge comprobó ambos idiomas, persistencia tras recarga, los cuatro recursos del footer, anclas internas, carga de la imagen del producto y funcionamiento del menú móvil a 390 px sin desbordamiento horizontal de la página.

## Ecosistema del Proyecto

La Landing Page actúa como la capa de presentación dentro de una arquitectura mayor. El ecosistema de CeTe se compone de:

1. **[Landing Page (Presentación)](https://cete-landing-av2.onrender.com/):** Propuesta de valor, funcionalidades y acceso al producto. [Repositorio](https://github.com/Nexxus-ops/nexxus-landing-page).
2. **[Frontend (App Transaccional)](https://cete-web-av2.onrender.com/):** SPA con Vue.js, Pinia y PrimeVue para inventario, compras, ventas, boletas y despachos. [Repositorio](https://github.com/Nexxus-ops/FrontEnd-CeTe).
3. **[RESTful API (Backend)](https://cete-api-av2.onrender.com/swagger):** Servicios propios en C# y ASP.NET Core, con EF Core y PostgreSQL, ejecutados mediante Docker en Render. [Repositorio](https://github.com/Nexxus-ops/CeTe-Api).
4. **[Informe del Proyecto](https://github.com/Nexxus-ops/Report-CeTe):** Requisitos, diseño, planificación y evidencias académicas.

## Equipo de Desarrollo

Construido para democratizar la tecnología logística de las MYPES peruanas.

* **Desarrollo y Arquitectura:** Equipo Nexxus.

---

*Desarrollado por el equipo Nexxus para el curso de Aplicaciones Web de la Universidad Peruana de Ciencias Aplicadas - 2026.*
