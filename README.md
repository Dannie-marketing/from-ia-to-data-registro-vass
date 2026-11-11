# Landing VASS — From IA to Action (versión autocontenida)

## Qué se corrigió
- La landing está en un **solo archivo HTML**. Banners y estilos están dentro del propio archivo, así que no se rompe al abrirla individualmente.
- Se conserva la combinación blanco / negro de la V11, Titillium Web y los textos originales ya aprobados.
- El `data-tf-live` exacto que entregaste sigue presente. No se recrea ni se sustituye el formulario.
- Si Typeform no se puede cargar, verás un mensaje en el espacio del formulario, no una página vacía.

## Cómo revisar
1. Abre `index.html` en un navegador de escritorio o teléfono (mejor después de poner el HTML en una URL pública de prueba HTTPS).
2. En un HTML local (`file://`) el script externo Typeform puede estar bloqueado. Esto no afecta el resto de la página.
3. Para ponerla online, sube todos los archivos a GitHub Pages/Netlify. El HTML también funciona por sí solo, sin `assets/`; el archivo `privacidad.html` se conserva en el paquete por el enlace del aviso.
4. Haz un registro de prueba y confirma en Typeform que llegó la respuesta antes de enviar la landing a tus asistentes.

## Pendiente
- Prueba de envío real en HTTPS.
- Verificación final de autorizaciones y condiciones de privacidad dentro de Typeform.
- La descripción editorial sigue siendo la trabajada en versiones anteriores, no se ha vuelto a transcribir de Beyond Dreamforce.
- Desactivar robots noindex/nofollow solo al publicar definitivamente.
