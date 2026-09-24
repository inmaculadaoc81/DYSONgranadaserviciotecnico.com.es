DYMASTER SERVICIO TÉCNICO DYSON EN GRANADA
===========================================

Web de una sola página (HTML/CSS/JS estático + función serverless en Vercel)
para DyMaster, servicio técnico y reparación de equipos Dyson con recogida
y entrega en Granada y área metropolitana.

Dominio: https://granadaserviciotecnico.com.es/
Marca: DyMaster Servicio Técnico Dyson en Granada
Ficha de Google: https://maps.app.goo.gl/CnGdQ29rD5q8Q3pM7
Mapa: iframe de Google Maps de la ficha "DyMaster Servicio Técnico Dyson en Granada",
insertado tal cual en la sección de contacto (ancho 100% vía CSS).

DATOS DE CONTACTO
- WhatsApp: +34 649 97 01 28.
- Teléfono: +34 910 05 48 17.
- Recogida a domicilio: https://sis.redsys.es/tiendaWeb/item/NDk4OzI=
  (botón "Solicita tu recogida ahora" del hero, siempre en negro).
- Horario: lunes a viernes de 09:30 a 18:00.
- Política de privacidad: https://kelatos.com/privacy-policy/.

DIRECCIÓN: no se muestra dirección postal. La web indica "Granada y área
metropolitana" y servicio de recogida y entrega; el taller está en Madrid.
Si se confirma una dirección en Granada, añadirla al hero, footer y JSON-LD.

ESTRUCTURA
- index.html: toda la página (hero, ventajas, reparación rápida, confianza,
  servicios, por qué elegirnos, cómo trabajamos, contacto + mapa, FAQ, texto
  SEO, footer, cookies y JSON-LD).
- style.css: base de la plantilla.
- mobile-navigation.css, social-footer.css, cal-booking.css: ajustes compartidos.
- dymaster.css: identidad visual de la marca (una sola capa, sin
  sobrescrituras en cascada).
- dymaster-header-hero.css: cabecera grafito con logotipo blanco.
- dymaster.js: menú móvil (se cierra al pulsar un enlace), formulario y
  preferencias de cookies (clave localStorage "dymaster_cookie_preference").
- dymaster-n8n-chat.js / .css: chatbot n8n con webhook compartido del grupo
  y botón de respaldo.
- api/contacto.js: envío del formulario por SMTP (variables SMTP_HOST,
  SMTP_PORT, SMTP_SECURE, SMTP_USER, SMTP_PASS y CONTACT_EMAIL en Vercel).
- img/: isotipo, patrón e ilustraciones SVG de la marca.
- robots.txt y sitemap.xml apuntan a https://granadaserviciotecnico.com.es/.

PALETA: tecnología, seguridad y reparación.
- Primario azul cobalto eléctrico #1F4FE0 · oscuro #173DB5 · muy oscuro #0F2A80
- Azul noche grafito (cabecera, footer, cookies, sección oscura) #0E1624
- Acento naranja técnico #FF8A33 / #E85D04 (logotipo, líneas de sección,
  números de pasos, detalles sobre fondo oscuro)
- Cian #5CC8FF (ilustraciones SVG) · fondos gris acero #F2F5FA
Excepciones: WhatsApp conserva su verde y YouTube su rojo corporativo.
