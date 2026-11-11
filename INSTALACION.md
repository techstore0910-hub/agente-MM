# Preparación de agente-MM

Estado: código preparado, servicio bloqueado; NO instalado ni probado en vivo.

Fuente: soporte-desplegado/ del paquete-paquete-alumnos-v3-2026-11-11.zip,
commit declarado de origen 0cf75a457ebaa49024289dbddf7a7cbcd9b28001.
El index original se conserva localmente fuera de este repositorio.

Cambios preventivos: bloqueo incondicional de arranque antes de cargar dependencias;
datos bancarios de referencia vaciados; exclusión de archivos .env y logs.
El resto del conocimiento comercial es referencia pendiente de sustituir, sin aprobación
para usarlo con clientes. No retirar el bloqueo hasta estudiar los PLR, aprobar datos,
personalizar respuestas y configurar protección del servicio.

Railway está conectado a main: esta rama de preparación NO debe conectarse ni fusionarse
antes de completar la personalización. Sin claves en el repositorio.

Pendientes: entrevista, materiales PLR, aprobación, personalización, autenticación,
configuración privada y pruebas por etapa. No ejecutar npm test como prueba de calidad:
el paquete solo contiene el script de prueba por defecto que termina con error.
