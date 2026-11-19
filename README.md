# SheFix · Prototipo interactivo para pitch

Prototipo conceptual de una plataforma de contratación de servicios de oficios entre mujeres. **No es un MVP operativo**. Los perfiles, las valoraciones, las credenciales y las guardias 24 h son ficticios. No hay backend, cuentas reales, geolocalización, pagos ni solicitudes enviadas.

## Abrir localmente
Abrí `index.html` en Chrome, Edge, Firefox o Safari. Se necesita conexión solo para descargar las tipografías de Google; sin conexión se usan tipografías alternativas.

## Publicar en GitHub Pages
1. Creá un repositorio público llamado `shefix-prototipo`.
2. Subí `index.html`, `style.css` y `script.js` **a la raíz del repositorio** (podés incluir también este README).
3. Entrá a **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**.
5. Seleccioná la rama `main`, carpeta `/(root)` y guardá.
6. Cuando finalice la publicación, abrí `https://TU-USUARIO.github.io/shefix-prototipo/`.

## Qué mostrar en el pitch
- **Soy Clienta** → Plomería o **Buscar guardia 24 h** → Ver perfil → Solicitar servicio → Enviar solicitud → Seguimiento → Valoración.
- **Soy Proveedora de servicios** → Ver perfil profesional → Activar/desactivar guardia → Aceptar solicitud simulada.

## Archivos
- `index.html`: estructura.
- `style.css`: diseño adaptable a celulares.
- `script.js`: navegación y simulación interactiva.

## Seguridad y privacidad
No introducir datos personales reales en el formulario. La demo no envía ni almacena los datos en un servidor; el contenido del campo de descripción no se conserva tras enviar. **GitHub Pages es alojamiento estático y no proporciona por sí mismo autenticación, pagos, verificación de credenciales o reservas reales.**

## Identidad visual actualizada
Paleta oficial: violeta `#5a3c6d`, lavanda `#ddb2fd`, rosa `#d862a4` y negro ciruela `#110911`. Se aplicó a botones, fondos, tarjetas, estados y marco de la aplicación.


## Actualización: tarifas y checkout
- Las Clientas pueden ordenar los resultados por **mejor valoración** o **menor tarifa de visita**.
- Los perfiles muestran importes **ficticios en pesos argentinos**; la tarifa de visita no incluye reparaciones, materiales ni recargos de guardia.
- Tras solicitar un servicio, aparece un **checkout simulado** de estilo app de movilidad: resumen del precio, selección de tarjeta o billetera virtual y confirmación.
- **No se capturan datos bancarios, no se procesan pagos ni se envían solicitudes reales**. GitHub Pages aloja únicamente esta demostración estática.
- Para pagos reales en un futuro MVP hará falta un proveedor de pagos, backend seguro y cumplimiento normativo.

## Actualización de portada
La primera pantalla muestra «Una app exclusiva para mujeres» y aclara que conecta clientas con mujeres proveedoras de servicios.

## Corrección de actualización en GitHub Pages
Esta versión usa parámetros de versión en `index.html` para evitar que el navegador reutilice `style.css` y `script.js` antiguos. En la columna lateral aparece «Versión 4» como comprobación. Subí los cuatro archivos en la raíz del repositorio y verificá que Pages publique la rama `main` y la carpeta `/(root)` (o la configuración que corresponda). Si no ves Versión 4, revisá la rama y la ruta de publicación.

## Versión 5 — Mensaje de bienvenida

La primera pantalla incorpora: «Elegí contratar a otra mujer. Porque sentirte segura y abrir oportunidades pueden ir de la mano.». Mantiene el distintivo «Una app exclusiva para mujeres» y las funciones previas. El indicador lateral dice «Versión 5».
