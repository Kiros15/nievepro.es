# NievePro

Web estática de NievePro preparada para GitHub + Vercel.

## Incluye
- Homepage responsive con estética NievePro aprobada.
- Fotografías reales de nieve/montaña mediante Unsplash.
- Secciones Ski, Snowboard, Material, Guías, Estaciones y Blog.
- SEO técnico básico: title, description, canonical, Open Graph, robots y sitemap.
- JSON-LD básico para WebSite.
- Espacios preparados para publicidad/AdSense.
- Páginas de Aviso legal, Privacidad, Cookies y Contacto.
- Diseño mobile-first y menú móvil.

## Publicación
Sube todo el contenido de esta carpeta a la raíz del repositorio GitHub `Kiros15/nievepro.es` y Vercel desplegará automáticamente el cambio si el proyecto está conectado al repositorio.

## Importante antes de monetizar
Completa los datos reales del titular en Aviso legal, configura el email de contacto y, antes de activar analítica/AdSense, añade el sistema de consentimiento de cookies y los identificadores de las plataformas.

## Analítica y monetización
Esta versión incluye:
- Google Analytics 4: `G-CL13EHQFR0`
- Google Tag Manager: `GTM-WD9BML4Z`
- Google AdSense: `ca-pub-2781521462195370`

Los tags se han añadido a las páginas HTML del sitio.

## V4 — SEO, Search Console, AdSense y consentimiento
- `ads.txt` incluido con el publisher de AdSense.
- `sitemap.xml` actualizado y enlazado desde `robots.txt`.
- Páginas legales: aviso legal, privacidad, cookies y contacto.
- Banner de consentimiento para cookies no esenciales.
- Google Analytics se carga tras aceptar analítica.
- Google Tag Manager y AdSense mantienen los códigos proporcionados.

### Google Search Console
1. En Search Console añade la propiedad `nievepro.es` (preferiblemente propiedad de dominio).
2. Google te dará un registro TXT único para verificar el dominio.
3. Añade ese TXT en Arsys sin tocar MX/SPF/DKIM.
4. Verifica la propiedad y envía `https://nievepro.es/sitemap.xml`.

El TXT de verificación no se puede pre-rellenar porque Google genera un valor distinto para cada propiedad/cuenta.
