# Alexa Candles — Navidad En Cera

Estado: index personalizado y verificado localmente; pendiente revisión del propietario.
No está desplegado ni habilitado para clientes.

## Procedencia
Fuente común: soporte-desplegado/ del paquete de instalación,
commit declarado de origen 0cf75a457ebaa49024289dbddf7a7cbcd9b28001.
Se conservan las 24 funciones originales; se amplían respuestas e intenciones.

## Oferta confirmada
Alexa representa a Alexa Candles. Navidad En Cera incluye cuatro libros PDF por $90 MXN:
Navidad en Cera 1, Navidad en Cera 2, Colecciones y Kits Navideños y
Taller de Velas — Materiales, Moldes y Herramientas.
Todo es digital. Entrega por WhatsApp después de validación aprobada del comprobante.
Transferencia y depósito OXXO. Sin permiso para revender los documentos.
Lista de proveedores separada, sin oferta activa ni precio configurado.

## Alcance
Conservar el lector y el funnel existentes, incluido su tratamiento automatizado de rechazos.
El soporte recibe texto; no valida pagos, no altera resultados y no entrega archivos por sí mismo.
La atención humana la realiza el propietario mediante revisión manual en ManyChat.

## Configuración pendiente
SERVICIO_HABILITADO permanece en false: se impide atender tráfico y arrancar el servidor.
Antes de habilitar, revisar contenido, configurar autenticación y límites, variables privadas,
conexiones y pruebas por etapa. Railway sigue conectado a main; no fusionar antes de revisión.
OPENAI_API_KEY se configurará por mecanismo seguro, nunca en código ni repositorio.
PAGO_BANCO, PAGO_TITULAR y PAGO_CLABE son nombres de variables privadas pendientes;
la respuesta de transferencia no muestra campos vacíos si faltan datos.
No hay enlaces de entrega ni datos bancarios codificados.

## Verificación actual
Sintaxis aprobada. Pruebas locales con dependencias simuladas: 62 consultas de intención,
22 respuestas directas, entradas texto/mensaje/message, errores, límite de longitud,
bloqueo 503 y respuestas de IA simuladas (correcta, vacía y error).
No son pruebas de HTTP real, inferencia real, importación n8n, ManyChat o circuito E2E.
