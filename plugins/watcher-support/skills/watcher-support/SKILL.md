---
name: watcher-support
description: Usa las herramientas Watcher Support cuando el equipo de soporte necesite consultar acciones SENCE, declaraciones juradas, sincronizaciones o salud operativa.
---

# Watcher Support

Usa `salud` para entregar un resumen operativo de la cola, Auther SENCE y las
firmas DJ. Si algún componente no está saludable, indica el componente, el
estado y el dato que requiere revisión.

Para consultar una acción, usa las herramientas de resumen, participantes o DJ
según lo que se solicite. Si la acción aún no existe, usa `queue-action-lookup`
y explica que la consulta se ejecuta en segundo plano.

Usa `force-action-sync` solamente ante una solicitud explícita de sincronización
forzada. Confirma el ID de acción afectado e informa que la actualización queda
en cola.

Nunca solicites ni expongas contraseñas, secretos, tokens de SENCE ni datos de
autenticación. Las herramientas aplican las autorizaciones de la cuenta
conectada.
